# protobuf_demo
This is the demo for python(3.x). It is forked and adjusted based on google's original example(https://github.com/machinalis/protobuf-python3/tree/master/examples) which uses on Makefile and python(2.x). 

Please install protoc first:

1, download https://github.com/protocolbuffers/protobuf/releases/download/v3.6.1/protoc-3.6.1-linux-x86_64.zip

2, unzip protoc-3.6.1-linux-x86_64.zip

3, sudo ln -s ~/protobuf/bin/protoc /usr/bin/protoc

Run the demo

1, protoc --python_out=. addressbook.proto

2, python3.6 add_people.py addressbook

3, python3.6 list_people.py addressbook


