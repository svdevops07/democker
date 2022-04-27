# democker
demo docker

## How to run

```
# Download
git pull https://github.com/svdevops07/democker.git
cd democker/

# Run deploy
docker build -t democker:0.1 .
docker run -d -p 7777:8080 democker:0.1

# Run multistage
docker build -f Dockerfile-multistage -t democker-multistage:0.1 .
docker run -d -p 7778:8080 democker-multistage:0.1
```

## Resource
from video [hier](https://www.youtube.com/watch?v=ra80QpzrAWk&ab_channel=codelike)
