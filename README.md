Como instalar o Python no Ubuntu!

Dependências PyEnv e Panda
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev git liblzma-dev

curl -L https://raw.githubusercontent.com/yyuu/pyenv-installer/master/bin/pyenv-installer | bash

export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"

Cole os comandos acima em: gedit ~/.bashrc ~/.profile

Rode o comando pyenv install -l e procure a versão mais recente

Instale a versão mais recente: pyenv install x.x.x

E torne ela padrão utilizando: pyenv global x.x.x

Para verificar se está utilizando a versão mais recente, utilize o comando:pyenv versions | A versão mais recente deve conter um asterisco.
