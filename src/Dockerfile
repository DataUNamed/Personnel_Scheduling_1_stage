FROM python:3.8


RUN pip install bidict==0.22.0 && \
    pip install cachelib==0.9.0 && \
    pip install click==8.1.3 && \
    pip install Flask==2.2.5 && \
    pip install Flask-Login==0.6.2 && \ 
    pip install Flask-Session==0.4.0 && \ 
    pip install Flask-SocketIO && \ 
    pip install importlib-metadata==4.12.0 && \ 
    pip install itsdangerous==2.1.2 && \ 
    pip install Jinja2==3.1.2 && \ 
    pip install MarkupSafe==2.1.1 && \ 
    pip install python-engineio && \ 
    pip install python-socketio && \ 
    pip install six==1.11.0 && \ 
    pip install Werkzeug==2.2.3 && \ 
    pip install zipp==3.8.1

workdir /bancolscheduler

copy . /bancolscheduler

CMD [ "python", "ai_app.py"]