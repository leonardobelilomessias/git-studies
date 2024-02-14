Qunado digitamos o comando "git init" indicamos que o git vai controlar os aquivos naquela pasta e subpastas.

na criação de um arquivo ele fica em status untracked  ou seja o git não esta rastrando esse arquivo.

os arquivos geralmente ficam untracked
para traquear os arquivos é nesserario passar para a area de stage
stage é uma area de transferencia que já pode ter alguns arquivos controlados
commit é uma snapshot que temos acesso do contexto e status do arquivos. Os arquivos que passaram para o estado commited e é alterado passa por estado modified ou seja precisa ser tackeado e staged e commited novamente
então o fluxo fica podendo ser:
- untracked
- staged
- commited
- modified

Toda vez que 