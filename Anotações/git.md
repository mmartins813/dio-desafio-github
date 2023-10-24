# O que é o git.
<ul>
  <li>Sistema de controle de versão distribuido</li>
  <li>Gratuito/Open Source</li>
  <li>Leve e rápido</li>
</ul>
</br></br>

# Comandos básicos
```
git config --global credential.helper store
```
Adiciona credenciais no repo local para uso em futuros projetos git
```
git clone (url) "caminho"
```
Comando utilizado para clonar um repositorio remoto para o local especificado.

```
git clone <url> --branch <nome-branch> --single-branch <caminho>
```
Clona do repositorio remoto apenas a branch especificada.
```
git status
```
Mostra status da área de preparação e untracked files
```
Git add .
```
Adiciona alterações a área de preparação
```
git commit -m"mensagem"
```
Commita os arquivos na área de preparação
```
git push
```
"Empurra" as alterações na área de preparação para o repo remoto.
```
git pull
```
"Puxa" alterações do repo remoto
```
git log
```
Lista os ultimos commits.
