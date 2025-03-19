 <p align="center">
  <img src="https://github.com/EduardoNofre/padrao-commit-gitHub/blob/main/1820-gitlab_github-936x527.jpg.webp?raw=true" alt="Sublime's custom image"/>  
</p>

 - ## O que git? <br>
    ➜ Git é uma ferramenta de código aberto que permite gerenciar projetos e versões de código. É um dos sistemas de controle de versão distribuído (DVCS) mais populares do mundo

 - ## O que gitHub? <br>
    ➜ O GitHub é uma plataforma online que permite armazenar, compartilhar e colaborar em projetos de desenvolvimento de software.
 
 <h1 align="center">
 Boas práticas na utilização do Git. <br>
 </h1>

 - ## Os principais comando do dia a dia.

# ➜ git --version
    -  Exibe a versão do git instalada na maquina.
# ➜ git checkout -b 'nomeBranch'.
    -  Cria uma nova branch local
# ➜ git status.
    -  Verifica se há alterações no codigo
# ➜ git diff.
    -  Exibe as alteraçoes feita no arquivo informado pelo path
# ➜ git add .
    -  Adiciona o arquivo  
# ➜ git add path file.
    -  Adiciona o arquivo somente o arquivo mencioando no path caminho 
# ➜ git commit -m' mensagem '
    -  Descrição". Descrição das alterações
# ➜ git commit --amend -m "Reescrever a mensagem"
    -  Reescrever a mensgaem do git. Observação tem que ser feito antes do push.
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
# ➜ git log
    - Lista todos os commits log do ultimo para o mais antigo 'commits, arquivos'.
# ➜ git log -10
    - Lista os 10 utimos commits log do ultimo para o mais antigo 'commits, arquivos'.
# ➜ git reflog
    - Ideal para resturar uma versão anterior caso tenha algum erro. basta escolhe o indice dc8e5ea HEAD@{2}
  
  <h1 align="center">
    Os tipos. <br>
  </h1>
 - ### O commit possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.
  
 - ## fix
     - Commits do tipo fix indicam que seu trecho de código commitado está solucionando um problema (bug fix), (se relaciona com o PATCH do versionamento semântico).<br>
 - ## feat
     - Commits do tipo feat indicam que seu trecho de código está incluindo um novo recurso (se relaciona com o MINOR do versionamento semântico).
 - ## docs
     - Commits do tipo docs indicam que houveram mudanças na documentação, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).<br>
 - ## style
    - Commits do tipo style indicam que houveram alterações referentes a formatações de código, semicolons, trailing spaces, lint... (Não inclui alterações em código).<br>
 - ## refactor
    - Commits do tipo refactor referem-se a mudanças devido a refatorações que não alterem sua funcionalidade, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.<br>
- ## build
    - Commits do tipo build são utilizados quando são realizadas modificações em arquivos de build e dependências.<br>
- ## test
    - Commits do tipo test são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)<br>
- ## chore
    - Commits do tipo chore indicam atualizações de tarefas de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)<br>

 <h1 align="center">
        Boas praticas na utlização do git commit -M''.
 </h1>   
 
- ### No mundo do desenvolvimento de software, manter um padrão de commits claro e consistente é fundamental para a organização e rastreabilidade do código.

    - ### Escopo:<br>
       git commit -m'<tipo>(tipo): <descrição>'<br>
    - ### Utlizando:<br>
        - ### git commit -m'improvement:(serviço java): descrição ou numero  ou numero do Jira' <br>
          ➜ Manutenção dia a dia.<br>
        - ### git commit -m'feat:(serviço java): descrição ou numero  ou numero do Jira' <br>
          ➜ Novo recurso.<br>
        - ### git commit -m'fix:(serviço java): descrição ou numero  ou numero do Jira'  <br>
          ➜ Bug.<br>
        - ### git commit -m'test:(serviço java): descrição ou numero  ou numero do Jira' <br>
          ➜ Test unitario.<br>
        - ### git commit -m'docs:(serviço java): descrição ou numero  ou numero do Jira' <br>
          ➜ Melhoria na documentação readme ou swagger.<br>

      
