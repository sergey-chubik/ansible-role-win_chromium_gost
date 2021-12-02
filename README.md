Ansible Role: Win-Chromium-GOST
=========

Эта роль установит Chromium-GOST x64 на ОС Windows.
Версия Chromium-GOST 89.0.4389.128

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены вместе со значениями по умолчанию (см. `defaults/main.yml`). Роль установит и настроит окружение пользователя (UserData.exe), расширениях браузера (chrome://extensions/) для работы в Электронном бюджете и СУФД. На панели закладок необходимо исправить ссылки на адрес сервера СУФД своего региона или исправить файл Bookmarks.
Запускать браузер необходимо с ярлыка на рабочем столе!

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - win_chromium_gost

License
-------

BSD

Author Information
------------------

Chubik Sergey, sergey.chubik@mail.ru.
Chubik Sergey, chubik@ekaterinburg.fsin.uis.
