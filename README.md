# Simple PHP project on Docker.Simple PHP project.

### Requirements

- [Docker](https://www.docker.com/get-started) (version 20.10+)
- [Docker Compose](https://docs.docker.com/compose/install/) (version 2.0+)


## 🚀 Quick Start
### 1. Clone the project
```bash
git clone <https://github.com/melissapixel/project/>
cd my-php-app
```

### 2. Run the project
```bash
docker-compose up -d
```
Access:`http://localhost:8000/`

Ready! 🎉


## 🛠️ Useful commands
| Comand             | Description                                                                |
| ----------------- | ------------------------------------------------------------------ |
| `docker-compose up -d` | Run a project in the background |
| `docker-compose down` | Stop the project |
| `docker-compose restart` | Restart the container |
| `docker-compose logs -f` | Show logs in real time |
| `docker-compose exec app php -v` | Check PHP version |


⚙️ Settings
- **Port**: 8000 (can be changed in `docker-compose.yml`)
- **PHP version**: 8.2
- **Web server**: Built-in PHP server (for development)

