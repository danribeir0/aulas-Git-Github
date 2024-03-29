*** COMANDOS GIT ***

git init
    - Inicializa um versionamento na pasta/repositorio/projeto
    - Inicia um novo repositório Git local na pasta atual.

git status
    - mostra o(s) arquivo(s) que ainda esta(ão) pendente(s) de commit
    - Verifica o status atual do repositório, incluindo arquivos modificados e arquivos na área de stage (pronto para ser commitado).

git add . ou nome.arquivo
    - adiciona os arquivos pendentes para serem commitados
    - Adiciona arquivos selecionadas para a área de stage (pronto para ser commitado).

git commit -m "Descrição das alterações que estão sendo commitados"
    - commita os arquivos que foram add (adicionados)
    - Grava as alterações feitas na área de stage (pronto para ser commitado) como uma nova versão do código.

git log
git log --all
    - ver histórico de commits.

git checkout <numero* (hexadecimal) do commit que deseja ir> ou <master> (branch conhecida)
    - Navegando entre os commits

git remote add origin <https://github.com/...>
    vincula meu repositório local com um repositório online do Github

git push -u origin <branch>
    envia os arquivos do repositório para o Github

git clone <https://github.com/...>
    clona um repositório do Github para minha máquina

code .
    Abre o VSCode no diretório

git checkout -b <nome da branch>
    cria uma nova branch e muda para ela

git branch
    lista as branch que tem nesse repositório

-----------------------------------------------------------------------------------------------------
*** PARAMENTROS ***
HEAD: É um seletor que indica qual é o commit/branch/ramificação nós estamos trabalhando no momento
