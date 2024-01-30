# connect-avro-library

This project is to create a docker image that contains 
the libraries of confluent avro libraries. 

To use the image in your project you may copy the contents
of the /lib folder of this image. 

This may be useful when the confluent avro libraries are not 
available by default, and they need to be added later. 
For instance, debezium connect image does not have the 
confluent avro libraries by default.