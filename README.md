# Volara Node Setup
# Requirements
- Ubuntu 22.04.
- 4 cores, 8 GB RAM 160 gb disk.
- ben buna kurdum içinde 5 tane daha node var
# Linux Installation
```yaml
sudo apt update && sudo apt upgrade -y && sudo apt install -y apt-transport-https ca-certificates curl software-properties-common && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg && echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null && sudo apt update && sudo apt install -y docker-ce docker-ce-cli containerd.io
```
>
```yaml
screen -S volara
```
>
```yaml
[ -f "volara.sh" ] && rm volara.sh; curl -s -o volara.sh https://raw.githubusercontent.com/volaradlp/minercli/refs/heads/main/run_docker.sh && chmod +x volara.sh && ./volara.sh
```
>
# additional information
- Metamask private key isteyecek onu yapıştıralım. twitter şifrenizi ve twitter isminizi soracak başında @ işareti olmadan yazın.
size bir link verecek o linki kopyalın tarayıcınıza ve mail adresiniz ile giriş yapın ardından size verilen kodu yapıştırın sunucunuza
# metamask'a ağı ekleme ve faucet
- https://faucet.vana.com/moksha
- https://docs.vana.org/docs/overview#setting-up-the-network
