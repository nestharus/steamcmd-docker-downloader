# Personal Machine Tools For Maintaining Images!
### Prepare Your Machine For The Tools
1. https://www.pythontutorial.net/python-basics/install-pipenv-windows/
2. https://docs.docker.com/desktop/install/windows-install/
3. From root of this project
    - `pipenv install`

### Download/Update The Server Files From Steam
1. Copy docker-compose.yml, .env to server image directory under a subdirectory
2. Modify .env with steamappid and download folder
3. `docker-compose up`