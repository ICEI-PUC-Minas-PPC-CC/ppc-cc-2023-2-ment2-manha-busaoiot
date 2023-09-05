# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do diagrama de personas (identifiquem, no mínimo, 2 personas), histórias de usuários (identifiquem, no mínimo, 3 histórias de usuários por persona), requisitos funcionais, requisitos não funcionais e artefatos produzidos para levantamento de dados).

## Personas


|**Jorge Almeida**|           |                             | 
|-------------------|-----------|-----------------------------|
<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/Template-MentoringII/blob/main/docs/img/jorge2.png" width="200" height="200"/>|**Idade:** 29 anos. **Naturalidade:** Pouso Alegre - Minas Gerais. **Ocupação:** Estoquista.       |**Atribuições:** Responsável por fazer o recebimento, a conferência, a verificação da validade e do estoque dos produtos. Além disso, ele realiza balanços, inventários e relatórios. 
|**Motivações:** : Almeja um cargo mais alto dentro da empresa, para prover maior conforto a sua família.
  |**Frustações:** : Dificuldades de administrar seu tempo, pois mora longe da empresa onde trabalha e chega muito tarde e cansado em casa.
  |**Hobbies, história:** : Conhecer lugares diferentes em seu tempo livre com sua família.

|**Alice Gonzaga**|           |                             | 
|-------------------|-----------|-----------------------------|
<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/Template-MentoringII/blob/main/docs/img/alice2.png" width="200" height="200"/>|**Idade:** 52 anos. **Naturalidade:** Inconfidentes - Minas Gerais. **Ocupação:** Vendedora.       |**Atribuições:** : Responsável por fechar novos negócios e trazer receita. Suas principais atividades incluem prospectar clientes, realizar apresentaçõese e enviar propostas comerciais.
|**Motivações:** : Planeja uma aposentadoria tranquila, para que possa descansar e viajar com seu marido.
  |**Frustações:** :Sempre muito preocupada com as metas a serem batidas, muitas vezes perde o sono e  precisa acordar cedo para pegar ônibus para chegar a empresa. Isso consequentemente não acaba gerando um bom desempenho no trabalho.
|**Hobbies, história:** : Passear com seu cachorro e ir para o sítio de seus pais.

  |**César Faria**|           |                             | 
|-------------------|-----------|-----------------------------|
<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/Template-MentoringII/blob/main/docs/img/cesar2.png" width="200" height="200"/>|**Idade:** 35 anos. **Naturalidade:** Águas da Prata - São Paulo. **Ocupação:** Frentista.       |**Atribuições:** : Abastecer veículos, fazer o atendimento de clientes, auxiliar com o pagamento dos serviços prestados, e ajudar na limpeza e manutenção de veículos.
|**Motivações:** : Prentende construir uma família com sua noiva, por isso precisa dinheiro para construir sua casa própria.
|**Frustações:** : Como mora longe do posto em que trabalha, fica muito tempo no trajeto para casa, gerando um desconforto pois queria mais tempo para passar com sua noiva.
|**Hobbies, história:** : Sair aos domingos com sua noiva para fazer algo diferente saindo assim da rotina.




Enumere e detalhe as personas da sua solução. Para isso, se necessário, leia um pouco mais sobre o assunto nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes/beneficiários ideais que sua solução almeja.

Para selecionar as imagens de suas personas, utilize o site: https://this-person-does-not-exist.com/pt

## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

Exemplo:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Jorge Almeida | Otimizar meu tempo. | Conseguir dedicar mais tempo ao trabalho e a sua família. |
|Alice Gonzaga | Horario mais flexível e preciso. | Ter mais controle de seu sono, e desmpenhar no trabalho. |
|César Faria | Ônibus com melhores trajetos. | Chegar com rapidez no trabalho e em casa. |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução ou para execução da sua prática extensionista/curso. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação e também para identificar as dores que sua prática extensionista irá minimizar/sanar. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Obs.1: Caso seu grupo não vá desenvolver uma solução de software, as seções "requisitos funcionais", "requisitos não funcionais" e "restrições" DEVERÃO ser REMOVIDAS.
## Obs.2: Caso seu grupo não vá desenvolver algum atividade que demande, uma pesquisa de campo através de questinários, a seção "artefatos para levantamento de dados" DEVERÁ ser REMOVIDA.

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deverá permitir o gerenciamento dos pacientes | ALTA | 
|RF-002| O sistema deverá exibir todo histórico de atendimento do paciente   | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo | MÉDIA | 
|RNF-002| o sistema deve processar requisições do usuário em, no máximo, 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
-O sistema deve mostrar a proximidade do onibus, assim, os usuarios pode sair para o ponto apenas no momento exato, por exemplo, caso há um atraso, as pessoas ficariam sabendo.
-Quantos onibus fazem esse percurso durante o dia e quais os horarios gerais que passam, sem muita especificação, para melhor noção dos usuarios.
-Um tabela dos onibus da regiao em que o usuario esta, e quando clicado em especifico ponto de onibus mostrar em quantos minutos passa o proximo do mesmo.
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
-As principais caracteristicas dessa aplicação seria a não necessidade do publico de correr perigo na rua esperando um ônibus
-A comodidade de esperar em casa e não na rua. 
-A noção de quanto tempo ira chegar no trabalho com maior exatidão.
-Confiabilidade no programa quanto a exatidão do percurso.
-Confiabilidade no programa quanto a exatidão do horário.
-Grande variação de geolocalização, visto os vários pontos de ônibus mapeados.
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

### Artefatos para levantamento de dados

Foram produzidos dois artefatos para levantamento de dados, o artefato numero um é um questionário feito no Google forms, via disponibilização pela web e  será divulgado em grupos/páginas relevantes em poços de caldas.
o segundo artefato é um questionário feito no Google forms, que será preenchido in loco, procurando abordar pessoas nos pontos de ônibus e preenchendo o formulário ( O material a ser preenchido in loco pode também ser impresso porém com o Google forms é mais eficiente.)

Material que será disponibilizado pela web: https://docs.google.com/forms/d/e/1FAIpQLSeiCC-UlCB4Gp3AtXTV23MTwZWK1IHCoDyKkAS3QU1_UR3j5Q/viewform?usp=sf_link

Material que será preenchido in loco: https://docs.google.com/forms/d/e/1FAIpQLSdou_1PDT4T4_cgeFoaBfeSDPASLOGNGRWm8AhdrNDS7jFyMQ/viewform?usp=sf_link


Futuros resultados serão descritos na seção "detalhamento preliminar" ( Etapa 3).

