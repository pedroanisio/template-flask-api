# README

## PIP requirements

```shell
pip install pipreqs
```

```shell
pipreqs . --force
```

```shell
pip install -r requirements.txt
```

## Virtualenv

```shell
virtualenv venv
```

```shell
source venv/bin/activate
```

## Run Flask

```shell
python src/main.py
```

## Docker

 ```shell
docker build -t flask-api:tag .
```
```shell
docker run -p 5000:5000 flask-api:tag
```
## directory report

```shell
cd /home/pals/code/utils/dir2gpt
python3 dir2gpt.py  /pwd/flask-api -d 3
```

```shell
clear && cat report.md
```