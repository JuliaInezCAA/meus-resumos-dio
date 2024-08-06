# DIO | Resumos Git e GitHub
## AULA 03 - Desfazendo alterações no repositório local.

### excluindo diretórios e arquivos
```
git init 
rm -rf (vai escluir forçadamente e de forma recursiva)

rm [opções] [arquivo]
rm - Exclui um arquivo.
rm -f - Exclui arquivos forçadamente.
rm -r - Exclui o diretório e os arquivos na direção recursiva, o diretório especificado junto com seu subdiretório e arquivos.
rm -d - Remove somente diretórios vazios.
rm -i - Pergunta se queremos remover o arquivo/diretório antes de excluir.
```
### revertendo commits
```
git log ( pra ver histórico de commits e pegar a hash)

git reset --soft [hash] - Reverte um commit.
git reset --mixed [hash] - Reverte um commit.
git reset --hard [hash] - Reverte um commit.

git reflog (pra mostrar histórico mais detalhado)
```
### alterando mensagem do último commit 
```
git commit --amend -m"nova mensagem"
```
### restaurando arquivos
```
git restore (nome do arquivo a ser restaurado)

ou

mkdir resumos
touch resumos/aula-01.md resumos/aula-02.md
git status
git add .
git status
git reset resumos/aula-02.md
git status
```

## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)
