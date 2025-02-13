# Sprint 5 - Documentação

## Informações Gerais
- **Início da Sprint:** 31/01/2025
- **Fim da Sprint:** 13/02/2025
- **Objetivo da Sprint:** Avançar com as contribuções do projeto 

# Lista de Membros

| Nome                              | Usuário   GitLab    |
|-----------------------------------|---------------------|
| Ana Beatriz Massuh                | @AnaBeatrizMassuh   |
| Artur Jackson                     | @artur-jack         |
| Artur Rodrigues                   | @ArturRSA19         |
| Beatriz Nascimento                | @Beatrizvn          |
| Delziron Braz                     | @DelzironBraz       |
| Gabriel Marcolino Rodrigues       | @GabrielMR360       |
| Guilherme de Sá Gonçalves         | @GuilhermeDSa1013   |
| João Barreto                      | @JoaoBarreto03      |
| Lucas Felipe Soares               | @lucasfs1007        |
| Lucas Spinosa                     | @LucasSpinosa       |
| Mateus de Almeida                 | @Mateuszinnn        |
| Pedro Henrique R. de Carvalho     | @PedroHenrique2077  |
| Silas Souza                       | @Silas-souza        |
| Chaydson Ferreira                 | @chaydson           |
| Felipe Guimaraes                  | @felipegf1          |


# Issues por Membro

| Nome                              | Issues                   |
|-----------------------------------|--------------------------|
| Ana Beatriz Massuh                |                          |
| Artur Jackson                     |  [#2](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/2)                        |
| Artur Rodrigues                   |                          |
| Beatriz Nascimento                |  [#415](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/415)                       |
| Delziron Braz                     |                          |
| Felipe Guimaraes                  |  [#4](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/4)                       |
| Gabriel Marcolino Rodrigues       |                          |
| Guilherme de Sá Gonçalves         |  [#2](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/2)                         |
| João Barreto                      |                          |
| Lucas Felipe Soares               |                          |
| Lucas Spinosa                     |                          |
| Mateus de Almeida                 |                          |
| Pedro Henrique R. de Carvalho     |                          |
| Silas Souza                       |                          |
| Chaydson Ferreira                 |  [#3](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/3)                     |

## Participação dos Membros da Equipe durante a Sprint 5

### Ana Beatriz Massuh
- **Tarefas concluídas:**
- **Dificuldades encontradas:** 
- **Relatos:** 

### Artur Jackson
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:**

  
### Artur Rodrigues
- **Tarefas concluídas:**
- **Dificuldades encontradas:** 
- **Relatos:** 

### Beatriz Nascimento
- **Tarefas concluídas:** [#415](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/415)
- **Relatos:** Componentizar tabela de faturas da aba Faturas para reutilizar na prévia de Importar CSV. Realizar a implementação de um único componente de tabela que possa ser reutilizado pelas duas telas.
- **Dificuldades encontradas:**  minha maior dificuldade foi identificar as semelhanças e diferenças entre os dois casos de uso da tabela e tentar manter o componente reutilizável para ser flexível o suficiente para atender a ambos os casos, mas sem se tornar complexo demais.

### Chaydson Ferreira
- **Tarefas concluídas:** [#3](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/3) 
- **Dificuldades encontradas:**  realizar a validacao correta dos endpoints, impedindo o acesso e alteração indevida de dados.
- **Relatos:** os usuáriso sem permissão conseguiam visualizar, modificar e excluir contas de energia de outras instituições, evidenciando falha crítica no controle de acesso, mas foi resolvido.

### Delziron Braz
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 

### Felipe Guimaraes 
- **Tarefas concluídas:** [#4](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/4) 
- **Dificuldades encontradas:** a tentativa de correção de erros 
- **Relatos:** foi feito o teste com as imagens recomendadas na issue porem as duas nao sao vesões estaveis e isso apresentou diversos problemas durante o build , devido a isso resolvemos testar versoes estaveis posteriores a atual, que seria a 3.12.9 e 3.13.2 porem ambas apresentaram um numero maior de vulnerabilidades do que a versão atual , entao devido a isso encerramos a issue sem fazer a alteração solicitada

### Gabriel Marcolino Rodrigues
- **Tarefas concluídas:** 
- **Dificuldades encontradas:**
- **Relatos:** 

### Guilherme de Sá Gonçalves
- **Tarefas concluídas:**  [#2](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/2)  Parcialmente
- **Dificuldades encontradas:** Migrações nas tableas do banco
- **Relatos:** Pareei junto do Artur Jackson nessa issue, e basicamente era pra trocar o id sequencial dos usuários para um UUID, o que conseguimos fazer na tabela de usuários, com uma migration, o problema surgiu nas outras tabelas, nas quais não conseguimos ainda mudar as referências de chaves externas de bigint para o novo tipo UUID, tentamos já 3 possibilidades, migrations, editar as models e derrubar o banco e criar de novo do zero. Não chegamos a tentar de fato a última alternativa, pois não queríamos excluir todas as migrations anteriores para fazer novas. Tentaremos com a ajuda de algum monitor ou outros membros para finalizar essa tarefa o quanto antes, para estar merjada até a apresentação final.

### João Barreto
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 

### Lucas Felipe Soares
- **Tarefas concluídas:**
- **Dificuldades encontradas:** 
- **Relatos:**
  
### Lucas Spinosa
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 

### Mateus de Almeida
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:**
### Pedro Henrique Rodrigues de Carvalho
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:**

### Silas Souza
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 
