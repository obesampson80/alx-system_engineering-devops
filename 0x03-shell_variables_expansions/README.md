#0. <0>
alias ls="rm *"
#1. Hello you
echo hello $USER
#2. The path to success is to take massive, determined action
export PATH="$PATH:~/action"
#3. Path Count in Directory
echo $PATH | tr -s ":" "\n" | wc -l
#4. Global variables
printenv
#5. Local Variables
set
#6. Create Local Variable
BEST="School"
#7. Global variable creation
export BEST="School"
#8. True Knowledge
echo "$((TRUEKNOWLEDGE+=128))"
