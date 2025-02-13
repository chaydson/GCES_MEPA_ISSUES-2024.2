# Sprint 5 - Documentação

## Informações Gerais

- **Início da Sprint:** 31/01/2025
- **Fim da Sprint:** 13/02/2025
- **Objetivo da Sprint:** Avançar com as contribuções do projeto

# Lista de Membros

| Nome                          | Usuário GitLab     |
| ----------------------------- | ------------------ |
| Ana Beatriz Massuh            | @AnaBeatrizMassuh  |
| Artur Jackson                 | @artur-jack        |
| Artur Rodrigues               | @ArturRSA19        |
| Beatriz Nascimento            | @Beatrizvn         |
| Delziron Braz                 | @DelzironBraz      |
| Gabriel Marcolino Rodrigues   | @GabrielMR360      |
| Guilherme de Sá Gonçalves     | @GuilhermeDSa1013  |
| João Barreto                  | @JoaoBarreto03     |
| Lucas Felipe Soares           | @lucasfs1007       |
| Lucas Spinosa                 | @LucasSpinosa      |
| Mateus de Almeida             | @Mateuszinnn       |
| Pedro Henrique R. de Carvalho | @PedroHenrique2077 |
| Silas Souza                   | @Silas-souza       |
| Chaydson Ferreira             | @chaydson          |
| Felipe Guimaraes              | @felipegf1         |

# Issues por Membro

