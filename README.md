### Exercício Prático de Git e GitHub: Projeto Colaborativo de Site

**Objetivo:** Aplicar os conceitos básicos de Git e GitHub em um ambiente colaborativo assíncrono. Os alunos irão praticar clonagem de repositórios, criação de branches, commits, push, pull requests e resolução de conflitos.

### Descrição do Exercício

Os alunos irão colaborar para criar um site simples. Cada aluno será responsável por uma parte específica do projeto.

#### Passo a Passo
1. **Instalar Git local e criar uma conta no GitHub:**
   - Realizar o download do Git e instalar na sua máquina local
   - Criar o seu usuário no Github e enviar ao professor para adicionar ao repositório

2. **Clonagem do Repositório:**
   - Cada aluno deve clonar o repositório na sua máquina local:
     ```bash
     git clone https://github.com/pabloermida/atitus.git
     ```
     
3. **Criação de Branches:**
   - Cada aluno deve criar uma nova branch a partir da `main` para trabalhar na sua tarefa:
     ```bash
     git checkout -b aluno-nome-secao
     ```

4. **Edição e Commit:**
   - Cada aluno deve adicionar uma nova seção ao `index.html` e estilizar a seção no `style.css`. Por exemplo:
     ```html
     <!-- Adicionar ao index.html -->
     <section id="nome-secao">
         <h2>Seção Nome</h2>
         <p>Conteúdo da seção adicionada pelo aluno.</p>
     </section>
     ```
     ```css
     /* Adicionar ao style.css */
     #nome-secao {
         padding: 1em;
         background-color: #ffffff;
         margin: 1em 0;
     }
     ```
   - Fazer commit das mudanças:
     ```bash
     git add index.html style.css
     git commit -m "Adiciona seção Nome"
     ```

5. **Push para o Repositório Remoto:**
   - Enviar a branch com as mudanças para o GitHub:
     ```bash
     git push origin aluno-nome-secao
     ```

6. **Pull Request:**
   - Cada aluno deve criar um Pull Request (PR) da sua branch para a `main` no GitHub.
   - Os alunos devem revisar os PRs uns dos outros e sugerir melhorias, se necessário.

7. **Merge dos Pull Requests:**
   - Após a revisão, os PRs podem ser mesclados na `main`.
   - Instruir os alunos sobre como resolver possíveis conflitos que surgirem durante o merge.

8. **Atualização do Repositório Local:**
   - Após todos os PRs serem mesclados, cada aluno deve atualizar o seu repositório local:
     ```bash
     git checkout main
     git pull origin main
     ```

9. **Tarefa Final:**
    - Cada aluno deve adicionar seu nome e uma breve descrição da sua contribuição no arquivo `contribuidores.txt` na raiz do projeto.
    - Criar uma nova branch `contribuidor-nome`, adicionar o arquivo, fazer commit e enviar o PR para a `main`.

### Pontos de Aprendizado

- **Clonagem de Repositórios:** Trazer um repositório remoto para o ambiente local.
- **Branches:** Trabalhar com branches para isolar mudanças.
- **Commits:** Registrar mudanças no histórico do projeto.
- **Pull Requests:** Colaborar com outros desenvolvedores e revisar código.
- **Merge e Resolução de Conflitos:** Integrar mudanças de diferentes contribuintes e resolver conflitos.

Esse exercício ajudará a turma a praticar os conceitos de Git e GitHub em um ambiente colaborativo realista. Boa sorte!
