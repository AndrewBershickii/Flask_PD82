# Решение задания к лекции «Flask»

Условия задания описаны в файле [здесь](https://github.com/netology-code/py-homeworks-web/tree/new/2.1-flask)

Чтобы запустить сервер необходимо:

- Установить все необходимые библиотеки, для этого нужно открыть терминал по адресу директроии и выполнить:

```bash
pip install -r requirements.txt
```
- Подключить базу данных путём создания файла ```.env```, необходимые переменные для подключения можно просмотеть в файле [models.py](./models.py)
- Сервер запускается с помощью выполенеия:
```bash
python server.py
```
- Проверить API можно выполнив:

```bash
python client.py
```
- В файле [client.py](./client.py) можно протестировать различные методы к API,надо только их раскоментировать
