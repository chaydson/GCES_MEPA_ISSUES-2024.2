# Sprint 2 - Documentação

## Informações Gerais
- **Início da Sprint:** 02/12/2024
- **Fim da Sprint:** 12/12/2024
- **Objetivo da Sprint:** Avanço das contribuições no Projeto MEC-Energia

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
| felipegf1                         | @felipegf1          |



# Issues por Membro

| Nome                              | Issues                                                  |
|-----------------------------------|--------------------------------------------------------|
| Ana Beatriz Massuh                | [#360](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/360) e [#419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419)                                           |
| Artur Jackson                     | [#192](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/192) e [#442](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/442)                                          |
| Artur Rodrigues                   | [#218](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/218) |
| Beatriz Vieira                | [#387](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/387)   |
| Delziron Braz                     |   [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194), [#419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419)                        |
| Felipegf1                         |                                           |
| Gabriel Marcolino Rodrigues       | [#294](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/294) e [#137](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/137) |                                        |
| Guilherme de Sá Gonçalves         | [#192](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/192) e [#442](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/442)                                              |
| João Barreto                      | [#218](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/218) |
| Lucas Felipe Soares         |[#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408) e [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194)     |
| Lucas Spinosa                     | [#278](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/278) e [#251](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/251)  |
| Mateus de Almeida                 | [#216](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/216#resumo), [#443](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/443) e [#445](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/445)         |
| Pedro Henrique Rodrigues de Carvalho | |
| Silas Souza                       |                                            |
| Chaydson Ferreira                 | [#415](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/415), [450](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/450), [449](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/449) |



## Participação dos Membros da Equipe durante a sprint 2

### Ana Beatriz Massuh
- **Tarefas concluídas:** [#360](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/360), [#419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419) e verificação dos merges
- **Dificuldades encontradas:** Garantir que as implementações dos membros não interferissem ou quebrassem as funcionalidades existentes, o que demandou tempo para entender o contexto de cada alteração.
- **Relatos:** Realizei uma análise cuidadosa das alterações solicitadas pela equipe, verificando um por um para garantir que fossem compatíveis com a base de código atual, fiz ajustes significativos nos campos de "Potência Instalada" e "Demanda de Geração", implementando a sincronização bidirecional entre eles, como solicitado na sprint passada e  junto ao Delziron implementei a persistência do estado de abertura do menu lateral usando localStorage, o que permite que o menu mantenha seu estado entre atualizações e reaberturas da página.

### Artur Jackson
- **Tarefas concluídas:**  [#192](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/192) e [#442](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/442)
- **Dificuldades encontradas:** Verificar os valores que ainda não possuiam o ponto ou virgula.
- **Relatos:** Fiz as issues pareando com o Guilherme de Sá. Fizemos uma correção na issue 442 da sprint passada, com o feedback do João, arrumamos um espaçamento em branco desnecessário abaixo dos gráficos na aba de Análise. Também estou com issue 444 sobre corrigir o texto da data de fatura onde já comecei a tentar resolver, mas estou com alguns problemas no momento, porém vai ser meu foco na próxima sprint juntamente com a realização de testes

### Artur Rodrigues
- **Tarefas concluídas:** (**Parcialmente**) [#218](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/218) 
- **Dificuldades encontradas:** Autorização durante a realização do teste da funcionalidade.
- **Relatos:** Foi uma sprint cansativa onde surgiram vários problemas grandes a partir de um problema menor. Foi difícil concluir a issue justamente por falta de conhecimento avançado sobre as autorizações e requisições do projeto. Tive problemas com o teste.

### Beatriz Vieira Nascimento
- **Tarefas concluídas:** [#387](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/387)
- **Dificuldades encontradas:** O único problema que encontrei enquanto trabalhava na issue foi que, ao tentar transformar a data vinda do contrato em um objeto `Date`, ela sempre era convertida para o dia anterior. No entanto, após uma breve pesquisa, consegui resolver o problema. Segue a [solução](https://stackoverflow.com/questions/7556591/is-the-javascript-date-object-always-one-day-off).
- **Relatos:** A issue tinha como objetivo evitar uma renovação com a mesma data ou uma data anterior ao contrato atual. Foi uma tarefa bem tranquila de realizar, e não encontrei muitas dificuldades.

### Chaydson Ferreira
- **Tarefas concluídas:** [#415](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/415), [450](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/450), [449](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/449)
- **Dificuldades encontradas:** Entender a estrutura de testes do projeto
- **Relatos:** Foram criados testes para funcoes da pasta utils, a configuracao do jest para apresentar detalhes sobre a cobertura e iniciado a issue para componentizar a tabela de faturas, porem essa nao foi finalizada devido a duvidas

### Delziron Braz
- **Tarefas concluídas:** [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194), [#419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419) 
- **Dificuldades encontradas:** Na issue [#419](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/419) a maior dificuldade foi encontrar uma solução que pudesse ser desenvolvidade sem a necessidade de resolver a issue do carregamenta da tela em conjunto, pois, houve dificuldade em encontrar o problema que causava o regarregamento das views 
- **Relatos:** Foram criados testes para aumentar a cobertura do backend, onde cada passaram com êxito, como também, foi solucionada o problema com o estado do menu e a issue foi aceita.

### Felipe Guimaraes
- **Tarefas concluídas:** [#427](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/427) e [#404](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/404)
- **Dificuldades encontradas:** Apos entender melhor a estrutura do projeto , nessa sprint a maior dificuldade foi apenas alguns problemas tecnicos na minha maquina
- **Relatos:**  na sprint passada a minha primeira issue ainda nao havia passado no merge porem foi aprovada nessa sprint faltando apenas um detalhe que surgiu de ultima hora pra ser corrigido. E na segunda issue o problema foi simples de ser resolvido bastando apenas ajustar um posicionamento na tela por conta de um bug especifico com o rodapé

### Gabriel Marcolino Rodrigues
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** A principal dificuldade na #294 é para avaliar a possibilidade de unificar a tabela da prévia e a tabela na tela de UC em um único componente parametrizado. Já na #137 é no entendimento da regra de negócio da recomendação a qual pretendo buscar melhor entendimento com alguém do projeto. 
- **Relatos:** Para essa sprint peguei duas issues mais trabalhosas do que a primeira. A issue #294 tem vários ajustes no front-end que precisam ser feitos, já resolvi alguns deles e estou focando nela primeiro. Já a issue #137 é uma de back-end que precisa aumentar a cobertura de testes referentes as recomendações. 

### Guilherme de Sá Gonçalves
- **Tarefas concluídas:** [#192](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/192) e [#442](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/442)
- **Dificuldades encontradas:** Nada foi muito difícil, porém a parte mais trabalhosa foi fazer a varredura de todos os campos numéricos, para ver se a regra, do "." na casa de milhar, da issue #192 estava sendo aplicada ou não.
- **Relatos:** Uma vez encontradas as poucas ocorrências, apenas conversei com o Rodrigo e o João sobre como era pra ser formatado, pois já havia duas fórmulas que cuidavam disso: Uma com "." e duas casas decimais, e outra, sem as casas decimais. Uma vez respondida, fiz as alterações junto do meu par, Artur Jackson. Além disso foi feito uma correção na issue da sprint passada, com o feedback do João, arrumamos um espaçamento em branco desnecessário abaixo dos gráficos na aba de Análise. Também comecei a estudar mais as estruturas dos testes no backend, área que ainda não tinha explorado, porém vai ser meu foco na próxima sprint, ligado de forma geral a issue [#219](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/219)

### João Barreto
- **Tarefas concluídas:** (**Parcialmente**) [#218](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/218) 
- **Dificuldades encontradas:** Autorização durante a realização do teste da funcionalidade.
- **Relatos:** O código precisava retornar erros espcíficos na hora da criação de um contrato. Dessa forma, a resolução dessa parte no backend foi consideravelmente fácil, após o entendimento da estrutura do projeto. No entanto, na criação dos testes ocorreram vários erros e o principal deles foi o de autenticação, o que gerou grande dificuldade e a não conclusão da issue.

### Lucas Felipe Soares
- **Tarefas concluídas:** [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408) e [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194)  
- **Dificuldades encontradas:** Na issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-endosergia-api/-/issues/194) tive dificuldades iniciais para entender como se dava a estrutura dos testes até o momento e precisei tirar algumas dúvidas com o FLávio e o pessoal. Além mais, não tinha olhado tanto a estrutura do backend até o momento então tive que me ambientar um pouco mais para entender melhor em como fazer esses testes. Como demandava melhorar a arquitetura dos testes acredito que podemos melhorar mais ainda essa cobertura que já foi iniciada. Na issue [#408](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/408), apesar de conseguir ordenar numericamente a maioria das colunas ainda ocorre bugs em alguns dados em especial que não estão sendo ordenados, gostaria de conferir esse comportamento com a equipe.  
- **Relatos:** Fiz pareamento com o [Delziron Braz](https://gitlab.com/DelzironBraz) na issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-endosergia-api/-/issues/194) devido a quantidade de testes a serem explorados.

### Lucas Spinosa
- **Tarefas concluídas:** Nenhuma
- **Dificuldades encontradas:** Tive dificuldades com a arquitetura do projeto.
- **Relatos:** Nessa sprint tive dificuldades em encontrar tempo para me dedicar às issues, e por isso não consegui finalizar as tarefas, ficando assim para a próxima sprint.

### Mateus de Almeida
- **Tarefas concluídas:** [#216](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/216#resumo), [#443](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/443) e [#445](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/445)
- **Dificuldades encontradas:** As dificuldades encontradas continuam semelhantes a sprint anterior, ou seja, dificuldade com a arquitetura do projeto. Nessa sprint peguei uma issue da API [#216](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/216#resumo) e tive algumas dificuldades como a obtenção do token para fazer requisições a API, mas que foram sanadas pelo Flávio Vieira, além disso tive dificuldade para entender algumas respostas da API, mas em conversa com o Flávio consegui entender melhor as regras de negócio.
- **Relatos:** Consegui implementar o que as issues pediam, que eram respectivamente: Adicionar validação de data de início de vigência do contrato, Corrigir cor das setas de paginação nas tabelas de Pessoas e Instituições e Mensagem de erro de "Distribuidora já cadastrada".

### Pedro Henrique Rodrigues de Carvalho
- **Tarefas concluídas:** [#415](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/415), [450](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/450), [449](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/449)
- **Dificuldades encontradas:** Entender as funções utilitárias e a estrutura de testes do frontend.
- **Relatos:** Foram elaborados testes para funções da pasta utils. A configuração do Jest foi ajustada para fornecer detalhes sobre a cobertura dos testes. Iniciou-se uma issue para modularizar a tabela de faturas, porém esta não foi concluída devido a dúvidas persistentes.
  
- ### Silas Souza
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 