| Nome                          | Issues                                                                                                                                                                                                                                                                                                         |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ana Beatriz Massuh            | [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190)                                                                                                                                                                                                                                                                                                             
| Artur Jackson                 | [#2](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/2)                                                                                                                                                                                                    |
| Artur Rodrigues               |                                                                                                                                                                                                                                                                                                                |
| Beatriz Nascimento            | [#415](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/415)                                                                                                                                                                                                                |
| Delziron Braz                 | [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190)                                                                                                                                                                                                                                                                                                               |
| Felipe Guimaraes              | [#4](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/4)                                                                                                                                                                                                    |
| Gabriel Marcolino Rodrigues   | [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190), [#4](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/4) e [#447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447) |
| Guilherme de Sá Gonçalves     | [#2](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/2)                                                                                                                                                                                                    |
| João Barreto                  |                                                                                                                                                                                                                                                                                                                |
| Lucas Felipe Soares           |                                                                                                                                                                                                                                                                                                                |
| Lucas Spinosa                 |                                                                                                                                                                                                                                                                                                                |
| Mateus de Almeida             | [#1](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/1)                                                                                                                                                                                                                                                                                                               |
| Pedro Henrique R. de Carvalho |                                                                                                                                                                                                                                                                                                                |
| Silas Souza                   |                                                                                                                                                                                                                                                                                                                |
| Chaydson Ferreira             | [#3](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/3)                                                                                                                                                                                                    |

## Participação dos Membros da Equipe durante a Sprint 5

### Ana Beatriz Massuh

- **Tarefas concluídas:** [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190)
- **Dificuldades encontradas:** Um dos principais desafios foi a realização de testes na REST API, pois as rotas exigem autenticação, mas o Gabriel e o Lucas trabalharam para viabilizar os testes e garantir que a integração funcione corretamente.
- **Relatos:** Durante esta sprint, atuei na implementação da integração com a API pública da Aneel. Trabalhei em conjunto com Lucas Felipe, Gabriel e Delziron para desenvolver um novo módulo exclusivo para essa integração, garantindo um endpoint dedicado às consultas na Aneel. Implementamos a integração com a rota disponibilizada pela Aneel, criamos um módulo específico para essa funcionalidade e realizamos ajustes nas variáveis de ambiente do projeto, adicionando a API da Aneel para suportar a nova funcionalidade. Com essa solução, agora é possível realizar consultas filtradas diretamente na Aneel, garantindo acesso contínuo e atualizado às informações.

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
- **Dificuldades encontradas:** minha maior dificuldade foi identificar as semelhanças e diferenças entre os dois casos de uso da tabela e tentar manter o componente reutilizável para ser flexível o suficiente para atender a ambos os casos, mas sem se tornar complexo demais.

### Chaydson Ferreira

- **Tarefas concluídas:** [#3](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/3)
- **Dificuldades encontradas:** realizar a validacao correta dos endpoints, impedindo o acesso e alteração indevida de dados.
- **Relatos:** os usuáriso sem permissão conseguiam visualizar, modificar e excluir contas de energia de outras instituições, evidenciando falha crítica no controle de acesso, mas foi resolvido.

### Delziron Braz

- **Tarefas concluídas:** [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190)
- **Dificuldades encontradas:** Realização de testes de RESTAPI
- **Relatos:** Durante o desenvolvimento da issue [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190), trabalhei em colaboração com Ana Beatriz, Lucas Felipe e Gabriel para implementar uma solução que permitisse a integração com a API pública da Aneel. A solução desenvolvida possibilita a realização de consultas diretamente na API da Aneel, utilizando filtros como parâmetros para refinar os resultados. Para viabilizar essa funcionalidade, adicionamos um novo endpoint ao projeto, dedicado exclusivamente a essa consulta. Com essa implementação, agora é possível acessar os dados da Aneel a qualquer momento, garantindo informações sempre atualizadas e diretamente da fonte.

### Felipe Guimaraes

- **Tarefas concluídas:** [#4](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/4)
- **Dificuldades encontradas:** a tentativa de correção de erros
- **Relatos:** foi feito o teste com as imagens recomendadas na issue porem as duas nao sao vesões estaveis e isso apresentou diversos problemas durante o build , devido a isso resolvemos testar versoes estaveis posteriores a atual, que seria a 3.12.9 e 3.13.2 porem ambas apresentaram um numero maior de vulnerabilidades do que a versão atual , entao devido a isso encerramos a issue sem fazer a alteração solicitada

### Gabriel Marcolino Rodrigues

- **Tarefas concluídas:** [#190](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/190), [#4](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/4) e [#447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447)
- **Dificuldades encontradas:** Na issue a dificuldade foi em alterar a versão do python para a que foi recomendada mas devido 
ser uma versão não estável estava falhando no build da imagem. Na issue 190 surgiram muitas dúvidas as quais foram sendo sanadas com o professor 
e também com o pessoal do projeto.
- **Relatos:** Nessa sprint atuei na issue de vulnerabilidade #4 com o Felipe, realizamos varios testes para alterar a versão da imagem do python,
mas chegamos na conclusão de não alterar a versão, já que as vulnerabilidades referentes as versões 3.12.9 e 3.13.2 do python não eram significativas a ponto de mudar
para alguma delas. Na issue #190 atuei em conjunto com o Lucas Felipe, Delziron e Ana Beatriz para realizar a importação das tarifas diretamente do site da ANEEL,
fizemos o consumo da API disponibilizada no site da ANEEL para retornar as tarifas. E por fim finalizei a issue #447 da sprint passada.


### Guilherme de Sá Gonçalves

- **Tarefas concluídas:** [#2](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/2) Parcialmente
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

- **Tarefas concluídas:** [#1](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mepa-contratos-vulnerabilidades/-/issues/1)
- **Dificuldades encontradas:** Nenhuma
- **Relatos:** Nessa sprints pariei com o Lucas Spinosa e o Silas Souza para resolvermos a vulnerabilidade de escalação de privilégios, corrigi o código do Lucas para passar no pipeline e adicionei mais algumas verificações nas requisições feitas diretamente na API, nesse contexto adicionei uma verificação para que admins não escalem seus privilégios para usuário super, porém podem editar seus usuários para serem admins ou usuários normais.

### Pedro Henrique Rodrigues de Carvalho

- **Tarefas concluídas:**
- **Dificuldades encontradas:**
- **Relatos:**

### Silas Souza

- **Tarefas concluídas:**
- **Dificuldades encontradas:**
- **Relatos:**
