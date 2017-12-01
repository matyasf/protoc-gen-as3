How to use?

protoc --plugin=protoc-gen-as3="path/to/protoc-gen-as3[.bat]" --as3_out=output-path your.proto

See http://code.google.com/p/protoc-gen-as3/ for more information.

How to compile from source?

1. mvn clean install on the pom.xml in buildTools/protoc_2_6_1/java/pom.xml This will generate the protoc dependency for the main project.

2. mvn clean install on the pom.xml in this directory.