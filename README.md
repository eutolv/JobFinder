# JobFinder
Ferramenta em Python para coletar vagas remotas, júnior, internship ou entry-level na área de IT Support / Help Desk / NOC / SOC automaticamente.

```markdown
# JobFinder – IT Support Junior & Entry-Level Scraper

Ferramenta em Python que coleta automaticamente vagas públicas de **IT Support, Help Desk, NOC, SOC Tier 1 e Sysadmin Junior**, filtrando apenas oportunidades **remotas**, **júnior**, **entry-level** ou **intern**.

Gera um arquivo **DOCX** com lista organizada e links clicáveis para cada vaga encontrada.

---

## 🚀 Funcionalidades

- Busca automática em sites públicos.
- Filtragem por:
  - Nível: *junior, entry, intern, trainee, level 1, tier 1*
  - Área: *IT Support, Help Desk, NOC, SOC, Sysadmin Jr*
- Hiperlinks clicáveis exportados em **DOCX**.
- Fonte configurada (Garamond 10) e lista com marcadores.
- Zero login, zero scraping agressivo — apenas páginas públicas.
- Compatível com WSL, Linux, macOS e Windows.

---

## 📂 Estrutura do Projeto

```

.
├── jobfinder_it_support.py
├── requirements.txt
├── README.md
└── LICENSE

````

---

## ✅ Instalação

### 1. Criar ambiente virtual
```bash
python3 -m venv venv
source venv/bin/activate
````

### 2. Instalar dependências

```bash
pip install -r requirements.txt
```

---

## ▶️ Uso

```bash
python3 jobfinder_it_support.py
```

O script irá gerar um arquivo como:

```
vagas_encontradas_2025-11-07_16-16-43.docx
```

Com uma lista de vagas, cada uma com:

* título da vaga
* nível
* link direto para candidatura

---

## 🛠 Tecnologias

* **Python 3**
* `requests`
* `beautifulsoup4`
* `python-docx`
* `re` para filtros
* Scraping leve, apenas páginas públicas

---

## 🔍 Notas sobre Scraping Ético

Este projeto:

* **não acessa páginas privadas**
* **não faz login**
* **não usa APIs privadas**
* **não viola ToS**
* consulta apenas resultados públicos e permitidos.

---

## 📄 requirements.txt

```
requests
beautifulsoup4
python-docx
urllib3
```

---

## 📜 LICENSE (MIT)

```
MIT License

Copyright (c) 2025

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

---

## 🤝 Contribuindo

Pull requests são bem-vindos!
Sugestões de novos filtros, sites ou melhorias são apreciadas.

---

## ⭐ Créditos

Criado para facilitar a vida de quem está começando em **Infra / Suporte / Segurança** e precisa encontrar vagas **reais**, **filtradas** e **acessíveis**.

```
```
