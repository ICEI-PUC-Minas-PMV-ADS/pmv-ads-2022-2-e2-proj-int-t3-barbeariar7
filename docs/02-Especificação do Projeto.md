# Especificações do Projeto

Tendo em vista a necessidade do cliente em ter uma ferramenta que o ajudasse a organizar e anunciar a sua barbearia, foi requisitado uma aplicação interativa que o auxiliasse a suprir suas necessidades. A aplicação contará com agendamento online, valores de serviços e outras funcionalidades que o cliente desejar. 

## Personas

|Jeredy Bittencourt Falcão |              |                    |
|--------------------|--------------------|--------------------|
| **Idade**: 23 anos.    | **Ocupação** : Estudante de Economia na USP – Universidade de São Paulo. | **Aplicativos**: Facebook , Instagram , Twitter. |
| **Motivações** : Facilidade em ver os tipos de cortes para o meu estilo. |  **Frustrações** : Falta de opção em salão para tipos de corte.     |**Hobbies** : Natação Viajar Assistir Series.|

| Wilson Gomes da costa |                  |                  |
|-------------------------|------------------|------------------|
| **Idade**: 37 anos      | **Ocupação** :  Atua como professor.   | **Aplicativos**: WhatsApp ,Instagram ,Twitter . |
| **Motivações** : Praticidade na hora de marcar um corte de cabelo.| **Frustrações** :Não conseguir agendar um horário para ir ao salão. |  **Hobbies**: Ler livros, ir a lugares com a família como museu, zoológico e restaurantes.  |

| Amanda de Souza lino  |                  |                  |
|-------------------------|------------------|------------------|
|**Idade**: 32 anos | **Ocupação**: Analista administrativa.  | **Aplicativos**: WhatsApp ,Instagram |
| **Motivações** :Poder agendar um horário no salão para meu filho com facilidade e praticidade. | **Frustrações** :Não conseguir agendar um horário para que meu filho corte o cabelo.| **Hobbies**: Passear em parques ecológicos e fazer piqueniques com meus filhos e marido.|

| Kaio Oliveira Souza |                  |                  |
|-------------------------|------------------|------------------|
|**Idade**: 28 anos. |**Ocupação**: Youtuber  e Streamer |**Aplicativos** : Whatsapp , telegram |
|**Motivações** : Praticidade em poder marcar um horário. | **Frustações** :Não poder ver o trabalho do barbeiro, pois já tive cortes horríveis. |**Hobbies** :Jogar Video Game |

| Maria da conceição  |                  |                  |
|-------------------------|------------------|------------------|
|**idade** : 36 anos |**Ocupação** : Recursos Humanos RH. |**Aplicativos**: Whatsapp , Intagram |
|**Motivações** : Ver horários e dias em que a vagas para poder marcar. | **Frustações** : Dificuldade em agendar um horário para meu filho cortar o cabelo. |**Hobbies** Viajar para locais históricos , assistir series , Ir ao cinema |

| Clodoval Gates Jobs   |                  |                  |
|-------------------------|------------------|------------------|
|**idade** : 32 anos |**Ocupação** :  Analista de Sistemas em um grande banco. |**Aplicativos**:Linkedin , Facebook |
|**Motivações** : Ter informação de localização fácil ao salão. | **Frustações** :Sou deficiente auditivo e não consigo falar ao telefone.  |**Hobbies** : Boxe , Ler livros. |


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Jeredy Bittencourt Falcão | Ver os tipos de cortes do salão. | Porque evitará de ir até o salão e saber quais tipos de corte trabalham.  |
|Wilson Gomes da costa     | Poder saber os horários disponíveis. | Ter acesso a agenda da barbearia de uma maneira mais acessível.       |
|Kaio Oliveira de Souza    | Marcar um horário sem ter que ir ao salão ou ligar.  | Evitar de ficar esperando em filas ou ser atendido.   |
|Amanda de Souza lino      | Ter acesso ao perfil do profissional e da barbearia. | Conhecer um pouco do ambiente ao qual levarei meu filho.  |
|Clodoval Gates Jobs       | Um site que tenha acessibilidade para o cliente.     | Sou deficiente auditivo e não consigo me comunicar através de palavras, preciso conseguir marcar um corte de forma fácil.  |
|Maria da conceição        | Ter acesso a agenda da barbearia para saber os dias e horários disponíveis.|Saber os horários disponíveis para fazer um agendamento . |


## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir. 

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve apresentar o telefone de contato da barbearia.                                                    | MÉDIA | 
|RF-002| A aplicação deve abrir um menu durante o agendamento para selecionar o (os) serviço (os) disponíveis.              | ALTA  |
|RF-003| A aplicação deve permitir a avaliação do serviço.                                                                  | MÉDIA | 
|RF-004| A aplicação deve permitir que o cliente faça mais de um agendamento.                                               | MÉDIA |
|RF-005| A aplicação deve apresentar, a todos os momentos, o endereço da barbearia.                                         | ALTA  | 
|RF-006| A aplicação deve ter uma funcionalidade de login para seus usuários (Donos de barbearias, barbeiros e clientes)    | ALTA  |
|RF-007| Terá de ser uma aplicação acessível para todos os públicos.                                                        | ALTA  | 
|RF-008| A administração da aplicação ficará por responsabilidade do dono da Barbearia.                                     | MÉDIA |
|RF-009| A aplicação deve permitir que o cliente faça o cancelamento antecipado ou alteração do serviço agendado.           | ALTA  | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve funcionar nos principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge).          | ALTA | 
|RNF-002| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada.                           | ALTA | 
|RNF-003| O site deve ter bom nível de contraste entre os elementos da tela em conformidade.                                | MÉDIA | 
|RNF-004| O site deve ser publicado em um ambiente acessível publicamente na Internet (GitHub Pages).                       | ALTA | 
|RNF-005| Usar a linguagem C Sharp (C#) para o Back-end.                                                                    | ALTA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de xx/xx/xxxx.  |
|02| O aplicativo deve se restringir às tecnologias básicas da Web no Frontend e Backend                      |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho.                                            |



## Diagrama de Casos de Uso

![Diagrama  (2)](https://user-images.githubusercontent.com/103226164/189015034-d1c74286-b6aa-464c-8ca3-a26d4b4be4b7.png)


