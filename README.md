# MixWeather - Previsão do Tempo

MixWeather é um aplicativo simples e prático para consultar a previsão do tempo utilizando a API do OpenWeatherMap.

## Funcionalidades

- **Pesquisa por Cidade:** Insira o nome de uma cidade para obter informações atualizadas sobre o clima.
- **Modo Escuro:** Alternância entre modo claro e escuro no emoji de lua para melhor visualização.
- **Visualização Gráfica:** Gráfico de previsão de temperatura e chuva para os próximos 5 dias.

## Como Instalar e Rodar Localmente

### Pré-requisitos

- Certifique-se de ter Node.js instalado no seu sistema. Você pode baixá-lo em [nodejs.org](https://nodejs.org/).
- É necessário uma chave da API do OpenWeatherMap. Obtenha-a gratuitamente em [openweathermap.org/api](https://openweathermap.org/api).

### Configuração do Projeto

1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/MaaxTEAMPRO/mixweather.git
   ```

2. **Instale as Dependências:**
   ```bash
   cd mixweather
   npm install
   ```

3. **Configure a Chave da API se necessário:**
   - Abra o arquivo `index.html`.
   - Encontre a linha `const apiKey = 'sua-chave-da-api';`.
   - Substitua `'sua-chave-da-api'` pela chave da sua conta do OpenWeatherMap.

### Executando o Aplicativo

1. **Inicie o Servidor Local:**
   - Utilize um servidor HTTP para carregar o arquivo HTML localmente. Recomendamos o [http-server](https://www.npmjs.com/package/http-server).
     ```bash
     npm install -g http-server   # Instala o servidor HTTP globalmente
     http-server                  # Inicia o servidor na pasta atual
     ```
   - Abra o navegador e navegue para `http://localhost:8080` (ou o endereço que o servidor local indicar).

2. **Utilize o Aplicativo:**
   - Na página inicial, insira o nome de uma cidade no campo de pesquisa e clique no botão "Pesquisar".
   - Os dados meteorológicos serão exibidos, incluindo temperatura, descrição do clima, umidade, vento, nuvens, pressão atmosférica e visibilidade.
   - Além disso, você poderá visualizar a previsão para os próximos 5 dias em um gráfico interativo.

## Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- [Chart.js](https://www.chartjs.org/) para visualização gráfica.

## API Utilizada

- **OpenWeatherMap API:** Utilizada para obter dados meteorológicos em tempo real e previsões futuras.

## Melhorias Futuras

- Adicionar suporte para mais detalhes climáticos, como índice UV e direção do vento.
- Implementar funcionalidade de geolocalização automática do usuário.
- Aprimorar a interface com mais feedbacks visuais e responsividade para diferentes dispositivos.

## Projeto

Este projeto foi desenvolvido por motivos educacionais e práticos, visando aplicar conhecimentos em desenvolvimento web simples.

---

Para contribuir ou reportar problemas, por favor, abra um issue ou faça um pull request diretamente no repositório. Agradeço sua colaboração!
