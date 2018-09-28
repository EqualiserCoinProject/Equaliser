In order to run EQLI blockchain, issue the following at the command line. 

komodod -ac_name=EQL 

in the /komodo/EQL directory, create EQL.conf with the desired parameters. 

GEN=1 and GENPROCLIMIT=1 are both recommended, as this will enable the daemon to process blocks as a full node. Leave them out if
you do NOT want your node to mine. 
A sample EQL.conf follows

rpcuser=somerandomdude
rpcpassword=somethingnotmemorablebutverylong
gen=1
genproclimit=1
allowip=localhost
addnode=someknownnode
