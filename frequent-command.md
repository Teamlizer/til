# Frequent Command
- Get PID of process at port **lsof -i :443**
- Kill process with PID **kill -9 11234**
- Check outgoing/incomming request at specific port, specific ethernet card **sudo tcpdump -i en0 tcp port 3306 -vv -X**


### fasd
Quick access file, directory

alias a='fasd -a'        # any
alias s='fasd -si'       # show / search / select
alias d='fasd -d'        # directory
alias f='fasd -f'        # file
alias sd='fasd -sid'     # interactive directory selection
alias sf='fasd -sif'     # interactive file selection
alias z='fasd_cd -d'     # cd, same functionality as j in autojump
alias zz='fasd_cd -d -i' # cd with interactive selection

- Open pdf **open `sf pdf`**, then choose number
- Change directory **zz**, then choose number
- Open file with vi **vi `f -i`**, then choose number
