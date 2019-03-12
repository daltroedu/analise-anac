# analise-anac

Análise de dados sobre dados da ANAC.
Fonte: http://www.anac.gov.br/assuntos/dados-e-estatisticas/historico-de-voos 

$ sudo apt-get update
$ sudo apt-get install -y python3-pip build-essential libssl-dev libffi-dev python-dev python3-venv jupyter-notebook
$ mkdir ~/app/data/anac/2018/
$ mkdir ~/app/data/anac/outros/
$ cd ~/app/
$ virtualenv -p python3 env
$ source /env/bin/activate
$ pip3 install jupyter matplotlib numpy
$ jupyter notebook
