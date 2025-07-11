# 🔍 Análise de Sentimentos com Azure Language Studio

&nbsp;

## 📘 Descrição

Este projeto foi desenvolvido como parte de um laboratório prático com foco em **Azure AI**, utilizando as ferramentas **Azure Speech Studio** e **Language Studio**. O objetivo central é realizar **análise de sentimentos** em textos, explorando recursos de **Processamento de Linguagem Natural (PLN)** disponíveis na nuvem da Microsoft.

Além disso, foram registradas anotações e insights obtidos durante a prática, servindo como material de apoio para estudos futuros e implementações reais com serviços cognitivos da Azure.

&nbsp;

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
  - Azure Language Studio
  - Azure Speech Studio (módulo complementar)

&nbsp;

## 🚀 Etapas do Projeto

### 1. 📂 Criação do Recurso no Azure

- Acesse o [Portal do Azure](https://portal.azure.com/)
- Procure por **"Language Services"**
- Clique em **"Criar"**
- Preencha os campos:
  - Nome do recurso
  - Região
  - Grupo de recursos
  - Plano de tarifa (gratuito se disponível)
- Aguarde a implantação

&nbsp;

### 2. 🌐 Acesso ao Language Studio

- Acesse: [https://language.azure.com](https://language.azure.com)
- Faça login com sua conta Azure
- Selecione o recurso criado anteriormente
- Vá até **"Análise de Sentimentos"**

&nbsp;

### 3. ✍️ Inserção dos Dados para Análise

- Insira um ou mais textos de exemplo
- Selecione o idioma (Português)
- Clique em "Executar"
- O modelo exibirá o **sentimento predominante**: positivo, negativo ou neutro
- Também são mostradas **pontuações de confiança** para cada sentimento

&nbsp;

### 4. 💬 Complemento com Speech Studio (Opcional)

- Acesse: [https://speech.microsoft.com](https://speech.microsoft.com)
- Faça a transcrição de um áudio de fala para texto
- Use o texto transcrito como entrada no Language Studio

&nbsp;

### 5. 📝 Anotações e Insights

Durante a prática, alguns pontos relevantes foram observados:

- A análise de sentimentos é **sensível ao contexto e tom** do texto.
- Frases ambíguas podem resultar em sentimentos neutros.
- A ferramenta oferece uma boa base para aplicações como:
  - Atendimento ao cliente
  - Feedback de usuários
  - Monitoramento de redes sociais

&nbsp;

## 📌 Conclusão

Este projeto demonstrou, de forma prática, como utilizar as ferramentas de **Azure AI** para entender e analisar sentimentos em linguagem natural. Essa abordagem pode ser aplicada a diversos cenários reais, ampliando a capacidade de empresas e desenvolvedores de **tomar decisões baseadas em dados qualitativos**.
