 <h1 align="center">
 Boas práticas na utilização do GitHub. <br>
 </h1>

 - ## Os principais comando do dia a dia.

# ➜ git checkout -b 'nomeBranch'.
    -  Cria uma nova branch local
# ➜ git status.
    -  Verifica se há alterações no codigo
# ➜ git add .
    -  Adiciona o arquivo  
# ➜ git add path file.
    -  Adiciona o arquivo somente o arquivo mencioando no path caminho 
# ➜ git commit -m"
    -  Descrição". Descrição das alterações
# ➜ git push.
    -  Envia alterações confirmadas Observção para branch ja commitada
# ➜ git push --set-upstream origin 'nomeBranchLocal'.
    -  Primeiro push da branch local
# ➜ git pull origin master,prod ou dev
    -  Recupera a ultima versão commitada em na branch apontada
# ➜ git stash save 'Nome do stash'.
    -  Joga para a memoria as alteraçoes e remove do arquivo voltando para a versão original. e salva com o nome escolhido
# ➜ git stash list.
    -  Lista todos os stash em memoria.
# ➜ git stash pop stash@{0}.
    - Recupera o stash desejado informando o index do stash
# ➜ git stash show -p stash@{0}.
    - Exibie as alteraçoes no stash escolhido index.

- # Boas praticas na utlização do git commit -M''.
- No mundo do desenvolvimento de software, manter um padrão de commits claro e consistente é fundamental para a organização e rastreabilidade do código.

- # Tipos de Commits
O commit possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.
fix - Commits do tipo fix indicam que seu trecho de código commitado está solucionando um problema (bug fix), (se relaciona com o PATCH do versionamento semântico).
feat- Commits do tipo feat indicam que seu trecho de código está incluindo um novo recurso (se relaciona com o MINOR do versionamento semântico).
docs - Commits do tipo docs indicam que houveram mudanças na documentação, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).
style - Commits do tipo style indicam que houveram alterações referentes a formatações de código, semicolons, trailing spaces, lint... (Não inclui alterações em código).
refactor - Commits do tipo refactor referem-se a mudanças devido a refatorações que não alterem sua funcionalidade, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.
build - Commits do tipo build são utilizados quando são realizadas modificações em arquivos de build e dependências.
test - Commits do tipo test são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)
chore - Commits do tipo chore indicam atualizações de tarefas de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)
