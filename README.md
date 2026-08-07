# DevOps

##shell scripting part 2####

#######custom node script to detect nodeHealth#########

1. we learnt about two good prctices always write the metadata info.
2. whenever you start writting the script always write the script in the debug mode.

##########command to know all the processes in your Virtual Machine#########
1. ps -ef
2. ps -ef | grep "amazon" this command is split intto two parts first ps -ef and second is grep "amazon" so, ps -ef is printing all the info about the processes that are running on virtual machine. grip command only fetches the info that is required from the outputs generated. let's say you have 100 lines of code/employee names and you want to fetch line 55/shradha and 56/Harsh, then we can use grip command in that case. why do we use | it fetches the output from the first command and gives to second one.

######## pipe command ###########
whenever we are using pipe command make sure you use set -e, set -o pipefail
set -e is used when we want to exit the script when there is an error.
