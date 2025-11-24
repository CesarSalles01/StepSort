# 📊 StepSort

**StepSort** é uma aplicação web desenvolvida em **Flask** que demonstra algoritmos de ordenação passo a passo.  
O sistema permite que o usuário insira números manualmente ou gere listas aleatórias, e visualize como os algoritmos **Bubble Sort**, **Selection Sort** **Insertion Sort**  organizam os dados.

---

## 🎯 Objetivo

- Fornecer uma ferramenta interativa e educacional para estudantes de programação.  
- Demonstrar visualmente o funcionamento dos algoritmos de ordenação.  
- Possibilitar testes simples via endpoint `/health` para verificar se a aplicação está ativa.

---

## 🛠️ Stack Utilizada

- **Linguagem:** Python 3.x  
- **Framework Web:** Flask  
- **Frontend:** HTML5, CSS3 e JavaScript  
- **Templates:** Jinja2  

---

## 📂 Estrutura Inicial do Projeto
```bash
StepSort/
├── static/          <- arquivos CSS
├── templates/
│   ├── index.html   <- Página inicial
│   └── sorted.html  <- Página com resultado da ordenação
├── main.py          <- Código principal Flask
└── README.md
```

---

## 🚀 Como Rodar Localmente

### 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/StepSort.git
cd StepSort
```

### 2. Instalar dependências
```bash
pip install flask
```

### 3. Rodar o serviço Flask
```bash
python main.py
```

## A aplicação será executada em:
```bash
http://127.0.0.1:5000/
```

---

## 🧪 Testar endpoint /health

### Para verificar se o serviço está ativo, abra no navegador ou use curl:

```bash
http://127.0.0.1:5000/health	
```

### Resposta esperada
```bash
{"status": "ok"}
```

---

## 📷 Demonstração

<img width="1453" height="792" alt="StepSort  Menu_principal" src="https://github.com/user-attachments/assets/8d435deb-fd1a-4617-9032-71471aaf7dae" />

<img width="1297" height="903" alt="StepSort  Tela_Ordenação" src="https://github.com/user-attachments/assets/a83278d7-ebcc-4774-b3ea-065e6fff1c92" />

---

## 👥 Integrantes do Grupo

- **Ryan Juvenal Santos Oliveira**
- **Cesar Augusto Salles Marcondes**

---

## 📘 Disciplinas Envolvidas

- Computabilidade e Complexidade de Algoritmos
- Linguagens Formais e Autômatos

---

## 🏫 Informações Acadêmicas

- Universidade: **Universidade Braz Cubas**
- Curso: **Ciência da Computação**
- Semestre: 6º
- Período: Noite
- Professora orientadora: **Dra. Andréa Ono Sakai**

---
  
## 📄 Licença

MIT License — sinta-se à vontade para utilizar, estudar e adaptar este projeto.
