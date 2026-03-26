# notas-estudo
minhas notas de estudo tec senac


markdown


## configurando git

Para utilizar o git na minha maquina eu preciso configurar determinados comandos, sendo eles:

```bash
git config --global
```


## Como configurar Github

## SSH - Como configurar a maquina para Github

## Como criar um repositório
Aprendemos como instalar Git, configurar Git, criar conta no Github, configurar SSH no Github, instalar NodeJS,  instalar VSCode, criar repoditório, clonar repositório, abrir VSCode.

Github-SSH
SSH-GitBash
## verificar se existe chave ssh.
```bash
ls-al~/.ssh
```
## adicionar uma nova chave. (ID)
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"`
```
## inicializar agente-ssh
```bash
eval "$(ssh-agent S)"
```
## adicionar chave ssh ao agente.
```bash
Github- Settings- SSH and GPG keys- New SSH key- colar
```
Coloque um título que indentifique a chave
EX:SENAC-SALA-106-PCXPTO

## Testar Conexão
```bash
ssh -T git@hub.com

VS Code-Extensões
Liver Server
CSS Peek
CSS Grid Snippets
Color Highlight
Dracuma Theme Official

VS Code-Atalhos
! e html: 5 para scaffolding rápido
Alt + L + O para visualizar HTML no navegador
Ctrl+Space para sugestões de código
Ctrl+Shift+I para formatar código CSS
Ctrl+/ para comentar linhas código
Alt+Shift+F para formatar o código JavaScriptS