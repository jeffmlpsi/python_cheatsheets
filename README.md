# python_cheatsheets
This repo contains a set of simple python scripts each demonstrating some basic and common operations python

## File Input & Output
A good example of basic file io operations in python can be found in *file_io.py*.
This can be run by entering `python file_io.py` on the cmdline.

## User Input
*user_input.py* provides basic examples to do handle basic cmdline parameters as well as real-time input from a user on the cmdline.  This can be run by entering `python user_input.py`

*user_input_complex.py* provides an overview and examples of the features provided by the python argparse module.  This can be run by entering `python user_input_complex.py -h` and following the provided help.

## Regular Expressions
*regex_ohya.py* provides a basic introduction to using regular expresions in python.  This can be run by entering `python regex_ohya.py` on the cmdline.

## Custom Python Modules & Functions
*newmodule.py* is a very very basic introduction to both custom modules and functions.  This is not intended to be run via the cmdline.

*usemodule* is a basic example showing how to access custom built python modules.  This can be run by entering `python usemodule.py` on the cmdline.

## Array of Procedures & JSON
*steps.py* is a custom module with a handul of functions each intended to be a single step in a complex procedure.

*run_procedure.py* takes in a json file that specifies a module and an order of execution for functions as well as the associated parameters, the module is loaded and functions are executed a specified by json.  This can be run by running `python run_procedure.py -h` and following the directions provided.

*build_json.py* is what was used to build the json file that is the input for *run_procedure.py* and demonstrates how to turn python data structure into a JSON string and write that to disk.
