![BeAcademy](https://www.beacademy.com.br/wp-content/uploads/2019/11/Logo-Topo.png)

# BeAcademy - DevStart

| Comando | Descrição |
| --- | --- |
| git config |
| git config --global user.name | Comando utilizado para configurar o usuario do git  |
| git config --global user.email| Comando utilizado para configurar o email do usuario git |

### Principais comandos do git
git init- Responsavel por inicializar um repositorio

git status - para visualizaar o status do versionamento

git add .- Responsavel por preparar os arquivos para serem commitados

git rm --cached <file >-  para desfazer os commits

git commit -m "messagem"- para criar novos commits

git log- Comando ultilizado para mostrar os log das ramificações

| Comando | Descrição |
| --- | --- |
| git revert |
| git revert 'número do hash' | Uma maneira segura de desfazer os commits é usando git revert |
| git log -- oneline| O número do hash pode ser conseguido pelo comando. |

git branch <nome>- para cria uma nova branch

git checkout <nome>- para acessar a branch

git checkout -b <nome>-  cria uma nova branch e tambem faz o acesso a mesma

git branch -d <nome>-  ultilizado para deletar alguma banch em especifico

git merge <nome da branch>- ultilizando para unir os conteudos das branch na branch principal

git push- Envia os arquivos Commitados para o repositorio remoto ( github )

git stash- Arquiva deixando em segundo plano as alterações durante um determinado período, para que você possa trabalhar em outra coisa, depois voltar a trabalhar de onde parou

git stash list- Lista todos arquivos em stash

git stash apply@{ aqui você coloca o indece do stash}- Seleciona qual stash você que voltar a trabalhar

git stash pop - volta no stash mais recente

### Professores e Orientadores
Regis santos

### Ferramentas utilizadas
Git e GitHub

### Documentação do Git
https://git-scm.com/docs/git-config

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
