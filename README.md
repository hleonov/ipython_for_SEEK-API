Example ipython notebook to use the SEEK writeAPI (SEEK version 1.6.0+, https://github.com/seek4science/seek).
 
Creates a Project --> Investigation --> Study --> Assay(s) --> Assets, all based on each other, which result in the following ISA structure:
![alt text](https://raw.githubusercontent.com/hleonov/ipython_for_SEEK-API/master/ISA_Structure.png)

The Event and the Publication are not included in the code (Event is possible to add, Publication is not yet in the writeAPI code). 

In addition, contains examples on how to POST assets both based on uploads, or remote URLs, and an Assay with links to pre-existing assets.

'token' should contain a base64 encrypted "username:password" string to your SEEK instance. 


