#template
This folder primarily contains Halide generator templates for compute-intensive algorithms, 
including matrix multiplication, matrix addition, convolution, Gaussian pyramids, and more. 
These templates are parameterized by inputs and outputs to accommodate changes in hardware 
as well as input and output sizes.
#script
This folder primarily contains two examples of XML files along with some scripts for 
extracting data and updating files.
get_single_xml_data.py and get_xml_data.py are scripts for extracting parameters from single 
and composite models, respectively, outputting the results in an Excel spreadsheet. main.py 
is a script for modifying the main file generated by Simulink Coder. 
single_module.py is a script for modifying Simulink Coder function files and Halide generator 
templates, capable of automatically updating them based on the parameters obtained.
