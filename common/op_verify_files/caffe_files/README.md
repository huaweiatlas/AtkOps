EN|[CN](README.zh.md)

This directory is used to store the files related to the Caffe custom operator, including two categories:

(1) A list of unsupported operators generated by the network analysis module

(2) A single-operator model generated by the get_caffe_model.py file that only includes the input layer and the custom operator layer. The Op_verify.py and net_verify.py files will select the corresponding single-operator model based on the caffe_operator_type field in the config.json file.

