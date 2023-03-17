# Dev-Environment mit Docker Compose

Dieses Repository enthält eine `docker-compose.yml`-Datei, die ein komplettes Dev-Environment mit einer WordPress-Installation und einer MySQL-Datenbank auf Port 3306 erstellt.

## Voraussetzungen

Bevor Sie dieses Dev-Environment verwenden können, müssen Sie Docker und Docker Compose auf Ihrem System installieren. Bitte folgen Sie den Installationsanweisungen auf der offiziellen Docker-Website:

- [Docker installieren](https://docs.docker.com/engine/install/)
- [Docker Compose installieren](https://docs.docker.com/compose/install/)

## Verwendung

1. Klonen Sie dieses Repository auf Ihren Computer:

```
git clone https://github.com/yourusername/your-repo.git
```

2. Navigieren Sie in das Verzeichnis des Repositorys:

```
cd your-repo
```

3. Starten Sie den Docker-Compose-Stack mit dem Befehl:

```
docker-compose up -d
```

Dieser Befehl startet die Container für die MySQL-Datenbank und die WordPress-Installation im Hintergrund. Nachdem der Stack gestartet wurde, können Sie auf die WordPress-Website zugreifen, indem Sie `http://localhost` in Ihrem Browser eingeben.

Um den Docker-Compose-Stack zu stoppen, navigieren Sie zum Verzeichnis des Repositorys und führen Sie den Befehl `docker-compose down` aus. Dieser Befehl stoppt und entfernt alle Container und Netzwerke, die von Docker Compose erstellt wurden.

Wir hoffen, dass Ihnen dieses Dev-Environment nützlich ist!
