# SimpleBooksStoreDjango

https://user-images.githubusercontent.com/26525615/218316720-2970c0c3-c4a8-4f03-b20f-7bec36461979.mp4


Before you run the application you need to create the DB tables:

     python ./manage.py migrate

Now you can run the development web server on the port 8002:

     python ./manage.py runserver 8002

To access the applications go to the URL <http://localhost:8002/>

Also you need  a user and password to access "books\_fbv\_user application

you need to create a user to test this app, you can create a user using the following command:

    python ./manage.py createsuperuser

To create a normal user (non super user), you must login to the admin page and
create it: <http://localhost:8002/admin/>
