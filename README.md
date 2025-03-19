 <h1 align="center">
 Boas práticas na utilização do GitHub. <br>
 </h1>

 - *No mundo do desenvolvimento de software, manter um padrão de commits claro e consistente é fundamental para a organização e rastreabilidade do código.


## Os principais comando do dia a dia.

 - git status.
    - ### Verifica se ha alterações
 - git add .
    - ### Adiciona o arquivo  
 - git add path file.
   - ### Adiciona o arquivo somente o arquivo mencioando no path caminho 
 - git commit -m"
   - ### Descrição". Descrição das alterações
 - git push.
   - ### Envia alterações confirmadas
 - git pull origin master,prod ou dev
   - ### recupera a ultima versão commitada em na branch apontada
 - git stash save 'Nome do stash'.
   - ### Joga para a memoria as alteraçoes e remove do arquivo voltando para a versão original. e salva com o nome escolhido
 - git stash list.
   - ### Lista todos os stash em memoria.
 - git stash pop stash@{0}.
   - ### recupera o stash desejado informando o index do stash
 - git stash show -p stash@{0}.
   - ###  exibie as alteraçoes no stash escolhido index.
 - git stash list.
   <br>
