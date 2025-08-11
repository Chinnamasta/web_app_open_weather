### ☀️ Web App de Previsão do Tempo
Este é um projeto simples de um Web App para consulta de previsão do tempo, desenvolvido com Python e Streamlit. Ele utiliza a API do OpenWeather para buscar dados de clima em tempo real para qualquer cidade do mundo.

### ✨ Recursos
- Consulta por cidade: Digite o nome de uma cidade e veja as informações do clima.
- Dados em tempo real: Receba a temperatura, sensação térmica, umidade do ar e cobertura de nuvens atualizados.
- Interface intuitiva: Desenvolvido com Streamlit para uma experiência de usuário simples e limpa.
- Mensagens claras: Se a cidade não for encontrada, o aplicativo exibe um aviso amigável.

### 🚀 Como Rodar o Projeto 
Siga estes passos para configurar e executar o projeto localmente.

1. Pré-requisitos
Certifique-se de ter o Python e o pip instalados na sua máquina.

2. Chave da API do OpenWeather
Para usar a API do OpenWeather, você precisa de uma chave. Siga estes passos:
- Crie uma conta gratuita no OpenWeather.
- Gere sua chave da API.
- Guarde a chave, pois você precisará dela para a próxima etapa.

3. Configuração do ambiente
Clone o repositório:
git clone [URL_DO_SEU_REPOSITORIO]
cd [pasta-do-repositorio]
Crie um ambiente virtual (recomendado):
python -m venv .venv
Ative o ambiente virtual:
- Windows: .\.venv\Scripts\activate
- macOS/Linux: source ./.venv/bin/activate
Instale as dependências:
pip install streamlit requests python-dotenv
Crie o arquivo .env:
Na raiz do projeto, crie um arquivo chamado .env e adicione sua chave da API da seguinte forma:
CHAVE_API_OPENWEATHER="SUA_CHAVE_AQUI"
Lembre-se de substituir "SUA_CHAVE_AQUI" pela sua chave real da API.
Execute o aplicativo:
streamlit run seu_arquivo.py
O aplicativo será aberto automaticamente no seu navegador padrão. Divirta-se! 🎉

### 🛠️ Tecnologias Utilizadas
- Python
- Streamlit
- Requests
- python-dotenv

### 🤝 Contribuições
Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests. Toda contribuição é bem-vinda!
