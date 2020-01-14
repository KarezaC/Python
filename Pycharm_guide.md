# Pycharm_Guide

*Author: kareza*

## How to create a Django project with Pycharm?

![Pycharm-welcome](./res/Pycharm-welcome.png)

You can use the template provided by Pycharm to create Django.

![Django-create-template](./res/Django-create-template.png)

Maybe you'll stop at this interface for a while.

![installing-Django](./res/installing-Django.png)

Then an error is reported,because the download of  Django has timed out.

![downloading-timed-out](./res/downloading-timed-out.png)

I suggest you use the second plan.

Close this window, open terminal, and start typing.

+ Install Django

  ```shell
  pip install -i https://pypi.doubanio.com/simple django
  ```

+ Start Project

  ```shell
  django-admin --version
  ```

  ```shell
  django-admin startproject hello_django .
  ```

  ```shell
  mkdir templates
  ```

+ Run Project

  ```shell
  python manage.py runserver
  ```

![run_Django_success](./res/run_Django_success.png)