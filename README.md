![Фотка](https://github.com/Filmans/WinLocker/assets/80627579/e18b134e-21ed-4dfb-ba98-e0f6508e457d)
# Винлокер 2023 года :)))))))
``Разработан на Python. Блокирует клавиатуру, отчет времени на 3 часа. 
Если в течение 3-х часов вы не ввели пароль или истратили 7 попыток. то выходит BSOD и комп перезагружается.``

# Опасность использования
Данный винлокер является "легкой" версией. Тоисть не причиняет вреда системе, а только пунает жерту : )

# Установка пароля для жертвы
В коде на 78 строке есть строчка:  ``if password == "123"`` - эта строка и отвечает за правильный пароль.
По умолчанию я написал пароль ``"123"``.

# Компиляция в EXE файл
1. Установите pyinstaller

``pip install pyinstaller``

2. В консоле или терминале перейдите в папку, куда сохранили код
3. ``введите pyinstaller WinLocker.py``
4. Подождите, пока выполнится процесс
5. При окончании процесса введите:

``pyinstaller -F WinLocker.py``

6. Файл EXE готов. Он будет сохранен в папке, куда вы сохранили код.

# Установка нужных компонентов
В принципе в коде задействованы все стандартные библиотеки.
Установить надо только будет **keyboard**

``pip install keyboard``

больше ничего устанавливать не нужно для работы кода.

# ОТКАЗ ОТ ОТВЕТСТВЕННОСТИ
``Я, как разработчик данного програмного обеспечения отказываюсь от ответсвенности за ваше использования моей разработки!``
``Вы совершаете действия на свой страх и риск.``

# Связь с разработчиком
Телеграм [GitHub Pages](https://t.me/Codefer)
