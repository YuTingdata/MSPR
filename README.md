

# How to use

## Step 1

```shell
docker-compose up -d
```

## Step 2

To start using jupyter,
you can check `https://localhost:8888`
It will ask for a password/token

To get the token, check in the docker logs for the container
```shell
docker logs jupyter
```
Then copy-paste the token in the website.
Will will then be able to write notebooks through the browser.


