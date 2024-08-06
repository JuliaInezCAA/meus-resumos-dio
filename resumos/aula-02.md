# DIO | Resumos Git e GitHub
## AULA 02 - Salvando alterações no repositório local.

### Criando um repositorio pra resumos
```
1. em uma pasta vamos abrir o bash here, já instalado e configurado,
2. em seguida inserimos os seguintes comandos:
- mkdir meus-resumos-dio (ou nome-da-pasta-qualquer)(criando pasta vazia)
- cd meus-resumos-dio (entrando na pasta)
- git init (inicializando um repositório git vazio na pasta git aberta.)
- git status (mostra o status da área de trabalho/ de inicialização)
- touch README.md (criando arquivo .md vazio)
- git status (nesse momento o terminal vai retornar que existe um UNTRACKED FILES,
 arquivo não rastreado.)
- pelo chrome acessamos o editor README (https://readme.so/pt/editor), criamos em markdown
o conteúdo do nosso repositório e acrescentamos manualmente, pelo bloco de notas, no 
arquivo README.md no explorador de arquivos na nossa pasta meus-resumos-dio e salvamos.
- agora que chegamos num ponto que desejamos commitar esse arquivo;
- no terminal botamos os comandos:
- git add README.md
- git commit -m"mensagem do commit(exemplo "commit inicial")"
- git log (para vermos o commit pronto)

```
### Diretórios vazios
```
git status (mostra o status do nosso local de trabalho)
mkdir resumos (criando Diretório)
git status (vai retornar pasta TREE CLEAN pq o Git não reconhece pasta vazia)
touch resumos/resumo-aula1.md (criando arquivo vazio)
echo resumos/ >.gitignore (mandando para gitignore para ele não reconhecer mais a pasta)
echo > .gitignore (remove de gitignore)

```
```
OUTRA FORMA:

- gitkeep - usado para git reconhecer diretórios vazios.

exemplo:
mkdir aulas
touch aulas/ .gitkeep
```
### Salvando o código
```
git add . (vai mandar todas as modificações pra area de preparação)
git commit -m"adicionei arquivos gitignore e diretorios de aulas e resumos."
````


## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)
