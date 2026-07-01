# Curso TMW Git & GitHub 2026

Um curso gratuíto para iniciantes em tecnologia aprenderem a usar o Git e GitHub.

-> Versionamento
-> Branches
-> Pulls / Push
-> Forks
-> Pull Requests

## Fluxo de trabalho Git local

1. git chechout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add .
5. git status
6. git commit -m 'mensagem do commit'
7. git checkout main
8. git merge nova-branch

## Fluxo de trabalho GitHub < > Local (projetos open-source)

1. Fork do projeto para o GitHub pessoal
2. git clone <endereco-fork-remoto>
3. git checkout -b <nova-branch>
4. alterações no arquivo
5. git status
6. git add *arquivos*
7. git status 
8. git commit -m 'mensagem de commit'
9. git push origin <nova-branch>
10. abrir Pull Request no GitHub da branch fork ->  main do repositório original
11. excluir <nova-branch> origin
12. git checkout main
13. git branch -D <nova-branch>

Além disso, o curso aborda Gitflow e integração com o VSCode.
