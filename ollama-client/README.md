# 🧠 Cliente Ollama - Modelo phi3:mini

Aplicação simples em Python que se conecta à API do Ollama e envia prompts ao modelo `phi3:mini`. O usuário digita uma mensagem, a aplicação envia para a IA e exibe a resposta no terminal.

**Este projeto foi desenvolvido por Hailton Neto e Vinicius Macedo.**

---

## 📦 Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/hailtonneto/ollama-client.git
   cd ollama-client
   ```
2. **Crie um ambiente virtual (opcional, mas recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    venv\Scripts\activate     # Windows
    ```
3. **Instale as dependências:**
    - Forma direta:
        ```bash
        pip install requests
        ```
    - Ou usando o arquivo requirements.txt:
        ```bash
        pip install -r requirements.txt
        ```

---

## 🚀 Como usar

1. **Execute o script:**
    ```bash
    python main.py
    ```
2. **Digite seu prompt no terminal e veja a resposta da IA.**
3. **Para sair, digite `sair`.**

---

## 🔧 Configurações

- URL da API: http://ollama.eastus.cloudapp.azure.com:11434/
- Modelo usado: phi3:mini
- Formato da requisição:
    ```bash
    {
    "model": "phi3:mini",
    "prompt": "sua mensagem aqui",
    "stream": false
    }
    ```

---

## 📁 Estrutura do Projeto

```bash
ollama-client/
├── main.py
├── requirements.txt
└── README.md
```

---

## 📄 Exemplo de uso

```bash
🧠 Cliente Ollama - Modelo phi3:mini

Digite seu prompt (ou 'sair' para encerrar): Qual a capital da França?

💬 Resposta da IA:
A capital da França é Paris.
```

---

## 📜 Licença

```bash
MIT License

Copyright (c) 2025 Hailton Neto e Vinícius Macêdo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```