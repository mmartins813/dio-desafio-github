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
```
git remote -v
```
Lista repositorios remotos vinculados


# Branches
<ul>
	<li>Uma branch é uma ramificação do seu projeto</li>
	<li>Pode ser utilizada para testes, sem afetar a branch principal do projeto</li>
	<li>Quando a nova branch é criada dentro de uma já existente, essa nova passa a apontar para 
Mesmo commit de onde ela se originou</li>
	<li>Criações em branches diferentes não se refletem em outras branches. Ambiente ideal para testes</li>
	<li>Após finalizar trabalho, mesclar branches juntam arquivos</li>
</ul>
</br>

# Comandos básicos

```
git checkout -b nomebranch
```
Cria uma nova branch
```
git checkout nomebranch
```
Altera a branch ativa.
```
git branch -v
```
Lista ultimo commit de cada branch