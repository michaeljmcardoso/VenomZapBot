# Zap-Bot Mística IA

Este projeto explora a integração de um Chat baseado em inteligência artificial com o WhatsApp, transformando o chatbot em um assistente virtual capaz de realizar tarefas como falar com amigos, responder a perguntas de clientes, e muito mais, com um toque de humanização nas conversas.

## 📚 Como funciona

A integração começa com o [wpconnect](https://github.com/wppconnect-team/wppconnect), que estabelece a conexão com o WhatsApp. <br/>
As mensagens recebidas são então processadas pela API do ChatGPT ou Gemini, que gera respostas coerentes e personalizadas.<br/>
Utilizamos um [assistant](https://platform.openai.com/docs/assistants/overview) da OpenAI, que é um do modelo OpenAI que foi pré-configurado com prompts detalhados. </br>
No caso do Gemini usamos um prompt pronto para instruções do modelo. </br>
Esses prompts orientam o assistente sobre como responder de maneira coerente e personalizada, assegurando que as interações não só se mantenham relevantes e engajantes, mas também reflitam uma abordagem humana e natural na conversação.

## 🚀 Como rodar o projeto
npm i para instalar as dependências
npm run config para ajustar as configurações: escolher entre gpt ou gemini; carregar o prompt; inserir chave de ID
npm run dev para rodar o programa

## 🧪 Informações adicionais
