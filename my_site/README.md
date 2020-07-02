# Как запустить *(Linux)*  

```
git clone https://github.com/H4RP3R/SF_D5.11.git
cd SF_D5.11
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```
В БД уже есть данные

## Проверка
Связать друга с книгой из админки можно как из модели "друг", так и из модели "книга".  
Во фронтенде — во вкладке "Одолженные книги".  
Добавить нового друга можно в админке и во фронтенде.  
