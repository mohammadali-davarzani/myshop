My Shop

apt install rabbitmq-server
Run: rabbitmq-server

pip3 install celery
celery -A myshop worker -l info

pip3 install flower
celery -A myshop flower

http://127.0.0.1:5555/dashboard

