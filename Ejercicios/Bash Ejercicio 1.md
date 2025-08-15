`#!/bin/bash`

`PASTEL_1="\033[38;5;217m"`
`PASTEL_2="\033[38;5;153m"`
`PASTEL_3="\033[38;5;151m"`
`PASTEL_4="\033[38;5;229m"`
`PASTEL_5="\033[38;5;183m"`
`PASTEL_6="\033[38;5;216m"`
`PASTEL_7="\033[38;5;189m"`
`PASTEL_8="\033[38;5;175m"`
`PASTEL_9="\033[38;5;194m"`
`PASTEL_10="\033[38;5;223m"`

`RESET="\033[0m"`
`COLORS=(${PASTEL_1} ${PASTEL_2} ${PASTEL_3} ${PASTEL_4} ${PASTEL_5} ${PASTEL_6} ${PASTEL_7} ${PASTEL_8} ${PASTEL_9} ${PASTEL_10})`

`for color in "${COLORS[@]}"; do`
    `echo -e "${color} Este es un nuevo color ${RESET}"`
`done`

