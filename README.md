<h1 align="center">Скрипт для скачивания фотографий пользователей / групп / бесед ВКонтакте</h1>

<div align="center">
	<a href="https://github.com/YarikMix/vk-admin-bot/vk-photos">
		<img src="https://img.shields.io/github/stars/YarikMix/vk-photos" alt="Stars Badge"/>
	</a>	
</div>


### Системные требования:

* Python 3 и выше
* Доступ к интернету
* Логин и пароль от ВКонтакте

### Как использовать:

Скачиваем зависимости:
```bash
pip3 install -r requirements.txt
```

В файл config.yaml вписываем свой логин и пароль от ВКонтакте:
```yaml
login: ""  # Ваш логин он ВКонтакте
password: ""  # Ваш пароль он ВКонтакте
token: ""  # Ваш токен (для скачивания фото участников беседы)
```

Запускаем скрипт:
```bash
python vk-photos/main.py
```

Вводим 1, 2, 3 в зависимости от того, чьи фото мы хотим скачать
![](https://github.com/YarikMix/vk-photos/raw/main/images/1.png)

Узнать id человека или группы ВКонтакте можно [тут](https://regvk.com/id/)

После того, как все фотографии скачаются, появится папка 'Фотки' c фотографиями<br><br>
![](https://github.com/YarikMix/vk-photos/raw/main/images/10.png)<br><br>
![](https://github.com/YarikMix/vk-photos/raw/main/images/21.png)<br><br>
![](https://github.com/YarikMix/vk-photos/raw/main/images/30.png)