My Django Shop
--------------------------------
_Online store on Django, Python_
--------------------------------
rabbitmq-server

install: `sudo apt install rabbitmq-server`

Run: `rabbitmq-server`

--------------------------------
celery

`pip3 install celery`

`celery -A myshop worker -l info`

--------------------------------
flower

`pip3 install flower`

`celery -A myshop flower`

--------------------------------