# 🌦️ Weather App

Um site simples de previsão do tempo desenvolvido para praticar o consumo de APIs e manipulação de dados em aplicações web.

## 🚀 Objetivo

Este projeto foi criado com o objetivo de aprender na prática:

- Como consumir uma API REST.
- Trabalhar com requisições HTTP (`fetch` ou `axios`).
- Manipular dados em formato JSON.
- Exibir informações dinâmicas na interface.
- Organização de um projeto front-end.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação do conteúdo.
- **CSS3**: Estilização e responsividade.
- **JavaScript (ES6+)**: Lógica de consumo da API e manipulação do DOM.
- **OpenWeatherMap API**: Fonte de dados climáticos em tempo real.

## 🔌 Como funciona a API

O sistema faz uma requisição para a API de clima, enviando o nome da cidade informada pelo usuário. A API retorna um objeto JSON contendo:

- **Temperatura:** Valor atual e variações.
- **Sensação térmica:** Percepção real de calor/frio.
- **Umidade:** Percentual de umidade do ar.
- **Condição do tempo:** Descrição detalhada (chuva, sol, nublado, etc.) e ícones correspondentes.

## 📦 Como rodar o projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/RFP40/Previsao_Tempo.git

2. **Acesse a pasta do projeto**
   ```bash
    cd Previsao_Tempo

3. **Configuração da API**
- Crie uma conta gratuita no [OpenWeatherMap.](https://openweathermap.org/)
- Obtenha sua `API KEY`
- Substitua a chave no código JavaScript:
    ``` JavaScript
    const key ="Insira_a_chave_aqui"
4. **Execução**
Abra o arquivoo `index.html` diretamente no navegador, ou, a extensão `live server` no VSCODE


## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
  
