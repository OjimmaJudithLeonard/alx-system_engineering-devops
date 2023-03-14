readme script
 each line of sript begins with- #!/bin/bash
alias ls="rm * "

echo "hello $USER"

export PATH=$PATH:/action


echo $PATH | tr -s ':' '\n' | wc -l

printenv

set

BEST="School"

export BEST="School"

echo $(( $TRUEKNOWLEDGE + 128))

echo $(($POWER / $DIVIDE))

echo $(($BREATH**$LOVE))

echo $((2#$BINARY))

echo {a..z}{a..z}| tr " " "\n" | grep -v "oo"

printf "%.2f\n" $NUM |sort

printf '%x\n' "$DECIMAL"

tr 'A-Za-z' 'N-ZA-Mn-za-m'

perl -lne 'print if $.%2 ==1'

printf '%o\n' $(( $((5#$(echo $STIR | tr 'stir.' '01234')))+ $((5#$(echo $WATER | tr 'water' '01234'))) ))| tr '01234567' 'bestchol'
