```markdown
# 🎓 Sistema de Gerenciamento de Turma (Turma AD6)

Este é um projeto em Python simples e interativo para gerenciar listas de professores e alunos utilizando estruturas de dados nativas (**Dicionários** e **Listas**).

---

## 🚀 Funcionalidades

O sistema permite realizar as seguintes operações através de funções interativas:

*   **📋 Visualizar Dados:** Exibe todos os professores e alunos cadastrados atualmente.
*   **➕ Adicionar Professor:** Insere um novo professor na lista.
*   **➕ Adicionar Aluno:** Insere um novo aluno na lista.
*   **❌ Remover Professor:** Permite selecionar e remover um professor baseado na sua posição na lista.
*   **❌ Remover Aluno:** Permite selecionar e remover um aluno baseado na sua posição na lista.

---

## 🛠️ Tecnologias Utilizadas

*   **Python 3**
*   **Dicionários (`dict`)** e **Listas (`list`)** para persistência temporária de dados na memória.

---

## 📖 Como Funciona?

### 1. Estrutura dos Dados
Os dados são estruturados em um dicionário onde cada chave mapeia para uma lista:

```python
turmaad6 = {
    "professores" : ["Felipe", "Luyz", "Priscila"],
    "aluno": ["Gabriel", "Alessandra", "Stefani"]
}
```

### 2. Funções Disponíveis
*   `ver_dados()`
*   `add_prof()`
*   `add_aluno()`
*   `remover_professor()`
*   `remover_aluno()`

---

## 💻 Exemplo de Execução

Para iniciar uma ação, basta chamar a função desejada em uma célula de código:

```python
# Para remover um professor e atualizar a lista:
remover_professor()
```
```
