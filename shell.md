# Shell

## Kill processes using a file:
`lsof +D ./ | awk '{print $2}' | tail -n +2 | xargs kill -9`
