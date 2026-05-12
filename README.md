# 🤖 Chatbot CS Nola

Chatbot interno desenvolvido para o time de Customer Success da Nola, 
uma plataforma de gestão para restaurantes.

## 🎯 Objetivo
Responder dúvidas operacionais do time de CS com base em uma 
base de conhecimento no Google Sheets, usando IA para gerar 
respostas humanizadas e precisas.

## 🛠️ Ferramentas utilizadas
- **N8N** — automação do fluxo
- **Google Sheets** — base de conhecimento
- **Groq (Llama 3.3 70B)** — motor de linguagem
- **Claude (Anthropic)** — apoio no desenvolvimento

## 🔄 Como funciona
1. Colaborador faz uma pergunta no chat
2. N8N busca toda a base no Google Sheets
3. Contexto é enviado para a IA (Groq)
4. IA responde com base exclusivamente na planilha
5. Resposta é exibida no chat com tom acolhedor

## 📋 Fluxo N8N
O arquivo `workflow.json` contém o fluxo completo pronto para importar no N8N.
