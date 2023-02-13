## YAML
It is ain't of markup language.
**Uses of YAML
* Data format used to exchange data.
* Similar to XML and Json.
* It is basically human readable language that are used to represent data.
* In YAML you can only store data not command.
* Data serialisation language : YAML, JSON, XML.
* These are used in :- configuration file like Docker , Kubernetes. and Logs caches.
**Benifits
* Simple and easy to read.
* Indentation is important.
* Easily to convert from XML to json or Json to Yaml etc.
* More powerful to represent complex data.
* Indentation and spaces are very much important.
* By --- we can separate different items in Yaml language and if we want to end the yaml file we need to enter ... 

**Datatypes of YAML
* String Variables: myself: "Asmita Bisoi" job: "Software"
* Integer Datatypes: Marks: 80, 
* Float Datatypes: maths: 76.9
* booleanvalues: NO # n, N, true, flase, False, FALSE

**Specify the type
* zero: !!int 0
* PositiveNum: !!int 876
* NegativeNum: !!int -98
* binaryNum: !!int 0101
* octalNum: !!int 06543
* hexa: !!int 0*45

**How to store multiple line in a single line
* Bio: |
Hey!! My name is Asmita Bisoi
im very nice girl.

**How to set multiple lines into single line in yaml
* Bio: >
Hey,
how are u dude

**Nested mappings: map within map
name: Asmita Bisoi
role:
  age: 24
  job: software
  home: odisha
### same as
name: Asmita Bisoi
role: {age: 24, job: software, home: odisha}



  
  
