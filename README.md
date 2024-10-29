## Wolf app 01

### How to run ?
Use the following command in your terminal to launch the app :
```python3 wolf.py```

### How to build / tune with docker ?

[Install docker on your host system](https://docs.docker.com/engine/install/)

Run with docker :
```docker run -i -t wolfunit/vpn_wolf:2```

Change the starting options in *entrypoint.sh*
Then build a new image with the following command :
```
docker build . -t <YOUR-REPO>/vpn_wolf:3
```

🇺🇦 ⚡- 2024 - Wolf-A
