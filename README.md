# Como usar o Git e Github na prática

aula de git e github professor Natan

## Instalando o GIT

* [Link com os downloads](https://git-scm.com/downloads)

## Criar um projeto novo
* Criar uma nova pasta no PC pra isso chamada `Git Tutorial`

* Salva o arquivo

Agora então é hora de usarmos o Git

* Abre o Git Bash que foi instalado na máquina (pode ser pelo terminal do VSCode mesmo)

* `git init` para inicializar o repositório

Foi criada uma pastinha `.git` e é ali que toda a mágica acontece, então não apague

* `git add README.md` para colocar o arquivo na área de stagging 

<img src="https://i1.wp.com/www.markus-gattol.name/misc/mm/si/content/git_git_add.png">

Esse `add` é necessário antes de darmos o commit de fato, mas por que isso? No final do vídeo explico para vocês

* `git commit -m "primeiro commit"` para de fato dar o commit no repositório

* `git branch -M "main"` para alterar o nome da branch principal de `master` para `main` (isso é uma boa prática atualmente recomendada)
