### Exercício Prático de Git e GitHub: Projeto Colaborativo de Site

**Objetivo:** Aplicar os conceitos básicos de Git e GitHub em um ambiente colaborativo assíncrono. Os alunos irão praticar clonagem de repositórios, criação de branches, commits, push, pull requests e resolução de conflitos.

### Descrição do Exercício

Os alunos irão colaborar para criar um site simples. Cada aluno será responsável por uma parte específica do projeto.

#### Passo a Passo
1. **Instalar Git local e criar uma conta no GitHub:**
   - Realizar o download 

2. **Clonagem do Repositório:**
   - Cada aluno deve clonar o repositório na sua máquina local:
     ```bash
     (git clone https://github.com/pabloermida/atitus.git)
     ```

3. **Distribuição de Tarefas:**
   - Divida as tarefas entre os alunos, por exemplo:
     - Aluno 1: Adicionar seção "Sobre"
     - Aluno 2: Adicionar seção "Serviços"
     - Aluno 3: Adicionar seção "Contato"
     - Aluno 4: Estilizar o header
     - Aluno 5: Estilizar o main
     - Aluno 6: Estilizar o footer
     - Aluno 7: Adicionar funcionalidade de formulário em "Contato"
     - Aluno 8: Adicionar script para navegação
     - Aluno 9: Adicionar script para animações
     - Aluno 10: Melhorar a responsividade do site

4. **Criação de Branches:**
   - Cada aluno deve criar uma nova branch a partir da `main` para trabalhar na sua tarefa:
     ```bash
     git checkout -b aluno-nome-tarefa
     ```

5. **Edição e Commit:**
   - Cada aluno deve fazer as mudanças necessárias na sua branch e fazer commits:
     ```bash
     git add .
     git commit -m "Adiciona seção Sobre"
     ```

6. **Push para o Repositório Remoto:**
   - Enviar a branch com as mudanças para o GitHub:
     ```bash
     git push origin aluno-nome-tarefa
     ```

7. **Pull Request:**
   - Cada aluno deve criar um Pull Request (PR) da sua branch para a `main` no GitHub.
   - Os alunos devem revisar os PRs uns dos outros e sugerir melhorias, se necessário.

8. **Merge dos Pull Requests:**
   - Após a revisão, os PRs podem ser mesclados na `main`.
   - Resolver possíveis conflitos que surgirem durante o merge.

9. **Atualização do Repositório Local:**
   - Após todos os PRs serem mesclados, cada aluno deve atualizar o seu repositório local:
     ```bash
     git checkout main
     git pull origin main
     ```

10. **Tarefa Final:**
    - Cada aluno deve adicionar seu nome e uma breve descrição da sua contribuição no arquivo `contribuidores.txt` na raiz do projeto.
    - Criar uma nova branch `contribuidor-nome`, adicionar o arquivo, fazer commit e enviar o PR para a `main`.

### Pontos de Aprendizado

- **Clonagem de Repositórios:** Trazer um repositório remoto para o ambiente local.
- **Branches:** Trabalhar com branches para isolar mudanças.
- **Commits:** Registrar mudanças no histórico do projeto.
- **Pull Requests:** Colaborar com outros desenvolvedores e revisar código.
- **Merge e Resolução de Conflitos:** Integrar mudanças de diferentes contribuintes e resolver conflitos.

Esse exercício ajudará a turma a praticar os conceitos de Git e GitHub em um ambiente colaborativo realista. Boa sorte!
