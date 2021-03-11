# docker-dosbox

Run [DOSBox](https://www.dosbox.com/) in a docker container. I run it on my NAS.

1. Add your game archives or folders (you can get games e.g. from https://dosgames.com/)
2. Run `docker build -t dosbox .`
3. Start with `docker run -p 8080:8080 dosbox` or if you use a volume `docker run -p 8080:8080 -v /local/folder/with/games:/root/dos dosbox`
4. Connect with a browser to your docker host e.g. http://localhost:8080
