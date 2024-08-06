# DIO | Resumos Git e GitHub
## AULA 01 - Criando e clonando Repositórios.

Existem duas maneiras para obter um Repositório Git na sua máquina:
### Transformando um diretório local (não versionado)em um Repositório Git;
```
1. em uma pasta vamos abrir o bash here, já instalado e configurado,
2. em seguida inserimos os seguintes comandos:
- mkdir nome-da-pasta (criando pasta)
- cd nome-da-pasta (entrando na pasta)
- git init (inicializando um repositório git vazio na pasta git aberta.)
- cd .git (entrando no repositório git)
- ls ( Lista arquivos e diretórios.)
- cat config (exibir conteúdo das configurações)
- git remote -v (pra ver se o diretório tá vinculado a algum repositorio)
- cd ..(volta um diretório)
- git remote add origin + vamos criar um Repositório remoto no GitHub ("repo-remoto" por exemplo),
 copiar a https dele e colar aqui. (para vincular uma URL remota com um nome.)
- cd .git (entrando no repositório git)
```
### Clonando um Repositório Git já existente, pelo GitHub;
```
1. Vamos copiar a URL do Repositório no GitHub que você deseja clonar;
2. E usar os comandos no terminal bash here, já aberto no diretório desejado:
- git clone +a URL (caso você deseje pode acrescentar aqui um nome novo que você quer que o
 Repositório clonado tenha no diretório após a URL, por exemplo "repo-clonado".)
- cd .git (entrando no repositorio git)
- cat config (exibir conteúdo das configurações)
- git remote -v (já vai estar vinculado ao repositorio, do qual pegamos ele para clonar)

```


#### Clonando uma branch
Comando para clonar apenas uma branch do Repositório remoto:
```
git clone (+URL do Repositório) --branch (+nome da branch) --single branch
```
## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)

