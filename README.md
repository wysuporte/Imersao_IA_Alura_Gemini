# Imersao_IA_Alura_Gemini
Chatbot Fitness com Alura e Google Gemini

# 🤖 Chatbot Fitness com Gemini (Google GenAI)

Este projeto implementa um chatbot fitness inteligente usando a API do Gemini da Google. O objetivo é auxiliar usuários com sugestões personalizadas de **alimentação** e **exercícios**, com base em informações pessoais fornecidas como **nome, idade, peso e altura**.

---

## 📌 Funcionalidades

- 🔹 Chat interativo com sugestões fitness personalizadas
- 🔹 Uso de modelos Gemini para geração de conteúdo em linguagem natural
- 🔹 Configuração de perfil do usuário (nome, idade, peso, altura)
- 🔹 Respostas baseadas nos dados fornecidos e nas solicitações feitas ao chatbot
- 🔹 Comando especial `"encerrar"` para terminar o atendimento

---

## ⚙️ Tecnologias Utilizadas

- Python 3 (Google Colab)
- [Google GenAI SDK](https://ai.google.dev/)
- Modelos: `gemini-2.0-flash`
- API Key (armazenada via `userdata.get` no Google Colab)

---

## ▶️ Como Executar

1. Clone este repositório:
git clone https://github.com/wysuporte/chatbot-fitness-gemini.git
cd chatbot-fitness-gemini

2. Instale as dependências
pip install google-genai

3. Defina sua API Key no ambiente (caso não esteja no Colab):
export GOOGLE_API_KEY='sua-chave-aqui'

4. Execute o script Python no terminal ou use diretamente no Google Colab.
https://goo.gle/alura-colab

💡 Como Usar
O chatbot solicitará seus dados pessoais:
Nome
Idade
Peso (kg)
Altura (cm)
Em seguida, você poderá interagir livremente com perguntas como:
Qual treino devo fazer hoje?
Sugira uma alimentação para emagrecer.
Como posso ganhar massa muscular?
Para encerrar a conversa, digite:
encerrar

📚 Base do Projeto
Este projeto foi desenvolvido com base na Imersão IA da Alura (2025).
https://www.alura.com.br/imersao-ia-google-gemini-ii

📸 Exemplo de Execução
--
🏋️‍♀️ Bem-vindo ao ChatBot Fitness com Gemini!

Digite seu nome: João

Digite sua idade: 28

Digite seu peso (em kg): 80

Digite sua altura (em cm): 178

---

Olá João! Agora posso te ajudar com dicas personalizadas. O que você deseja saber?

> Sugira um treino para perder gordura
Resposta: Você pode fazer 30 minutos de HIIT, seguidos de treino funcional com foco em membros inferiores. Faça 3x por semana.

> encerrar
✅ Atendimento encerrado. Até logo, João!


📫 Contato
Para dúvidas ou sugestões:

GitHub: @wysuporte

Email: wysuporte@gmail.com


