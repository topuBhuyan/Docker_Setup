### `🐋` Docker_Setup `🚀`
![Build](https://img.shields.io/) 
```
 Step_1 `✅`
 
  echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] \
  https://download.docker.com/linux/debian bookworm stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```
```
Step_2 `✅`

sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/debian/gpg | \
sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
```
```
Step_3 `✅`

sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
```
Step_4 `✅`

sudo docker --version
sudo docker run hello-world
```
```
Step_5 `✅`

docker version

```
<img width="600" height="293" alt="docker" src="https://github.com/user-attachments/assets/d92e661b-2234-4636-9770-dfeb35e98db7" />

