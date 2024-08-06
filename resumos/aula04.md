
# DIO | Resumos Git e GitHub
## AULA 04 - Enviando e baixando alterações no repositório remoto.

### 1. Enviando do repositório local para o remoto

Vamos iniciar criando um repositório vazio no GitHub,
vamos também simular algumas mudanças pelo conteúdo no bloco de notas, como retirar uma letra qualquer do nosso README.md e salvar a alteração
Agora vamos no GitHub e pegamos o link HTTps do repositório criado.
```
1. em uma pasta vamos abrir o bash here, já instalado e configurado,
2. em seguida inserimos os seguintes comandos:
git remote add origin https... (estamos conectando os repositórios)
git branch -M main (esse passo damos para renomear a branch de master pra main, caso ainda não esteja com essa configuração)
git push -u origin main (envia as alterações do repositório local pra o remoto)
```

### 2. Alterando no remoto e baixando as modificações localmente

 No próprio GitHub, indo no repositório desejado e em editar você pode fazer commits e salva-los.
 Com essas alterações feitas, vamos abrir nosso Git bash e escrever o comando:
 ```
 git pull (responsavél por puxar alterações do repositório remoto para o local)
 ```

## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)
