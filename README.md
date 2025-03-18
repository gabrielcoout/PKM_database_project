# Pokémon Data Scraper

**Pokémon Data Scraper** é um projeto de **Web Scraping** que coleta informações detalhadas sobre todos os Pokémon e armazena os dados em um banco de dados relacional **SQLite**. O objetivo é criar um repositório organizado e pesquisável com dados como nomes, tipos, estatísticas e habilidades dos Pokémon.

---

## 📌 **Recursos**
- 🔍 Extração automatizada de dados de uma fonte confiável.
- 📦 Armazenamento estruturado em um banco de dados **SQLite**.
- 📊 Possibilidade de consultas e análises dos dados coletados.

---

## 📁 **Estrutura do Projeto**
```
📂 Pkm_database/
│── 📄 README.md         # Documentação do projeto
│── 📄 requirements.txt  # Dependências do projeto
│── 📂 data/             # Banco de dados e arquivos temporários
│   │── 📄 pokemon.db    # Banco de dados SQLite
│── 📂 src/              # Código-fonte principal
│   │── 📄 scraper.py    # Script para extrair os dados
│   │── 📄 database.py   # Script para armazenar os dados no SQLite
│   │── 📄 main.py       # Arquivo principal para execução
```

---

## 🔧 **Instalação e Configuração**
1. **Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/pokemon-data-scraper.git
   cd pokemon-data-scraper
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Linux/macOS
   venv\Scripts\activate     # No Windows
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 **Como Usar**
1. **Execute o scraper para coletar os dados:**
   ```bash
   python src/scraper.py
   ```
2. **Armazene os dados coletados no banco SQLite:**
   ```bash
   python src/database.py
   ```
3. **Execute consultas e análises:**
   ```bash
   python src/main.py
   ```

---

## 📌 **Futuras Melhorias**
- [ ] Adicionar interface gráfica para navegação nos dados.
- [ ] Criar API para acesso remoto ao banco de dados.
- [ ] Melhorar o tratamento de erros e logs.

