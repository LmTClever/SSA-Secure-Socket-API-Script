#Note: The "move_to_sslsplit_in_ssa-daemon" is a directory that contains pxyconn.c, that is later used in the process. You do not need to modify the file or do anything with that directory. 
#Also, please DO NOT DELELTE THE DIRECTORY OR FILE EITHER.

#Steps to install and launch SSA
#-----------------------------------------------------------------------------------------
#1. Grant executable permission to "install_ssa.sh" script with the following command:

chmod +x install_ssa.sh 

#2. Execute the "install_ssa.sh" script with the following command and it will automate the configurations for you:

./install_ssa.sh

#3. After the execution of the "install_ssa.sh" script  is done, start the TLS service by going to the ssa-daemon directory. You can do this with the following commands:

cd ssa-daemon
./tls_wrapper
