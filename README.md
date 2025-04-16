# uv - python tools

ref:

- [https://www.youtube.com/watch?v=l6WyNOIk0Ng]
- [https://github.com/astral-sh/uv]
- [https://docs.astral.sh/uv/]

## introduction

uv is good, use uv.

## 2 installation

### 2.1 (prefer) use `pip`

```bash
pip install uv
```

## 3 project, application

```bash
uv init $my_project
```

or

```bash
cd $my_project
uv init
```

## 4 install liberary

```bash
uv add $my_lib
```

## 5 run

```bash
uv main.py
```

or

```bash
uv run main.py
```

## python env

install different python versions

```bash
uv python install 3.10 3.11 3.12 3.13
```

check avaliable python versions

```bash
uv python list
```

select python version

```bash
uv python pin # to check the cuurent version
uv python pin 
```

create venv

```bash
uv venv #will create .venv folder
uv venv $my_env
```

to activate venv

```bash
.venv\Scripts\activate
```
