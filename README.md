# 📊 Assistente Inteligente de Análise de Dados

Este projeto é um sistema web que utiliza Inteligência Artificial para auxiliar na análise de dados e visualização gráfica. Desenvolvido com foco em simplicidade de uso e apresentação clara, o sistema permite que usuários façam perguntas sobre dados, recebam sugestões baseadas em IA e gerem gráficos com arquivos `.csv`.

---

## 🚀 Funcionalidades

- ✅ Upload de arquivos CSV para análise
- ✅ Geração automática de gráficos (Plotly)
- ✅ Interação com IA via API (OpenRouter)
- ✅ Sugestões inteligentes com base em perguntas do usuário
- ✅ Design responsivo e amigável com React + CSS customizado

---

## 🛠️ Tecnologias Utilizadas

**Frontend:**
- React.js
- Axios
- Plotly.js
- React Icons

**Backend:**
- Node.js
- Express.js
- Axios
- body-parser
- dotenv

**Outros:**
- OpenRouter API com modelo `nousresearch/deephermes-3-mistral-24b-preview`
- Estilização com CSS customizado e fontes do Google Fonts

---

## 📂 Estrutura do Projeto

```data-analysis-app/
├── backend/
│ └── index.js
├── frontend/
│ ├── App.js
│ ├── App.css
│ └── .env
├── README.m
```
---

## ⚙️ Como Rodar Localmente

1. **Clone o repositório**
```bash
git clone https://github.com/seuusuario/data-analysis-app.git
```

```bash 
cd data-analysis-app
```

```bash
OPENROUTER_API_KEY=sk-...
```
```bash
node index.js
```
```bash
cd ../frontend

npm install

npm start

```
---

## 🧠 IA Utilizada

O modelo utilizado é o nousresearch/deephermes-3-mistral-24b-preview, acessado via OpenRouter. O prompt principal orienta o modelo a atuar como um especialista em análise de dados.

## 📈 Visualização de Dados
Os dados são extraídos do CSV e desenhados usando o Plotly.js, com um gráfico dinâmico do tipo scatter (linhas e marcadores).

## 🖌️ Sugestões de Design (a melhorar)
O layout atual foi prototipado rapidamente no Figma, mas recomenda-se refatorar o design com foco em:

- Responsividade

- Espaçamento proporcional ao conteúdo

- Padronização de ícones e botões

- Uso de bibliotecas de UI como Tailwind ou Material UI

## 🔐 Segurança

- Não compartilhe sua chave .env publicamente.

- O projeto já utiliza dotenv para proteger a API Key.

- Recomenda-se um proxy backend para não expor diretamente a OpenRouter ao frontend

## 📄 Licença
Este projeto está sob licença MIT. Veja o arquivo LICENSE para mais detalhes.

## ✨ Autor
***Desenvolvido por:***

 **Gabriel Marques 🚀***
