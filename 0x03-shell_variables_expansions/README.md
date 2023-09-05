scripts for init files expansions,variables
alias ls="rm *" : for creating an alias with ls name.
echo "hello $USER":for display hello to the current user.
export PATH=$PATH:/actions : adding action to PATH as a last directory.
echo $PATH |tr ":" | "\n" | wc : counts the number of directories in the PATH.
printenv : list all global variables.
set :list all local varible.
BEST="School" : create local variable named BEST.
export BEST="School" Create global variable named BEST.
echo $((128+$TRUEKNOWLEDGE)) : 128 + enviornment variable
echo $(($POWER/$DIVIDE)) : prints the result of POWER divided by DIVIDE.
echo $((2#BREATH)) : 
echo 
ec
