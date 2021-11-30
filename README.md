# Predict-Phising-URL

## ScreenShots

![](https://github.com/ak566g/Predict-Phising-URL/blob/main/images/ss1.png)

![](https://github.com/ak566g/Predict-Phising-URL/blob/main/images/ss2.png)


## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/ak566g/Predict-Phising-URL.git
$ cd Predict-Phising-URL
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```
Once `virtualenv` activated:

```sh
(env)$ cd phishingurlPredictor
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.