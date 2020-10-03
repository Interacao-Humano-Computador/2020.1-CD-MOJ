# Análise de Tarefas

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
Uma análise de tarefas é utilizada para se ter um entendimento sobre qual é o trabalho dos usuários, como eles o realizam e por quê. Nesse tipo de análise, o trabalho é definido em termos dos objetivos que os usuários querem ou precisam atingir. Segundo Diaper (2003), a análise de tarefas é: “a expressão utilizada no campo da ergonomia, que inclui IHC, para representar todos os métodos de coletar, classificar e interpretar dados sobre o desempenho de um sistema que possua ao menos uma pessoa como componente”.
</p>

## 2. Motivo da escolha

<p style="text-indent: 20px; text-align: justify">
Decidimos utilizar esta técnica pois ela fornece uma abordagem genérica para a investigação de problemas de IHC (Annet e Diaper, 2003). E também porque ela facilita a ilustração de tarefas do sistema, separando-as em objetivos, subobjetivos e operações e os relacionando de diferentes maneiras em relação a como as tarefas devem ser executadas pelo usuário, demonstrando as possibilidades de <i>inputs</i>, ações, <i>feedback</i> e problemas que estão no contexto da ferramenta análisada. 
</p>

## 3. Análise Hierárquica de Tarefas (HTA)

<p style="text-indent: 20px; text-align: justify">
A Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis) foi desenvolvida na década de 1960 para entender as competências e habilidades exibidas em tarefas complexas e não repetitivas, bem como para auxiliar na identificação de problemas de desempenho (Annett, 2003; Annett e Duncan, 1967). Ela ajuda a relacionar o que as pessoas fazem (ou se recomenda que façam), por que o fazem, e quais as consequências caso não o façam corretamente. Ela se baseia em psicologia funcional, e não comportamental, como eram as abordagens da época em que foi criada.
</p>

### 3.1 Diagrama HTA para Efetuar login como aluno

![Análise Tarefas Aluno](assets/HTA/analise_tarefas_aluno.png)

[Link para a imagem](https://app.lucidchart.com/invitations/accept/ed3219a7-79c7-487e-bb7a-e810025fc394)

### 3.2 Representação de Tarefas para o Objetivo Efetuar login como aluno

|Objetivo/Operações|Problemas e Recomendações|
|-|-|
| 0. Visualizar *contests* 1/3 | **ação**: Selecionar entre presentes, passados e vindouros <br /> **plano**: Participar de um *contest* e resolver os problemas |
| 1. Acessar *contest* 1/2 | **ação**: Clicar no *contest* desejado <br /> **plano**: Acessar o *contest* desejado |
| 1.1. Efetuar *Login* 1/2 | **plano**: Visualizar questões do *contest* |
| 1.1.1. Verificação usuário| **feedback**: O sistema informa se a senha está incorreta |
| 1.1.2. Informar *login* e senha | **input**: Fornecer *login* e senha |
| 1.1.2.1. Confirmar *login* 1/4 | **ação**: Clicar no botão de *login* |
| 1.1.2.1.1. Visualizar questões do *contest* | **plano**: Visualizar questões do *contest* |
| 1.1.2.1.2. Alterar senha | **feedback**: O sistema informará se é possível alterar a senha <br /> **input**: A nova senha <br /> **ação**: Clicar no botão de mudar a senha |
| 1.1.2.1.3. Fazer *logout* | **ação**: Sair do *contest* atual |
| 1.1.2.1.4. Selecionar questão 1/3 | **plano**: Escolher uma questão para resolver ou visualizar |
| 1.1.2.1.4.1. Resolver um problema | **ação**: Pensar numa solução para o problema  |
| 1.1.2.1.4.1.1. Submeter a resposta | **ação**: Clicar no botão e selecionar um arquivo <br /> **feedback**: O sistema irá informar o veredito da submissão |
| 1.1.2.1.4.2. Visualizar questão em PDF | **ação**: Abrir descrição da questão em um documento PDF |
| 1.1.2.1.4.3. Visualizar questão em HTML | **ação**: Abrir descrição da questão em um documento HTML  |
| 1.2. Fazer cadastro no mojinho | **ação**: Fazer cadastro do usuário por meio do chatbot mojinho |
| 2. Acessar *score* | **plano**: Visualizar quais questões os participantes já enviaram e/ou acertaram|
| 3. Acessar estatística | **plano**: Visualizar os dados estatísticos acerca das questões <br /> **feedback**: O sistema irá informar se a estatística está disponivel |

### 3.3 Diagrama HTA para efetuar login como professor

![Análise Tarefas Professor](assets/HTA/analise_tarefas_professor.png)

[Link para a imagem](https://app.lucidchart.com/invitations/accept/aa7c054f-83d1-4e9c-b7ca-dec5cc45823a)

### 3.4 Representação de Tarefas para o Objetivo Efetuar login como professor

|Objetivo/Operações|Problemas e Recomendações|
|-|-|
| 0. Efetuar *login*| **plano**: Efetuar *login* e senha |
| 1. Informar *login* e senha| **input**: Fornecer *login* e senha |
| 2. Confirmar *login* 1/8 |  **ação**: Clicar no botão de *login* |
| 2.1. Acessar *Sherlock* | **plano**: Descobrir as submissões suspeitas de plágio <br /> **feedback**:  O sistema informa os códigos que suspeitos de plágio |
| 2.2. Acessar *Score* | **plano**: Mostrar quais questões foram enviadas pelos participantes do *contest* |
| 2.3. Visualizar questões do *contest* | **plano**: Visualizar as questões do *contest* |
| 2.4. Alterar Senha | **feedback**: O sistema informará se é possível alterar a senha. <br /> **problema**: O sistema não permite que a senha seja alterada.|
| 2.5. Fazer *logout* | **ação**: Sair do *contest* atual |
| 2.6. Selecionar questão 1/3 | **plano**: Selecionar uma questão para resolver |
| 2.6.1. Resolver um problema | **ação**: Criar uma solução para o problema proposto |
| 2.6.1.1. Submeter a resposta | **ação**: Clicar no *select* para escolher a questão e submeter o *script*/código com a possível solução da questão |
| 2.6.2. Visualizar questão em PDF | **ação**: Mostrar questão em formato *PDF*.|
| 2.6.3 Visualizar questão em HTML | **ação**: Mostrar questão em formato *HTML*. |
| 2.7. Visualizar estatísticas | **plano**: Visualizar os dados estatísticos acerca das questões <br /> **feedback**: O sistema irá informar se a estatística está disponivel |
| 2.8. Visualizar todas as submissões | **ação**: Mostrar todos os exercícios enviados por cada aluno. |

## 4. Referências Bibliográficas

- BARBOSA, Simone. SILVA Bruno. "Interação Humano-Computador"
- ANNETT, J. “Hierarchical Task Analysis”. In: D. Diaper & N. Stanton (eds.), The handbook of task analysis for human-computer interaction. Mahwah, NJ: Lawrence Erlbaum Associates, pp. 67 –82, 2003.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 03/10/2020 | Criação documento de analise de tarefas | Todos os integrantes |
