### Проект: Сайт - визитка

Сайт - визитка написан на фреймворке Flask с использоваием docker.
С помощью GitHub Actions созданы workflow, которые проверяют код
на соответствие PEP8 и отпрвляют изменённый образ в репозиторий
#Docker Hub.



### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Kuzahka/business-card.git
```

```
cd Seb
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```



Запустить проект:

```
flask run
```

