# J.A.R.V.I.S.

**Justificador Automático para Resumo e Validação de Informações na Superfície**  
Um assistente de leitura de tela com OCR + IA generativa (Gemini) que interpreta automaticamente o conteúdo visível no seu monitor e responde perguntas ou gera resumos, dependendo do contexto.

![Demonstração](demo.gif)

---

## ✨ Funcionalidades

- 📸 Captura o conteúdo visível na tela do usuário
- 🧠 Usa OCR (Tesseract) para extrair texto da imagem
- 🤖 Interage com o modelo Gemini para interpretar ou responder ao conteúdo
- 🧼 Resumo inteligente quando não há pergunta detectada
- 💾 Histórico salvo automaticamente durante o uso
- 🔒 Histórico é apagado ao encerrar o app
- ⚡ Atalho CMD+L para leitura instantânea
- 💻 Interface gráfica simples com Tkinter

---

## 🚀 Como executar

1. Clone este repositório:

```bash
git clone https://github.com/seuusuario/J.A.R.V.I.S.git
cd J.A.R.V.I.S
```

2. Instale os requisitos:

```bash
pip install -r requirements.txt
```

3. Adicione sua chave da API Gemini em `config.py`:

```python
# config.py
GEMINI_API_KEY = "sua-chave-aqui"
```

4. Execute:

```bash
python main.py
```

---

## 🧪 Tecnologias utilizadas

- Python 3.13
- OCR: pytesseract + PIL
- GUI: Tkinter
- AI: Gemini 1.5 Flash API (Google)
- Screenshot: PyAutoGUI
- Clipboard: pyperclip

---

## 📁 Estrutura

```
J.A.R.V.I.S/
├── main.py               # Código principal do app
├── config.py             # API Key da Gemini
├── requirements.txt      # Dependências do projeto
├── .gitignore            # Ignora cache/histórico
├── historico/            # Arquivos gerados durante o uso
├── demo.gif              # Demonstração visual (GIF)
```

---

## 👤 Autor

Desenvolvido por **Willian Barbosa**  
🔗 [LinkedIn](https://www.linkedin.com/in/seuperfil)  
📬 willianandrade@example.com

---

## 📄 Licença

Este projeto está sob a licença MIT.
