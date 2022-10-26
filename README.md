`postmorphoses`

Разве *лес* не похож на *речь*?
Разве не теряешься среди пульсации деревьев-обрывков фраз? не сливаешься с мхом слов?
Разве не напоминает бесконечное воспроизводство природы комбинаторную репликацию речи?

Проект `postmorphoses` исследует нашу работу, которая заставляет природу видоизменяться и плести миф о себе, захватывая нас в его сети.

Обрывки фраз со словом «природа», взятые из [национального корпуса русского языка](https://ruscorpora.ru/), циклично подаются на вход нейросети [RuGPT-3](https://huggingface.co/sberbank-ai/rugpt3medium_based_on_gpt2), ответ выводится в консоль. Так создаётся бесконечный *манифест-палимпсест* природы. Но в него можно внести изменения: если ввести в поле «Что такое природа?» свою версию ответа на вопрос (или вообще что угодно), ответ обработается нейросетью и займёт место среди прочих.

Для демонстрации сначала нужно установить виртуальное окружение из `requirements.txt`, затем вставить API-ключ от [YandexSpeechKit](https://cloud.yandex.ru/services/speechkit) в файл `scripts/auth.txt`, запустить скрипт `form.py` (поднять сайт-форму), открыть её, введя в строке браузера `http://127.0.0.1:5000/`, а затем запустить **в командной строке** из-под виртуального окружения файл `main.py`. Пример команды:
`venv/Scripts/python.exe main.py`

---

[![postmorphoses demo](http://img.youtube.com/vi/Htbzcj6OevE/0.jpg)](http://www.youtube.com/watch?v=Htbzcj6OevE)


https://user-images.githubusercontent.com/91334765/197907341-aaa27f09-7fe7-4944-9ce3-0a04f0ebba10.mp4


---

**Exposition history**

First exposed on [*OtherSiders*](https://othersiders.space/) Festival at ITMO 15.10.2022: [commit](https://github.com/andreygetmanov/postmorphoses/tree/e01e5eb90da39c74704ae84e785725896b58f81b) 

| [TV report](https://www.youtube.com/watch?v=j546fPJ99d4) (2:56) |
