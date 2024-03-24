meu primeiro sistema no git
alteração no readme pra descrever o sistema melhor


git branch - saber qual branch vc esta
git log - ver o log de commits feitos
git status - ver o status das modificações (arquivos modificados e adicionados)
git add -A - adicione todos os arquivos modificados e inseridos no git
git add nomedoarquivo - adiciona um arquivo especifico
git commit -m "Descrição" - Cria uma nova versão dos arquivos modificados
git commit -am "Descrição" - adiciona os arquivos novos e modificados e Cria uma nova versão dos arquivos modificados

existe 3 tipos de reset no git: soft, mixed e hard
o soft desfaz o commit, mantendo as alterações no arquivo em um estagio antes do commit, permitindo corrigir o erro e commitar novamente
o mixed desfaz o commit e o add. Então voce tera que adicionar e commitar o arquivo novamente
o hard desfaz o commit, o add e as modificações, voltando literalmente a um estagio anterior da pasta
o comando de reset é 
git reset --soft e a hash do commit
git reset --mixed e a hash do commit
git reset --hard e a hash do commit

git stash - Desfaz tudo que nao foi comitado ainda

git branch nomedobranch - cria um novo branch
git checkout (ou switch) nomedobranch - muda para o branch escolhido

git diff (o codigo dos commits que deseja comparar) - mostra a diferença entre o ultimo commit e as ultimas modificações sem commitar
git diff --name-only - mostra somente o nome dos arquivos que foram modificados
git diff nomedoarquivo - mostra as laterações somente no arquivo escolhido

git checkout HEAD nomedoarquivo - O Head é interpretado como o Branch atual. Então ele vai pegar o arquivo modificaro do branch atual e subuitiuir pelo original.

Para clonar um repositorio, digite o comando git clone e cole o caminho da internet do repositorio a ser clonado

Texto alterado no repositorio local Mega
Texto alterado no repositorio local Casa
Texto adicionado via GITHUB web.

Para colocar uma tag em um commit, use o comando git tag ONomeDaTag ONumeroDaTag