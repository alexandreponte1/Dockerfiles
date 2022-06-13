
## Comandos rancher desktop

nerdctl compose up -d

nerdctl container rm -f $(nerdctl container ls -aq)

nerdctl image rm $(nerdctl image ls -qa)