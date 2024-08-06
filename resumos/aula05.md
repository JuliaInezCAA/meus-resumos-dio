# DIO | Resumos Git e GitHub
## AULA 05 - Trabalhando com branches I 

### Criando, mesclando, deletando e tratando conflitos.
```
mkdir trabalhando-com-branches
cd trabalhando-com-branches
git init 
touch READEME.md
git add READEME.md 
git commit -m"commit 0"
git log
```
Criando mais 2 commits
```
echo "#commit-1-branch-main" > commit-1-branch-main.txt
git add .
git commit -m"commit1"
git log
echo "#commit-2-branch-main" > commit-2-branch-main.txt
git add .
git commit -m"commit2"
git log
```
Agora vamos criar a branch
```
git checkout -b teste ("teste" é o nome que demos a nossa branch)
git log
```
Criando commit na branch teste
```
echo "#commit-3-branch-main" > commit-3-branch-main.txt
git add .
git commit -m"commit3"
git log
```
```
checkout main (retorna pra branch main)
git branch -v (lista o último commit de cada branch(main e teste nesse caso))
```
mesclando as branches com a main
```
git merge teste (mescla)
git branch (lista as branches que estão nesse repositório)
git branch -d teste (exclui a branch teste ,que já estava na main)
```
### Conflitos de merge
No caso de haver conflitos de informações quando for enviar as mudanças para o repositório remoto:
```
git push origin main (o Git vai recusar por conta do conflito)
git pull

- agora você vai escolher manualmente as mudanças que vai querer e salva-las no diretório

git status
git add .
git commit -m"commit após o conflito"
git log
git push origin main
```

## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)
