#Weekly application restart- in PROD

Working in I4 AND I5 ***** 


Shutdown INFORM
Need to shut down Batch and Interactive

Batch *** START HERE ***
1 - Run this from the command prompt on I004 and I0005
@inf_command:inf_shutdown 

from prompt - chkprog (make sure OT02 is down, then proceed)

Interactive
3 - Menu - IMFS
Options 1, 4, 1, and answer the prompts

Verify all is down
4 - From command line prompt, I0004 ONLY 
APPDOWN-------IMV ***ONLY ON PRODUCTION SIDE ***

APPDOWN-------
Go thru and make sure INF and IMV are down

Options: INF  3 and 3

Options: IMV 2 and 3


Start INFORM back up
Batch
6 - Menu option IAPR, 
say Yes to start all
Do on both I0004 and I0005
Interactive
8 - Menu - IMFS 
Options 1, 3, 1 and answer prompts

Verify all is up
From the command prompt, I0004 or I0005

9 - CHKPROG - to see if all of batch is back up

10 - CHKINTER - to see if all of Interactive is back up

