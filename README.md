 sisti
 =====

 Sistema de controle de procedimentos/chamados/estoque/usuários da TI do câmpus Concórdia

 ** ATENÇÃO: estes passos foram testados no ubuntu 12.04 server **

 sudo apt-get install python-pip python-virtualenv build-essential libmysqlclient-dev python-dev

 virtualenv diretorio-do-sistema
 cd diretorio-do-sistema
 . /bin/activate

 easy_install -U distribute
 pip install django
 pip install mysql-python




