# **Machine Learning Project Template**

![workflow status](https://github.com/rohwid/machine-learning-project-template/actions/workflows/builder.yml/badge.svg)

Steps:
+ Create virtual enviroment

    ```bash
    virtualenv .venv -p /usr/bin/python3.10
    ```
+ Activate the virtual enviroment

    ```bash
    source .venv/bin/activate
    ```

+ Install package.

    ```bash
    pip install -r requirements.txt
    ```

+ enable the enviroment variables.

    ```bash
    cp .env.example .env
    ```

+ `main.py` to runs the ML pipeline.
+ `app.py` to runs the ML application.