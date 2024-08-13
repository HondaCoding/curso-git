# **[Curso de Git e GitHub - 2023] Pietro Martins De Oliveira - Youtube**
## *Extensões necessárias no vscode:*
- **Git Graph**
- **Git History**
## *Comandos utilizados:*

- **git diff**                         : visualizar alterações (no modo 'unstaged')
- **git status**                       : ver status atual
- **git add**                          : passa o arquivo para o modo 'staged'
- **git log**                          : visualizar histórico (log)
- **git log --pretty=oneline**         : log organizado
- **git blame**                        : log de cada usuario q fez a alteração 
- **git commit -m**                    : commit com o add
- **git commit -am**                   : commit sem o add
- **git push**                         :  
- **git restore <file>**               : restaura a versao anterior
- **git restore <file> --staged**      : tira o arquivo do modo staged(nao será comitado)

- **git branch**                       : visualizar em qual branch voce está
- **git checkout -b "nome-da-branch"** : cria uma nova branch
- **git checkout "branch"**            : navega para a branch escolhida

- **branch -M main**                   : renomear a branch 'master' para 'main'
- **git remote add origin <url>**      : Ele configura seu repositório Git local para se conectar a um repositório remoto no GitHub 
- **git remote get url origin**        : indica a url do repository
- **git push -u origin main**          : PRIMEIRO push do MAIN no repository, após o primeiro push basta somente 'git push'

- **git push origin nome-da-branch**   : push da branch local para o github(nuvem);

- **git branch -d nome-da-branch**     : deleta a branch LOCAL (git)
- **git push origin --delete nome-da-branch**     : deleta a branch REMOTA (github)
- **git fetch --prune**                : atualiza as branch remotas para as locais
 
- **git push --set-upstream origin "nome-branch"** : push QUANDO TEM UMA NOVA BRANCH do repository local para o gitHub
- **git merge "nome-branch"**          : faz o merge da branch indicada para a branch que se encontra atualmente
