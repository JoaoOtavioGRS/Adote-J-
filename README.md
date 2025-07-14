# Adote-Ja
Plataforma social para facilitar a adoção de animais, projeto acadêmico TADS - UNIFIL

# Adote-Já 🐶🐱

Sistema web para facilitar a doação e adoção de cães e gatos, desenvolvido como atividade de extensão do curso de **Tecnologia em Análise e Desenvolvimento de Sistemas (TADS)** da **UNIFIL**.

## 📌 Descrição
O **Adote-Já** tem como objetivo ajudar a reduzir o número de animais abandonados, conectando pessoas que resgatam cães e gatos a adotantes em potencial de maneira rápida, prática e intuitiva.

## 🎯 Funcionalidades
- Cadastro de usuários;
- Login e logout;
- Cadastro e listagem de animais para adoção;
- Edição e exclusão de animais cadastrados;
- Marcar animal como adotado;
- Busca de animais com filtros (espécie, raça, cor, idade, vacinação, castração);
- Copiar telefone do responsável pelo animal diretamente para a área de transferência;
- Interface responsiva (celular, computador, tablet).

## 🚀 Tecnologias Utilizadas
- **Frontend:** HTML, CSS, Bootstrap;
- **Backend:** Python (Flask);
- **Banco de Dados:** SQLite;
- **Protótipo:** Figma;
- **Hospedagem:** AWS (planejada).

## 🖥️ Como Rodar o Projeto Localmente

### Pré-requisitos:
- Python 3.11 instalado
- Git instalado

### Passos:
```bash
# Clone o repositório
git clone [https://github.com/JoaoOtavioGRS/Adote-Ja]
# Acesse a pasta do projeto
cd adote-ja

# Crie um ambiente virtual (opcional mas recomendado)
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows

# Instale as dependências
pip install -r requirements.txt

# Rode a aplicação
python app.py
