# Sprint 3 - Documentação

## Informações Gerais
- **Início da Sprint:** 20/01/2025
- **Fim da Sprint:** 30/01/2025
- **Objetivo da Sprint:** Avançar com as contribuções do projeto 

# Lista de Membros

| Nome                              | Usuário   GitLab          |
|-----------------------------------|---------------------|
| Ana Beatriz Massuh                | @AnaBeatrizMassuh   |
| Artur Jackson                     | @artur-jack         |
| Artur Rodrigues                   | @ArturRSA19         |
| Beatriz Nascimento                | @Beatrizvn          |
| Delziron Braz                     | @DelzironBraz       |
| Gabriel Marcolino Rodrigues        | @GabrielMR360       |
| Guilherme de Sá Gonçalves         | @GuilhermeDSa1013   |
| João Barreto                      | @JoaoBarreto03      |
| Lucas Felipe Soares               | @lucasfs1007        |
| Lucas Spinosa                     | @LucasSpinosa       |
| Mateus de Almeida                 | @Mateuszinnn        |
| Pedro Henrique Rodrigues de Carvalho | @PedroHenrique2077 |
| Silas Souza                       | @Silas-souza        |
| Chaydson Ferreira                 | @chaydson           |
| Felipe Guimaraes                        | @felipegf1          |


# Issues por Membro

| Nome                              | Issues                   |
|-----------------------------------|--------------------------|
| Ana Beatriz Massuh                |      |
| Artur Jackson                     | [#444](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/444)             |
| Artur Rodrigues                   |                   |
| Beatriz Nascimento                |  Correções na issue [#387](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/387) da sprint 2  |
| Delziron Braz                     |                       |
| Felipe Guimaraes                  |                          |
| Gabriel Marcolino Rodrigues       | [#447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447)                       |
| Guilherme de Sá Gonçalves         | [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                     |
| João Barreto                      |                         |
| Lucas Felipe Soares               | [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408)                         |
| Lucas Spinosa                     |       |
| Mateus de Almeida                 |                       |
| Pedro Henrique Rodrigues de Carvalho |                     |
| Silas Souza                       |                          |
| Chaydson Ferreira                 |[#452](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/452)                        |

## Participação dos Membros da Equipe durante a Sprint 3

### Ana Beatriz Massuh
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 

### Artur Jackson
- **Tarefas concluídas:** [#444](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/444) 
- **Dificuldades encontradas:** Achar o commit onde foi removido o datePicker da edição da fatura e corrigir.
- **Relatos:** Nessa sprint eu finalizei a issue 444. Já tinha pego essa issue em sprints anteriores, mas estava com problemas. Inicialmente era somente para corrigir a cor de um mês desabilitado selecionado na data da fatura para onPrimary, para ficar mais visível. Só que com as alterações vindas da upstream, percebi que o dropdown de seleção da data do mês de referencia foi removido tanto da página de edição quanto lançamento da fatura. Após fazer alguns comentários na issue me pediram para recolocar o datePicker novamente somente na página de edição da fatura. Então recoloquei novamente na página de edição e corrigi o que issue queria inicialmente, que era a cor para onPrimary.

### Artur Rodrigues
- **Tarefas concluídas:** 
- **Dificuldades encontradas:**
- **Relatos:** 

### Beatriz Nascimento
- **Tarefas concluídas:**  Realizei mudanças solicitadas na issue 387 feita na sprint 2
- **Relatos:**  Os ajustes foram esses: CurrentDate repetido no set, mudar para setOneDayAfterCurrentDate, retirar comentario em RenewContract e usar um Max entre os dois elementos, e não um OR, usando o OR com datas, sempre o primeiro elemento é o retornado, caso não seja undefined.

### Chaydson Ferreira
- **Tarefas concluídas:** Implementação de testes unitários para os componentes AverageConsumptionPlot, BaseCostComparisonCard, BaseCostComparisonPlot, CurrentBaseCostPlot, DetailedAnalysisHeader, MeasuredConsumptionPlot, MeasuredDemandPlot, RecommendationCard e Revisão dos MRs da Sprint 3.
- **Dificuldades encontradas:** Ajustes nas configurações do ambiente de testes foram necessários para garantir a compatibilidade total com a versão mais recente do framework utilizado.
- **Relatos:** A abordagem de escrever os testes de forma modular permitiu identificar rapidamente qualquer discrepância ou falha durante a execução dos testes.

### Delziron Braz
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 

### Felipe Guimaraes 
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** Devido a questões pessoais e de tempo nao consegui chegar a finalizar uma issue nessa sprint e foquei em estudar e concluir etapas do trabalho individual 

### Gabriel Marcolino Rodrigues
- **Tarefas concluídas:** 
- **Dificuldades encontradas:**
- **Relatos:** Nessa sprint estava pareando com o Silas na issue [447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447), foi feito os ajustes solicitados nas telas de criar e editar unidade consumidora. Porém o ajuste na tela de renovar o contrato não foi feito pois surgiu uma dúvida a qual estou esperando o Rodrigo responder para fianlizar os ajustes solicitados.

### Guilherme de Sá Gonçalves
- **Tarefas concluídas:** [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)
- **Dificuldades encontradas:** Foi minha primeira vez fazendo testes de componentes no projeto, então demorei um pouco para aprender, e fui vendo os exemplo feitos anteriormente.
- **Relatos:** Basicamente fiz mais testes nessa sprint, incrementei um arquivo de testes de validação, o form-validation.test.js, e adicionei testes para mais dois componentes, Footer e FilterButtons. Também ajudei no mapeamento das alterações necessárias ainda do MR da Sprint 2, conseguindo fazer uma alterçaõ mais simples no que dizia respeito a issue [#427](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/427).

### João Barreto
- **Tarefas concluídas:**

### Lucas Felipe Soares
- **Tarefas concluídas:** [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408).  
- **Dificuldades encontradas:** Não sabia como resolver os problemas de pipeline da issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e dependi bastante do suporte do Flávio para lidar. Estive com um pouco menos de tempo por problemas pessoais e outras disciplinas então foi uma sprint mais pesada que as demais. 
- **Relatos:** A issue [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408), tive de fazer algumas correções passadas pela Adne no MR da sprint 1. Já os problemas de pipeline da issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) consegui resolver e aproveitei para aumentar mais a cobertura de testes, sobretudo do módulo de universidades que havia trabalhado menos na sprint passada.

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
