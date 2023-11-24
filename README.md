This docker-compose downloads 
[audio-webui](https://github.com/gitmylo/audio-webui)
And helps you to run it, it exports huggingface and env directories to local folder, for more info just read the code, it is about 100 lines total :)

# run it using 
```
docker compose up
```

## SSH into the container
```
docker exec -it <name> /bin/bash
```

## Start the application
```
pip install --upgrade virtualenv
virtualenv -p python3 venv
pip install tensorboardX
./run.sh --listen
```
- [Open the web interface](http://localhost:7860/)

## Doc to running
https://github.com/gitmylo/audio-webui#-running

