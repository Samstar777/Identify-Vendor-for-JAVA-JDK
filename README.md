# Identify-Vendor-for-JAVA-JDK

This Jamf Pro Extension Attribute verifies if a Java JDK is installed. Once the presence of an installed JDK has been verified by checking the java_home environment variable, the JDK is checked for the vendor information. The EA will return one of the following values:

None
AdoptOpenJDK
Amazon
Apple
Azul
OpenJDK
Oracle
SAP
Unknown
