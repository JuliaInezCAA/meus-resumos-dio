
# DIO | Resumos Git e GitHub
## AULA 06 - Trabalhando com branches II 

### Comandos úteis no dia a dia.
```
git init - Cria um repositório git vazio.

git status - Informa o estado das alterações do nosso projeto.

git add [file] - Adiciona ou atualiza mudanças para irem para o nosso repositório.

git add . - Você pode adicionar todos os arquivo usando o ".".
git rm [file] - Remove os arquivos que foram adcionados com o git add.

git commit -m "message" - Registra alterações no repositório.

git commit -am "message" - Atualiza o repositório e registra alterações no repositório ao mesmo tempo.
git commit --amend -m "message" - Troca a última mensagem feita no commit.
git log - Mostra os pontos na "linha do tempo" do repositório (commits).

git log --oneline - Mostra os pontos na "linha do tempo" de forma mais resumida.
git log --abbrev-commit - Ao invés de mostrar o hash com 40 caracteres, mostra apenas com 7 caracteres.
git log --pretty=oneline - Faz com que caiba toda a mesagem de commit em uma linha.
git log --graph - Desenha uma representação gráfica dos commits no lado esquerdo da saída do terminal.
git log --grep="texto" - Busca por commits que tenha a a palavra "texto".
git diff - Mostra o que foi alterado em um arquivo, de vermelho o que foi excluído, de verde o que foi adicionando.
 Use-o antes do git add.

git show - Apresenta o último ponto na "história" do nosso projeto.

git show [hash] - Apresenta determinado ponto na "história" do nosso projeto.
git branch - Lista, cria ou exclui ramificações.

git branch -d [ramificação] - Exclui ramificações.
git checkout [hash] - Alterna ramificações ou restaura arquivos da árvore de trabalho.

git checkout -b [minha-feature] - Cria uma nova ramificação no nosso projeto.
git checkout [minha-ramificação] - Vai para a ramificação criada pelo desenvolvedor.
git checkout master - Vai para a ramificação master.
git checkout -- [arquivo-modificado] - Descarta as mudanças feitas no arquivo. Use antes de dar o git add.
git merge [branch] - Faz a fusão de uma branch X com uma branch Y.
 Para fazer a fusão das branchs você tem que estar na branch que vai recber a outra branch.

git mv [arquivo] [diretório] - Move um arquivo para um diretório especificado

git mv [nome-original] [novo-nome] - Renomea um arquivo.

git clean -f - Remove arquivos não rastreados.

git reset --hard [hash] - Reverte um commit.

git remote - Verifica se existe um repositório remoto.

git push - Envia alterações locais para o repositório remoto.

git clone [link-do-repositório] - Clonar um projeto / repositório.

git pull - Puxa do repositório remoto.
```

## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)
