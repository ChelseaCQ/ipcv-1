#  Horizontal Scaling for an Embarrassingly Parallel Task:Blockchain Proof-of-Work in the Cloud
- created using python3 ,boto3 and fabric3 module
- See the included report for a full writeup
#   Environment configuration
- use aws CLi , input configuration data written in config and credentials
- set path for cloudkey.pem(~/.ssh/cloudkey.pem)
- install module boto3 and fabric3 by 'pip install boto3' and 'pip install fabric3 '
#  Setup
- Proof-of-work: input difficulty level as argv , command:python pow.py level
- Multiprocessing PoW: command 'python multiproc.py' to run, difficulty level can be changed in function worker_1
- Single VM: set path for fabfile-single.py (required for using fabric module)  ,rename it by 'fabfile.py',command: fab single
- Parallel VMs: set path for fabfile.py, input difficulty level as argv,command :fan -P parallel :level,numbers of instanced can be changed in function parallel(dif)
