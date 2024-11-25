XML Serialization and Deserialization Example
This project demonstrates how to use XML serialization and deserialization in C#. It covers the following key features:

Features
Serialize an object to an XML string:
The project shows how to convert an object of the Member class to an XML string and display it.

Deserialize an XML string to an object:
It also demonstrates how to convert an XML string back into an object using XML deserialization.

Serialize a list of objects to an XML file:
A list of Member objects is serialized and saved into an XML file (sample04.xml).

Deserialize an XML file to a list of objects:
The project shows how to read data from an XML file (sample04.xml) and convert it back into a list of Member objects.

Serialize an object to an XML file:
A single Member object is serialized and saved into a file (sample02.xml).

Deserialize an XML file to a single object:
The project demonstrates how to read and deserialize data from an XML file (sample01.xml) into a single Member object.

Requirements
C# (Any version supporting .NET Framework or .NET Core)
Visual Studio or any other C# IDE
Usage
Clone or download the project.
Build and run the project.
The program will:
Serialize a Member object to an XML string.
Deserialize that XML string back to a Member object.
Serialize a list of Member objects to an XML file.
Deserialize that XML file back into a list of Member objects.
Sample Output
When you run the project, you'll see XML output on the console, showing the serialized Member object.

Example output:

xml
Copy code
<?xml version="1.0" encoding="utf-8"?>
<Member>
  <Name>John</Name>
  <Email>john@gmail.com</Email>
  <Age>30</Age>
  <JoiningDate>2024-11-25T10:15:30.9999999</JoiningDate>
  <IsPlatinumMember>false</IsPlatinumMember>
</Member>
