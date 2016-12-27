## CodexGigas
This repository contains the minimal files to run CodexGigas in [Remnux](https://remnux.org/) 

## Installation
First install [docker](https://www.docker.com) and [docker-compose](https://docs.docker.com/compose/) (```pip install -U docker-compose```), then:
```
git clone https://github.com/codexgigassys/remnux-codex
cd remnux-codex/codex-backend/
sudo docker-compose up
```

Then browse to ```http://127.0.0.1:6100```. A folder called ```mongo-data``` will be created with the database. To add new files, copy them to ```files_to_load``` folder and use the ```Load``` of the menu. You can delete the files in the folder after they have been loaded. For the complete documentation, go to the [repo](https://github.com/codexgigassys/codex-backend).
