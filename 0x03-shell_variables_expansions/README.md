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
#9. Divide and rule
echo $((POWER/DIVIDE))
#10. Love exponent breath
echo "$((2#$BINARY))"
#11. Binary to decimal
echo "$((2#$BINARY))"
#12. Combinations
printf "%s\n" {a..z}{a..z} | grep -v "oo"
#13. Floats
printf "%.2f\n" $NUM
#14. Decimal to hexadecimal
printf "%x\n" $DECIMAL
#15. Rot13 Encryption
tr 'a-zA-Z' 'n-za-mN-ZA-M'
#16. Odd
cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2
#17. Water and stir
printf "%o\n" $((5#`echo $WATER | tr 'water' '01234'` + 5#`echo $STIR | tr 'stir.' '01234'`)) | tr '01234567' 'behlnort'
