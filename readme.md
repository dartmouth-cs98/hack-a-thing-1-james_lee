# Readme

## Description

I built a web application using the Django framework and implemented a basic chat functionality that allows users to join a chat room and send messages to each other.  I utilized a package called Django channels that allows easier handling of websockets and chat protocols. Also, since I have some experience with React, I wanted to learn how to integrate react into a Django framework, and therefore created the frontend with React.

## What I learned

I learned the basics of Django and how to create a simple, functioning Django application. Since Django is used for more full stack application, I learned how to create the frontend within django, as well as the integration of models that save data into sqlite. I also learned how to implement chat functionality within the application, using Django channels to handle user connection/disconnection as well as sending/receiving messages via websockets. Lastly, I learned how to integrate React within a Django application in order to create a richer, more dynamic front end.

## What didn't work

I initially had a lot of trouble trying to understand the format of Django, and how the different files are integrated (how do the views.py, urls.py, routing.py, and models.py all relate?). But going through this sample application slowly helped me understand the Django workflow a bit better.

In addition, the application lacks the functionality of differentiating users within the chat room, since I have yet to integrate user authentication. If I had the time to do so, the application would have a much more functional chat room that allows all different users to enter a chat room and send messages (currently there is only one user that sends messages).

## Instructions

### Installing
```
git clone https://github.com/dartmouth-cs98/hack-a-thing-1-james_lee.git
```
install necessary packages
```
cd frontend
yarn install
cd ../djangochat
pip install -r requirements.txt
```

### Deployment
create two terminals- in one terminal navigate to the frontend folder and type ```yarn start```
in the other terminal navigate to the djangochat folder and type ```python3 manage.py runserver```


## Resources

[https://channels.readthedocs.io/en/latest/](https://channels.readthedocs.io/en/latest/)
[https://www.youtube.com/watch?v=Wv5jlmJs2sU&list=PLLRM7ROnmA9EnQmnfTgUzCfzbbnc-oEbZ&index=1](https://www.youtube.com/watch?v=Wv5jlmJs2sU&list=PLLRM7ROnmA9EnQmnfTgUzCfzbbnc-oEbZ&index=1)