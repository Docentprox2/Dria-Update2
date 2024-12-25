# Dria-Update2
Dria güncelleme Gemini


screene giris yapalim

screen -r dria
Çalışan servis varsa ctrl+c ile durduralım

DKN_WALLET_SECRET_KEY i bir yere not edin

  nano ~/dkn-compute-node/.env
rm -rf dkn-compute-node
güncelleme

sudo apt update && sudo apt upgrade -y
curl -fsSL https://ollama.com/install.sh | sh
Dria kurulumu

curl -L -o dkn-compute-node.zip https://github.com/firstbatchxyz/dkn-compute-launcher/releases/latest/download/dkn-compute-launcher-linux-amd64.zip
unzip dkn-compute-node.zip
cd dkn-compute-node
Buradan bir Gemini_api_key alalim https://ai.google.dev/gemini-api/docs/api-key?hl=tr

.env içerisine DKN_WALLET_SECRET_KEY i ve GEMINI_API_KEY i ekliyoruz.

nano .env
ctrl+x y enter ile çıkalım

Dria yı çalıştırıyoruz

ollama pull hellord/mxbai-embed-large-v1:f16

./dkn-compute-launcher -m=gemini-1.5-flash,llama3.1:latest
Gemini api key isterse tekrar girelim.Digerlerini enter ile gecelim.
