# flask 조사하기


flask
micro 웹 프레임 워크

필요한 것만 제공하고 가벼운 느낌

flask의 단점? 따로 필요한 기능들을 pip로 인스톨 해야댐.

beginner 추천

Django에 비해서 가벼운 느낌

가볍지만 강력함


flask 구조

pip install flask 로 인스톨
그런데 파이썬에 기본적으로 있는듯하다

/home/user/Projects/flask-tutorial
├── flaskr/
│   ├── __init__.py
│   ├── db.py
│   ├── schema.sql
│   ├── auth.py
│   ├── blog.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   └── blog/
│   │       ├── create.html
│   │       ├── index.html
│   │       └── update.html
│   └── static/
│       └── style.css
├── tests/
│   ├── conftest.py
│   ├── data.sql
│   ├── test_factory.py
│   ├── test_db.py
│   ├── test_auth.py
│   └── test_blog.py
├── venv/
├── setup.py
└── MANIFEST.in

저장하는 영역이 다르다. 서버를 구성하는 줄기?



django 

웹 프레임워크
django 안에는 모든 것이 딸려온다
service를 직접 운영할 때는 장고가 더 낫다?

pip install Django 로 인스톨
안에 여러가지 익스텐션들이 있어서 인스톨하는데 시간이 조금 걸린다
