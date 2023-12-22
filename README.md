## Agenda



##
### Executar em sua maquina
Para ter acesso e executar o projeto, algumas configurações são necessarias.

***Passo 01***

Crie um novo diretorio vasio e acesse-o pelo terminal
```
mkdir name-diretorio
cd name-diretorio
```

***Passo 02***

De acordo com o serviço que utiliza para se conectar ao repositorio execute um dos seguintes comandos:

Via requisição HTTP:
``` 
git clone https://github.com/JAndersonArruda/Agenda.git
```
Via chave SSH:
``` 
git clone git@github.com:JAndersonArruda/Agenda.git
```

***Passo 03***

Configure o ambiente e start o app
```
cd Agenda
python -m venv .venv
. .venv/bin/activate

pip install -r requirements.txt

cd agenda
python manage.py migrate
python manage.py runserver
```

##
### Autores
[J. A. F. Arruda](https://jandersonarruda.github.io/)

