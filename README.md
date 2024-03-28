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

-----------------------------------------------------------------------------------------------------
*** PARAMENTROS ***
HEAD: É um seletor que indica qual é o commit/branch/ramificação nós estamos trabalhando no momento
