AirBnb CLONE
_______________________________________________________________________________________________________

pROJECT dESCRIPTION
This is a recreation of the AirBnB site, from back-end data management to the front-end user interface.
We are using a command line interpretor to access objects that will store user data.
Users can use the console to :
1. create objects
2. update object attributes
3. remove objects
4. list all objects
5. store and read data from a .json file.

________________________________________________________________________________________________________

########################################################################################################
To start the console, type './console.py' on the command line 
--------------------------------------------------------------------------------------------------------
Supported commands are:

create <class name>	: to create an object of the declared class by the user
show <class name>	: display the object information if it exists
destroy <class name>	: delete the object if it exists
all <class name>	: dislplay all instances
update <class name><id>
	<attribute name>
	<attribute value>: update an instance of a previously declared object

the console also supports the following command formats:
<class name>.all()		: display all instances of the specified class;
<class name>.count()		: display the number of instances of the specified class;
<class name>.show(<id>)		: display the instance with correct id and class;
<class name>.destroy(<id>)	: delete the instance with correct id and class;
<class name>.update(<id>, 
		<attribute name>, 
		<attribute value>): update an instance of the given class and id with the new attribute;
<class name>.update(<id>, 
		<dictionary representation>): update an instance of the given class and id with a 
		dictionary of key value pairs that will be new attributes for the objects.
