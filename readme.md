# 💸 expense-tracker-js

Uma calculadora de despesas pessoais simples, feita com **HTML, CSS e JavaScript puro**, que permite ao usuário registrar, visualizar e remover seus gastos. Os dados são armazenados no `localStorage`, garantindo persistência mesmo após fechar o navegador.

---

## 📌 Tópicos

- [📖 Sobre o Projeto](#-sobre-o-projeto)
- [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [⚙️ Como Executar](#️-como-executar)
- [🛠️ Funcionalidades](#️-funcionalidades)
- [🧠 Explicação do Código](#-explicação-do-código)
- [📄 Licença](#-licença)
- [🤝 Contribuindo](#-contribuindo)

---

## 📖 Sobre o Projeto

Este projeto permite que o usuário acompanhe suas despesas pessoais de forma simples. Ao adicionar uma descrição e um valor, o sistema soma automaticamente o total dos gastos e os exibe. Todos os dados são armazenados no `localStorage`, possibilitando o uso offline e a persistência dos dados.

---

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3 (inline)
- JavaScript (vanilla)
- Armazenamento local com `localStorage`

---

## ⚙️ Como Executar

1. **Clone o repositório:**

```bash
git clone https://github.com/rafaelmoreirax/expense-tracker-js.git
cd expense-tracker-js
```

2. **Abra o arquivo no navegador:**

```bash
start index.html
```

Ou apenas clique duas vezes no arquivo `index.html` para abrir no navegador.

---

## 🛠️ Funcionalidades

- [x] Adicionar nova despesa com descrição e valor
- [x] Remover uma despesa da lista
- [x] Cálculo automático do total de gastos
- [x] Armazenamento persistente com `localStorage`
- [ ] Filtro por data ou categoria (em planejamento)
- [ ] Exportar para CSV (em planejamento)

---

## 🧠 Explicação do Código

- `addExpense()`: adiciona uma nova despesa à lista.
- `removeExpense(index)`: remove a despesa pelo índice.
- `updateDisplay()`: atualiza o HTML com os dados armazenados e o total.
- Os dados são armazenados e recuperados do `localStorage` com `JSON.stringify()` e `JSON.parse()`.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🤝 Contribuindo

Contribuições são muito bem-vindas!

1. Faça um fork deste repositório.
2. Crie sua branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m 'feat: nova funcionalidade'`
4. Push para sua branch: `git push origin minha-feature`
5. Abra um Pull Request.

---

## 👤 Autor

Feito com 💰 por [Rafael Moreira](https://github.com/rafaelmoreirax)
