# Гайд по лендингу в creatio

* Склонируйте репозиторий
    ```bash
    git clone https://github.com/Zayac11/creatio
    ```
* Создайте публичный репозиторий на github.com
* Перейдите в папку с проектом
* Индексируйте все изменения, коммит и сделайте пуш в созданный репозиторий
    ```bash
    git remote set-url origin https://github.com/{your github name}/{repository name}.git
    git add .
    git commit -m "cloned repo"
    git push --force
    ```
* В Creatio перейдите в раздел Лендинги и web-формы > Добавить > Форму регистрации контакта
* Заполните поле Название
* Откройте файл index.html на устройстве
* Замените выделенные строки в файле index.html на ваши
![Иллюстрация к проекту](https://github.com/Zayac11/creatio/blob/master/assets/lines.png)
* В локальном репозитории создайте ветку gh-pages
    ```bash
    git checkout -b gh-pages
    ```
* Сделайте пуш в репозиторий гит
    ```bash
    git push -u origin gh-pages
    ```
* Перейдите в появившуюся вкладку Environments
![Иллюстрация к проекту](https://github.com/Zayac11/creatio/blob/master/assets/env.png)
* Нажмите на кнопку View deployment
![Иллюстрация к проекту](https://github.com/Zayac11/creatio/blob/master/assets/deploy.png)
* Далее откроется страница с формой, если открывается страница с 404 ошибкой - просто подождите
* После заполнения формы и её отправки в Creatio перейдите на вкладку Контакты и отфильтруйте их по дате создания
