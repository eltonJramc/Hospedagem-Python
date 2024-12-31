# 🏨 Análise de Dados de Hospedagem com Python

Este projeto tem como objetivo transformar e limpar um conjunto de dados sobre hospedagens para análises futuras. 
Utilizei **Python** e as bibliotecas **Pandas** e **NumPy** para realizar a manipulação e normalização dos dados.

---

## 📂 Estrutura do Projeto

- `dados_hospedagem.json`: Conjunto de dados de hospedagem utilizado no projeto.
- `main.py`: Código principal para transformação e análise dos dados.

---

## 🛠️ Funcionalidades

1. **Normalização de Estruturas JSON**:
   - Utilização de `pd.json_normalize` para lidar com dados aninhados.
   - Explosão de colunas para facilitar a manipulação.

2. **Conversão de Tipos e Limpeza de Dados**:
   - Conversão de colunas para os tipos apropriados (`int`, `float` e `datetime`).
   - Limpeza de textos com expressões regulares e padronização.

3. **Tokenização de Textos**:
   - Separação e limpeza de descrições para análises textuais futuras.

4. **Análise Temporal**:
   - Agrupamento por mês para avaliar a disponibilidade de vagas.

---

## 💡 Principais Tecnologias

- **Python**
- **Pandas**
- **NumPy**
- **Google Colab (Jupyter Notbook)**

---

## 📊 Exemplos de Saída

### Disponibilidade de Vagas por Mês:
```plaintext
2024-01: 150 vagas
2024-02: 130 vagas
...
