[Curso de Git e GitHub - 2023] Pietro Martins De Oliveira - Youtube

git diff                        // visualizar alterações (no modo 'unstaged')
git status
git add                         // passa o arquivo para o modo 'staged'
git log
git log --pretty=oneline
git blame                       // log de cada usuario q fez a alteração 
git commit -m
git commit -am
git push
git restore <file>              // restaura a versao anterior
git restore <file> --staged     // tira o arquivo do modo staged(nao será comitado)

branch -M main                  //renomear a branch 'master' para 'main'
git remote add origin <url>
git remote get url origin       //indica a url do repository
git push -u origin "main"       //primeiro push no repository, após o primeiro push basta somente 'git push'
