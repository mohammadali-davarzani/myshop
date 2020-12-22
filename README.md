My Shop (Django)
===
---

    Online store on Django, Python
>Developer: Aleksandr Suvorov

---

![GitHub language count](https://img.shields.io/github/languages/count/mysmarthub/myshop)
![GitHub repo size](https://img.shields.io/github/repo-size/mysmarthub/myshop)
![GitHub all releases](https://img.shields.io/github/downloads/mysmarthub/myshop/total)
![GitHub](https://img.shields.io/github/license/mysmarthub/myshop)
![GitHub Repo stars](https://img.shields.io/github/stars/mysmarthub/myshop?style=social)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/mysmarthub/myshop)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/mysmarthub/myshop)

---

Help the project financially:
---
>Yandex Money:
https://yoomoney.ru/to/4100115206129186

    Visa:    4048 4150 0400 5852

    Sberbank Russia: 4276 4417 5763 7686

https://paypal.me/myhackband

---

Description:
---
    Online store on Django, Python

---

Help:
---


    rabbitmq-server

>install: `sudo apt install rabbitmq-server`

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

    Don't forget to add settings.SECRET_KEY it to your private key

`pip install -r requirements.txt`

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py createsuperuser`

`python manage.py loaddata fixtures/rubric.main.json --app main.models`

`python manage.py dumpdata --format=json main > fixtures/main.json`

---

Links:
---
>[GitHub](https://github.com/mysmarthub/myshop)

---

Disclaimer of liability:
------------------------
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Support:
---
    Email: myhackband@yandex.ru
    Copyright © 2020 Aleksandr Suvorov