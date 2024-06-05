<h1 align="center">Global Solution - 2º Semestre - 1º Ano - 1ESPR</h1>

<hr/>

<p align="center">
  <a href="#pushpin-Desafio">Desafio</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bulb-Solução">Solução</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#hammer_and_wrench-Tecnologias-e-Ferramentas">Tecnologias e Ferramentas</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-Como-Utilizar">Como Utilizar</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologist-Integrantes">Integrantes</a>
</p>

<hr/>

## :pushpin: Desafio
O Desafio de “Inovação Azul” 2024 incentiva os estudantes, entusiastas de tecnologia, inovação e sustentabilidade, a contribuir para soluções que promovam uma gestão sustentável dos oceanos.
Buscamos projetos que alertem e informem as populações costeiras e as empresas que utilizam os mares para existência e subsistência sobre a saúde dos oceanos.

## :hammer_and_wrench: Tecnologias e Ferramentas
Este projeto utilizou as seguintes tecnologias e ferramentas:
* [Wokwi](https://docs.wokwi.com/pt-BR/)
* [C++](https://pt.wikipedia.org/wiki/C%2B%2B)
* [Node-RED](https://nodered.org/)
* [TagoIO](https://tago.io/)
* [Firebase](https://firebase.google.com/)

## :bulb: Solução
Como solução, criamos um circuito Arduino que utiliza sensores para obter dados sobre a qualidade dos mares e os envia para o banco de dados do Firebase da Google.


### Circuito
<h4>Componentes</h4>
<ul>
  <li><b>ESP32</b>: uma placa microcontroladora de código aberto com Wi-Fi e Bluetooth.</li>
  <li><b>DHT22</b>: um sensor desenvolvido para medir temperaturas da faixa de -40°C a +80°C.</li>
  <li><b>LDR</b>: um resistor cuja resistência varia conforme a intensidade da luz que incide sobre ele.</li>
  <li><b>LED</b>: luz de led.</li>
  <li><b>LDR e LED foram utilizados para simular um sensor de turbidez da água, uma vez que o Wokwi não possui esse sensor.</b></li>
</ul>

<img src="https://github.com/Rafafaaa-FIAP/GS02-EDG/blob/main/circuit.png" alt="circuit" width="500" />
<h6>Acesse o projeto clicando <a href="https://wokwi.com/projects/399175551749774337">aqui</a>.</h6>

### Fluxo
<img src="https://github.com/Rafafaaa-FIAP/GS02-EDG/blob/main/flow.png" alt="fluxo" width="500" />
<h6>Acesse o JSON para importação no Node-RED clicando <a href="https://github.com/Rafafaaa-FIAP/GS02-EDG/blob/main/flows.json">aqui</a>.</h6>

### Dashboard no TagoIO
<img src="https://github.com/Rafafaaa-FIAP/GS02-EDG/blob/main/dashboard.png" alt="dashboard" width="500" />

### Firebase
<img src="https://github.com/Rafafaaa-FIAP/GS02-EDG/blob/main/firebase.png" alt="firebase" width="500" />

### Vídeo Demonstrativo
Acesse o vídeo de demonstração do funcionamento clicando <a href="https://youtu.be/f0vBU6J-aKE">aqui</a>.

## :gear: Como Utilizar
1. Acessar o circuito montado no Wokwi;
2. Instalar o Node-RED;
3. Iniciar o Node-RED no computador;
4. Importar o fluxo no Node-RED no computador e fazer o deploy;
5. Acessar a plataforma TagoIO e acessar a dashboard.

## :technologist: Integrantes
* RM 552980 - Danilo Vieira
* RM 553521 - Rafael Cristofali