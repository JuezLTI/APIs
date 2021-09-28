
# PEARL

The file PEARL.json contains a JSON Schema definition of PEARL

PEARL stands for Programming Exercise Assessment Reporting Language

This definition was inspired by the XML Schema definition of ERL in ERL.xsd

This folder contains examples of valid PERL serializations  

You can test these serializations using the REPL of AJV: https://ajv.js.org/ 

You must declare the specification on the command line, as in this example

    ajv  -s PEARL.json -d ./samples/ex_request_delayed.json
