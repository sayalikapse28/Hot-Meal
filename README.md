# Hot-Food
> Food Delivery Website built with HTML, CSS, JS, Python, Django 
# Demo:
## Homepage
![](demo/home.png)
## Product page
![](demo/product.png)
## Installation:
**1.Setup pipenv & Install Requirements**
```sh
pip install pipenv
pipenv install -r requirements.txt
pipenv shell
```
**2.Set Up RabbitMQ Server**
```sh
sudo apt-get install rabbitmq-server
service rabbitmq-server start
```
**3.Migrate Database**
```sh
python manage.py makemigrations
python manage.py migrate
```
**4.Start Server**
```sh
python manage.py runserver
```

