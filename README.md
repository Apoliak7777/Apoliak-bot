# Lorelei

## Installation

### Systemd

You can use systemd (linux) to run this bot

1. Put it in your desired directory (preffering `/var/lorelei-bot`)
2. Edit `lorelei.service` to match user with permissions to the directory (or leave on root, which can be unsafe) and directory to the folder
3. Place `lorelei.service` into `/etc/systemd/system/`
4. Create file named `.secret.key` and put your token inside
5. Install dependencies

```bash
pip install -r requirements.txt
```
(if you run it as root, place `sudo` before command)

6. Enable and start the service
```bash
sudo systemctl enable lorelei.service
sudo systemctl start lorelei.service
```

### Pterodactyl

You can also run it using pterodactyl (UPTDATER DOESNT HAVE TO WORK)

1. Place repository into root of the pterodactyl
2. Add all requirements from `requirements.txt` into your settings
3. Set main file as `run.py`
4. (Optional) Disable autoupdate in `config.py` for better stability, **You will have to update manually**
5. Start
## Config
work in progresssssssssssss
