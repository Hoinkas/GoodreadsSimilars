# GoodreadsSimilars

# Requirements
* Python 3.8
* MongoDB 4.4
* Docker

# Installation
To install the project, run the following command:
```shell
git clone
```

### Python
```bash
pip install -r ./requirements.txt
```

### MongoDB
```bash
sudo apt update
sudo apt install -y mongodb
sudo systemctl start mongod
```

### Docker
```bash
sudo sysctl -w kernel.apparmor_restrict_unprivileged_userns=0
systemctl --user restart docker-desktop
docker compose stop; docker compose rm -f; docker compose pull; docker compose build --no-cache; docker compose up -d
```

## Usage
To run this project, you need to run the following commands:

```bash
python3 app.py
```
