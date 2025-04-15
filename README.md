# 🚴‍♀️ App Ride

Aplicação web que calcula a distância percorrida em uma corrida feita pelo usuário. Exibe informações detalhadas como o mapa com o percurso, velocidade em tempo real, tempo decorrido, data e local da corrida.

![Demonstração do App](.project_show/AppRide.gif)

## 🧩 Funcionalidades

- 📋 Tela inicial com lista de corridas registradas
- ➕ Botão para adicionar nova corrida
- 📍 Detecção de localização via GPS
- 🚀 Velocímetro em tempo real durante a corrida
- 🗺️ Visualização do percurso no mapa com Leaflet
- 📦 Armazenamento local (Local Storage)
- 🕒 Registro de tempo, data, local e velocidade média
- 📑 Detalhamento completo de cada corrida registrada

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Leaflet (API de mapas)
- API `navigator.geolocation`
- Local Storage

## ▶️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/app-ride.git

2. Inicie o index.html

## 📱 Testando no celular com Ngrok (opcional)

Para testar o App Ride com localização real em um dispositivo móvel, você pode usar o [Ngrok](https://ngrok.com/) para expor seu servidor local:

```bash
ngrok http 5500  # ou a porta em que seu app está rodando
