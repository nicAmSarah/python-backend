# python-backend

PyPI (Python Package Index) onde os pacotes são armazenados de maneira pública

[text](https://pypi.org/)

pip install numpy - > instalar um pacote
pip uninstall numpy --> desinstalar um pacote 
pip list - > listar todas as libs que estao instaladas na versão ativa no ambiente
pip install --upgrade nomeDoPacote --> Atualizar um pacote
pip --> listar as libs do seu ambiente  
pip search termoDoPacote --> Procurar pacotes do pypi por linha de comando (NÃO FUNCIONA MAIS)

AMBIENTE VIRTUAL

pythonV -m venv myenv(nome do ambiente virtual, geralmente seria o nome do projeto, ou .env)
LINUX : source myenv/bin/activate

WINDOWS : myenv/Scripts/activate

caso seu windows não esteja com permissão para executar scripts, será necessario habilitala
1) Abrir o Power Shell e executa-lo como admnistrador de sistema.
2) No prompt você vai digitar Set-ExecutionPolicy (Comando para passar a executar os scripts).
3) Aceitar [S]

Para voltar com a proteção você digitará o mesmo comando, porem, ordenando a Restringir os comandos. Assim:
Set-ExecutionPolicy Restricted

Pip install django 

DEACTIVATE --> sair do seu ambiente virtual