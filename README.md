# 🎙️ Multi-Language Audio Transcriber & Insight Extractor

> **AI Automation Tool:** Aplicação hands-on para transcrição automática de voz em múltiplos idiomas e estruturação de texto utilizando o modelo OpenAI Whisper.

---

## 🎯 Problema de Negócio

Em rotinas de gestão de produtos e projetos, a captura manual de notas de reuniões, entrevistas com usuários e alinhamentos operacionais consome tempo e gera perda de contexto. 

Esta solução foi desenvolvida para **automatizar o fluxo de ingestão de áudio e conversão em texto legível**, reduzindo o esforço manual e criando a base para pipelines de extração automática de atas, requisitos e insights de negócios.

---

## 💡 A Solução

Um pipeline integrado que captura áudios diretamente via interface web, processa os arquivos de som e aplica modelos avançados de Processamento de Linguagem Natural (NLP) para transcrição multiidioma de alta precisão.

### Principais Funcionalidades
- **Captura In-Browser:** Interface responsiva em JavaScript para gravação direta pelo microfone.
- **Processamento de Áudio:** Conversão e padronização automática para o formato `.wav`.
- **Transcrição Multiidioma:** Suporte nativo a dezenas de idiomas com detecção automática de fala via OpenAI Whisper.
- **Tratamento de Exceções:** Pipeline resiliente preparado para falhas de gravação ou ruídos de áudio.

---

## 🏗️ Arquitetura do Fluxo
[ Usuário / Microfone ]
│
▼  (JavaScript MediaRecorder API)
[ Captura de Áudio In-Browser ]
│
▼  (Exportação .wav)
[ Pipeline Python ]
│
▼  (Processamento de NLP)
[ Modelo OpenAI Whisper ]
│
▼
[ Texto Transcrito & Pronto para Ingestão ]

---

## 🛠️ Tech Stack & Ferramentas

- **Linguagens:** Python, JavaScript
- **Modelo de IA / NLP:** OpenAI Whisper
- **Interface / Execução:** Google Colab / MediaRecorder API
- **Formatos Manipulados:** Áudio (`.wav`), Texto não estruturado

---

## 🚀 Como Executar o Projeto

Você pode testar a solução interativa diretamente no ambiente do Google Colab:

1. Acesse o notebook do projeto: [🔗 Abrir no Google Colab](https://colab.research.google.com/drive/1LrT0TQ0_K4gg746XwgkpekzpSKmSRQ0x?usp=drive_link)
2. Execute as células de configuração técnica.
3. Conceda permissão de microfone e grave seu áudio em tempo real.
4. Visualize a transcrição processada ao final da execução.

---

## 🔮 Próximos Passos (Product Roadmap)

- [ ] Integrar com a API de LLMs (ex: GPT-4o) para gerar resumos executivos e *action items* automaticamente após a transcrição.
- [ ] Criar interface web dedicada utilizando **Streamlit**.
- [ ] Adicionar suporte a upload de arquivos de áudio longos (ex: MP3/M4A de reuniões gravadas no Zoom/Teams).

---

<details>
<summary>ℹ️ Contexto do Projeto</summary>

Projeto desenvolvido originalmente como protótipo prático durante o Bootcamp *GenAI & Dados* (parceria DIO + Bradesco), evoluído para demonstrar a aplicação de ferramentas de áudio e IA no suporte a processos corporativos e de produto.
</details>
