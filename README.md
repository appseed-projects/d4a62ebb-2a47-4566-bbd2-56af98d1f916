# Datta Able Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Datta Able](https://appseed.us/generator/datta-able/)** a modern Bootstrap design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).

<br />

> Context:

- Built with [Datta Able Generator](https://appseed.us/generator/datta-able/)
- Timestamp: `2022-05-12 13:21`
- Build ID: `d4a62ebb-2a47-4566-bbd2-56af98d1f916`

<br />

> 👉 **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

## ✨ Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True

...
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:85` in your browser. The app should be up & running.

<br />


![Datta Able - Open-source seed project crafted in Django.](https://user-images.githubusercontent.com/51070104/167302688-3158f673-b5dd-4a26-a8a0-da11910a83a6.png)

<br />

## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/d4a62ebb-2a47-4566-bbd2-56af98d1f916.git
$ cd d4a62ebb-2a47-4566-bbd2-56af98d1f916
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />

## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Designed for those who like bold elements and beautiful websites, **Datta Able** is the most stylish Bootstrap 4 Admin Template compare to all other Bootstrap admin templates. It comes with high feature-rich pages and components with fully developer-centric code. 

- 👉 [Flask Datta PRO](https://appseed.us/product/datta-able-pro/flask/) - product page
- 👉 [Flask Datta PRO](https://flask-datta-able-pro.appseed-srv1.com) - LIVE Deployment

<br >

![Datta Able PRO - Flask](https://user-images.githubusercontent.com/51070104/167877982-b057f319-dbe0-4b9f-af7d-03ccf403d327.jpg)

<br />

---
Datta Able Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
