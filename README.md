# 🍽️ Sabor Express

Sistema de gerenciamento de restaurantes via terminal (CLI), desenvolvido em Python.

O projeto permite cadastrar, listar e alternar o estado de restaurantes de forma simples, utilizando uma interface interativa no terminal.

---

## 🚀 Funcionalidades

- ✅ Cadastro de novos restaurantes
- 📋 Listagem de restaurantes cadastrados
- 🔄 Alternar estado do restaurante (ativado/desativado)
- 🧭 Menu interativo no terminal
- 🎨 Interface com títulos e informações formatadas

---

## 🛠️ Tecnologias utilizadas

- Python 3
- Biblioteca padrão:
  - `os`

---

## 📂 Estrutura do projeto

```bash
sabor-express/
│
├── app.py
└── README.md
```

---

# ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/VMurtis/restaurante-python-terminal.git
```

### 2. Acesse a pasta do projeto

```bash
cd restaurante-python-terminal
```

### 3. Execute o programa

```bash
python app.py
```

---

# 💡 Como usar

Ao executar o sistema, será exibido um menu interativo:

```text
1. Cadastrar restaurante
2. Listar restaurantes
3. Alternar estado do restaurante
4. Sair
```

### Cadastro de restaurante

O usuário informa:

- Nome do restaurante
- Categoria

O sistema cria um novo restaurante com status inicial como desativado.

---

# 📊 Estrutura dos dados

Os restaurantes são armazenados utilizando uma lista de dicionários:

```python
{
    'nome': 'Pizza Suprema',
    'categoria': 'Pizza',
    'ativo': True
}
```

Cada restaurante possui:

| Campo | Descrição |
|---|---|
| nome | Nome do restaurante |
| categoria | Tipo de culinária |
| ativo | Status do restaurante |

---

# 🧠 Conceitos aplicados

- Organização de código com funções
- Uso de listas e dicionários
- Manipulação de dados em Python
- Tratamento de erros com `try/except`
- Interface em terminal (CLI)
- Boas práticas com `main()`
- Uso de docstrings para documentação de funções

---

# 📈 Melhorias futuras

- 💾 Persistência de dados utilizando JSON ou banco de dados
- 🔍 Busca de restaurantes
- ✏️ Edição de informações
- 🧪 Implementação de testes automatizados
- 🌐 Criar versão web utilizando Flask
