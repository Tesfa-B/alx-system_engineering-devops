scripts for init files expansions,variables
alias ls="rm *" : for creating an alias with ls name.
echo "hello $USER":for display hello to the current user.
export PATH=$PATH:/actions : adding action to PATH as a last directory.
echo $PATH |tr ":" | "\n" | wc : counts the number of directories in the PATH.
printenv : list all global variables.
set :list all local varible.
BEST="School"
export BEST="School"

