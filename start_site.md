- Установите brew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
```
brew install python
pip install virtualenv
```
- далее выдаёт путь где установлен
```
virtualenv /Users/<username>/venv
source /Users/<username>/venv/bin/activate
pip install Django
django-admin startproject <lolkek>
cd <lolkek>
django-admin startapp <my_app>
```
- см. Снимок экрана 2019-11-13 в 19.04.20.png
```
python3 manage.py runserver
python3 manage.py migrate
```
