# pre-requisites
```bash
pip3 install django
pip3 install pyyaml ua-parser user-agents
pip3 install django-user-agents
pip3 install matplotlib
```

# Development server
```bash
cd targetAquired
python3 manage.py runserver
```

# Web server at: https://eu.pythonanywhere.com/

User: X2

Password: x2teampassword

# Default users:
Login as each user type with credentials below. 

## TAs
usernames: a12346bc, d12346ef, g12346hi

password: ta_password

## lecturer
username: z98765le
password: password

## demo admin user - can create/drop tables
username: demo
password: demo

# Front-end Dev
Modify files within targetAquired/main_site/templates
Put all image files within /static/ and reference using ```"{% static 'imageName.extension' %}"```

ALternatively, login to live website and develop there.
Make sure to refresh website to view changes - see web tab. 