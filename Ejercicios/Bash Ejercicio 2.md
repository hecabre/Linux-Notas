`#!/bin/bash`
`run=true`
`while $run; do`
    `echo "IP: $(hostname -I | awk '{print $1}')"`
    `read -n 1 -t 1 answer`
    `if [ "$answer" == "1" ]; then`
      `run=false`
    `fi`

`done`
`echo "Fin"`
Password bandit game: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc lvl8