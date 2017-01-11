# Wsdl2Jar
===================================================================================================
The script/project can be used to generate a jar file if a WSDL file is given as input.
It used axis-wsdl2java to acheive the same.

===================================================================================================

Steps to use the script file.
- Run build.gradle
- The gradle.properties file contains 3 properties,
	wsdl : Give a comma seperated list of wsdl files needed. Eg: some.wsdl,someOther.wsdl
	jar_name : name of the jar file to be generated
	wsdlPackageMapping : This is optional. If there are cases where you need to add a package mapper use this. eg: some.wsdl:NstoPkg.properties
	This can also take comma seperate values
