# basic-sentiment-analysis

This project is a very simple example of sentiment analysis with Python.

There is a prebuilt image available on DockerHub.

# Build steps

```commandline
docker build .
```

```commandline
docker tag <image-id> boneff/basic-python-sentiment-analysis:latest
```

```commandline
docker push boneff/basic-python-sentiment-analysis:latest
```

# Usage

```commandline
docker run --rm -it boneff/basic-python-sentiment-analysis:latest bash
```

```commandline
pipenv run python main.py
```
