# 🎙️ Assistente de Voz Multi-Idiomas com Whisper e ChatGPT

Aplicação de **Inteligência Artificial** capaz de **traduzir textos falados ou escritos do Português para o Inglês (americano)**, utilizando **reconhecimento de voz**, **IA generativa** e **síntese de áudio**.

Projeto desenvolvido a partir do **Bootcamp de Gen IA & Dados – Bradesco (DIO)**, com foco em **aplicações práticas de IA**, automação e processamento de linguagem natural (NLP).

---

## 🚀 Visão Geral

Este assistente atua como um **tradutor inteligente**, indo além da tradução literal:

- 🎧 Reconhece **áudio** em português (Speech-to-Text)
- 🌎 Traduz para **Inglês Americano**
- 🧠 Explica **expressões e palavras**
- ✍️ Gera **exemplos reais de uso no cotidiano**
- 🔊 Converte a resposta novamente em **áudio (Text-to-Speech)**

Ideal para:
- Estudantes de inglês
- Desenvolvedores explorando IA generativa
- Demonstração de skills em **Python + IA**

---

## 🧠 Papel da IA (Prompt de Sistema)

A aplicação utiliza o seguinte papel para a IA:

```json
{
  "role": "developer",
  "content": "Assuma o papel de um Tradutor especialista, que ajuda o usuário a traduzir frases, expressões e palavras para o inglês americano. Quando a tradução for de uma expressão ou palavra, dê pelo menos 2 exemplos de aplicações dessas expressões ou palavra em frases do cotidiano em inglês."
}
```
Esse contexto garante **respostas didáticas, naturais e alinhadas ao uso real da língua inglesa.**

## 🛠️ Tecnologias Utilizadas

- Python
- OpenAI Whisper – Reconhecimento de fala (Speech-to-Text)
- ChatGPT (OpenAI API) – Tradução e geração contextual
- Text-to-Speech (TTS) – Geração de áudio
- IA Generativa & NLP
- APIs REST
