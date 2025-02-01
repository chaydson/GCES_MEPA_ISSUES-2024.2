# Sprint 4 - Documentação

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
| Ana Beatriz Massuh                | [#220](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/220) e teste unitário     |
| Artur Jackson                     | [#444](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/444)             |
| Artur Rodrigues                   | [#151](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/151) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260)                  |
| Beatriz Nascimento                |  Correções na issue [#387](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/387) da sprint 2  |
| Delziron Braz                     | [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e .[419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419)                      |
| Felipe Guimaraes                  |                          |
| Gabriel Marcolino Rodrigues       | [#447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447)                       |
| Guilherme de Sá Gonçalves         | [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                     |
| João Barreto                      | [#151](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/151) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260)                       |
| Lucas Felipe Soares               | [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408)                         |
| Lucas Spinosa                     |       |
| Mateus de Almeida                 | [#445](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/445)                      |
| Pedro Henrique Rodrigues de Carvalho |  [#452](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/452)                   |
| Silas Souza                       | [#447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447) e [#448](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447)                   |
| Chaydson Ferreira                 |[#452](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/452)                        |

## Participação dos Membros da Equipe durante a Sprint 3

### Ana Beatriz Massuh
- **Tarefas concluídas:** [#220](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/220) e testes unitários para a função getSubgroupsText
- **Dificuldades encontradas:** 
- **Relatos:** Desenvolvi testes utilizando Jest para validar se a função retorna a string corretamente formatada.
Implementei esse teste para verificar o comportamento da função quando recebe um array incompleto, garantindo que um erro seja lançado. Além disso  refatorei o sistema de envio de emails da aplicação, substituindo a implementação baseada em smtplib por django.core.mail. Essa mudança visa melhorar a manutenibilidade do código, facilitar a configuração em diferentes ambientes e permitir a integração com o sistema de templates HTML do Django (Atualizei o settings.py para utilizar as configurações nativas do Django para envio de emails, garantindo que todas as credenciais sejam carregadas corretamente via variáveis de ambiente.Substituí o uso de smtplib pelo backend de email do Django, utilizando send_mail para simplificar o envio e permitir a renderização de emails em HTML.Ajustei o arquivo send_email.py para usar as novas configurações, removendo código desnecessário e melhorando a clareza da implementação.Configurei o Mailpit como servidor SMTP no ambiente de desenvolvimento, permitindo a captura e visualização de emails de teste.).


### Artur Jackson
- **Tarefas concluídas:** [#444](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/444) 
- **Dificuldades encontradas:** Achar o commit onde foi removido o datePicker da edição da fatura e corrigir.
- **Relatos:** Nessa sprint eu finalizei a issue 444. Já tinha pego essa issue em sprints anteriores, mas estava com problemas. Inicialmente era somente para corrigir a cor de um mês desabilitado selecionado na data da fatura para onPrimary, para ficar mais visível. Só que com as alterações vindas da upstream, percebi que o dropdown de seleção da data do mês de referencia foi removido tanto da página de edição quanto lançamento da fatura. Após fazer alguns comentários na issue me pediram para recolocar o datePicker novamente somente na página de edição da fatura. Então recoloquei novamente na página de edição e corrigi o que issue queria inicialmente, que era a cor para onPrimary.

### Artur Rodrigues
- **Tarefas concluídas:** [#151](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/151) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260)
- **Dificuldades encontradas:** Enfrentei desafios com a validação de CNPJ e o ajuste da responsividade com zoom na interface. Para a validação, foi necessário um controle mais refinado para garantir que o mesmo CNPJ fosse cadastrado em diferentes instituições, além de gerar exceções específicas para cada caso, sem comprometer a integridade dos dados. Já no zoom, o desafio foi corrigir o desajuste dos elementos na interface.
- **Relatos:** Tive que aprender como adaptar a lógica de validação de CNPJ para que funcionasse corretamente em diferentes contextos. Também precisei entender melhor como a estrutura do layout afetava a responsividade e como garantir que a interface se comportasse bem em diferentes resoluções. Esse processo me ajudou a melhorar meus conhecimentos sobre exceções e boas práticas de CSS. 

### Beatriz Nascimento
- **Tarefas concluídas:**  Realizei mudanças solicitadas na issue 387 feita na sprint 2
- **Relatos:**  Os ajustes foram esses: CurrentDate repetido no set, mudar para setOneDayAfterCurrentDate, retirar comentario em RenewContract e usar um Max entre os dois elementos, e não um OR, usando o OR com datas, sempre o primeiro elemento é o retornado, caso não seja undefined.

### Chaydson Ferreira
- **Tarefas concluídas:** Implementação de testes unitários para os componentes AverageConsumptionPlot, BaseCostComparisonCard, BaseCostComparisonPlot, CurrentBaseCostPlot, DetailedAnalysisHeader, MeasuredConsumptionPlot, MeasuredDemandPlot, RecommendationCard e Revisão dos MRs da Sprint 3.
- **Dificuldades encontradas:** Ajustes nas configurações do ambiente de testes foram necessários para garantir a compatibilidade total com a versão mais recente do framework utilizado.
- **Relatos:** A abordagem de escrever os testes de forma modular permitiu identificar rapidamente qualquer discrepância ou falha durante a execução dos testes.

### Delziron Braz
- **Tarefas concluídas:**  [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e .[419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419)
- **Dificuldades encontradas:** 
- **Relatos:** Desenvolvi testes unitários para aumentar a cobertura de testes no MEPA API, focando especificamente nos módulos user_type e tariff_utils. Além disso, corrigi a implementação da Sprint 2, que envolvia ajustes no menu principal.
Os testes foram implementados com sucesso e passaram sem falhas. O maior desafio, mais uma vez, foi lidar com o lint no pipeline. No entanto, com o suporte dos monitores, conseguimos identificar e resolver o problema corretamente utilizando o Ruff.
Vale destacar que os testes foram desenvolvidos em pareamento com Lucas Felipe, o que contribuiu significativamente para a qualidade do código.
Por fim, sobre a correção do menu principal, o problema estava relacionado à necessidade de um rebase. Com o merge request, a alteração acabou sendo sobrescrita, mas a questão já foi corrigida.

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
- **Tarefas concluídas:** [#151](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/151) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260)
- **Dificuldades encontradas:** Enfrentei desafios com a validação de CNPJ e o ajuste da responsividade com zoom na interface. Para a validação, foi necessário um controle mais refinado para garantir que o mesmo CNPJ fosse cadastrado em diferentes instituições, além de gerar exceções específicas para cada caso, sem comprometer a integridade dos dados. Já no zoom, o desafio foi corrigir o desajuste dos elementos na interface.
- **Relatos:** Tive que aprender como adaptar a lógica de validação de CNPJ para que funcionasse corretamente em diferentes contextos. Também precisei entender melhor como a estrutura do layout afetava a responsividade e como garantir que a interface se comportasse bem em diferentes resoluções. Esse processo me ajudou a melhorar meus conhecimentos sobre exceções e boas práticas de CSS.

### Lucas Felipe Soares
- **Tarefas concluídas:** [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408).  
- **Dificuldades encontradas:** Não sabia como resolver os problemas de pipeline da issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e dependi bastante do suporte do Flávio para lidar. Estive com um pouco menos de tempo por problemas pessoais e outras disciplinas então foi uma sprint mais pesada que as demais. 
- **Relatos:** A issue [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408), tive de fazer algumas correções passadas pela Adne no MR da sprint 1. Já os problemas de pipeline da issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) consegui resolver e aproveitei para aumentar mais a cobertura de testes, sobretudo do módulo de universidades que havia trabalhado menos na sprint passada.

### Lucas Spinosa
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** Esperei o surgimento de issues no frontend do projeto, mas não aconteceu. Não peguei issues essa sprint, mas vou pegar issue de backend na próxima sprint caso não surjam issues de frontend.

### Mateus de Almeida
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** Não sei se existe um endpoint para pesquisar distribuidoras pelo cnpj para fazer validações, por isso fiquei estacionado pensando em outra forma de implentar o pedido.
- **Relatos:** Nessa sprint foquei em resolver uma pendência da sprint 2, na verdade eu só precisava implementar a validação no campo do cnpj quando o usuário estivesse editando uma distribuidora já existente, já que na criação de uma nova distribuidora eu já havia implementado essa validação e inclusive foi aceita no mr, então seria como uma nova issue relacionada a issue [#445](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/445), mas infelizmente ainda não consegui implementar o proposto.

### Pedro Henrique Rodrigues de Carvalho
- **Tarefas concluídas:** Desenvolvimento de testes unitários para os componentes AverageConsumptionPlot, BaseCostComparisonCard, BaseCostComparisonPlot, CurrentBaseCostPlot, DetailedAnalysisHeader, MeasuredConsumptionPlot, MeasuredDemandPlot, RecommendationCard e revisão dos MRs da Sprint 3.
- **Dificuldades encontradas:** Foi preciso realizar ajustes nas configurações do ambiente de testes para assegurar total compatibilidade com a versão mais recente do framework adotado.
- **Relatos:** A estratégia de modularizar os testes facilitou a detecção rápida de inconsistências ou falhas durante a execução.

### Silas Souza
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** Nessa sprint pareei com Gabriel Marcolino na issue [447](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/447), e estamos esperando resposta do rodrigo para finalizar esta issue, e além disso também trabalhei na issue [448](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/448)., foi implementado a função de excluir UC sem faturas no front, porém falta a implementação no back-end
