# v2fly
This project makes your v2ray up and running using docker compose.
## Prerequirements
* A VPS (debian 11 recommended)

## Steps
1. Install docker & docker compose
```bash
https://docs.docker.com/engine/install/debian/
```

2. Create your own UUID (It's just a string)
```bash
https://www.uuidgenerator.net/version1
```

3. Clone the project into your VPS
```bash
git clone https://github.com/naghiloo/v2fly.git
cd v2fly
```

4. Edit the config.json
  * Define your port at line 7
```bash
"port": 1310,
```

  * Replace your UUID at line 15
```bash
"id": "<your-uuid>",
```

  * Replace your email at line 18
```bash
"email": "<your-email>"
```

5. Make your v2fly up and running
```bash
docker compose up -d
```
