### Halide Generator Templates
This folder primarily contains Halide generator templates for compute-intensive algorithms, including matrix multiplication, matrix addition, convolution, and Gaussian pyramids. These templates are parameterized by inputs and outputs to accommodate changes in hardware as well as input and output sizes.

### XML Examples and Scripts
This folder also includes two examples of XML files along with several scripts that serve different purposes:

- `get_single_xml_data.py` and `get_xml_data.py`: These scripts are used for extracting parameters from single and composite models, respectively. The extracted data is outputted into an Excel spreadsheet.

- `main.py`: This script modifies the main file generated by Simulink Coder, making necessary adjustments based on specific requirements.

- `single_module.py`: This script is designed to modify Simulink Coder function files and Halide generator templates. It automatically updates these elements based on the parameters obtained, ensuring that changes are applied consistently and accurately.



