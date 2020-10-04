# Análise de Tarefas

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
Análise de tarefas é parte de maior foco da área de interação humano computador, pois se preocupa com a perfomance do trabalho, e isso é o que a distingue de outras técnicas. Uma abordagem sistemática é adotada para descrever as propriedades dos modelos usados na análise de tarefas. Tem como objetivo fornecer ao designer a visão dos usuários em relação as tarefas que eles precisam executar (Diaper e Stanton, 2004).
</p>

## 2. CNM-GOMS

<p style="text-indent: 20px; text-align: justify"> 
O modelo GOMS (Goals, Operators, Methods, and Selection Rules) é um método para analisar o desempenho de usuários a partir do seu conhecimento sobre como realizar uma tarefa em termos de objetivos, métodos, operadores e regras de seleção. O CMN-GOMS se refere à proposta original de GOMS, elaborada por Card, Moran e Newell (Barbosa e Silva, 2010).
</p>

## 3. Motivo da escolha

<p style="text-indent: 20px; text-align: justify">
Nós decidimos utilizar o GOMS pois ele pode ser usado tanto para prever a performance da tarefa quanto substituir testes de usuário empíricos necessários para chegar a um design que é tanto funcional quando utilizável. Mais especificamente decidimos utilizar o CNM-GOMS porque a análise é executável, qualquer exigência da tarefa pode ser simulada seguindo caminhos diferentes, dependendo de cada tarefa (Barbosa e Silva, 2010).
</p>

## 4. Objetivos

### 4.1 Realizar contest como aluno

<p>
<b>GOAL 0</b>: Realizar contests
<br>&emsp;<b>GOAL 1</b>: Encontrar contest
<br>&emsp;&emsp;<b>OP 1.1</b>: Descer a página até encontrar o contest desejado
<br>&emsp;&emsp;<b>OP 1.2</b>: Deslocar o cursor do mouse para o botão "Join"
<br>&emsp;&emsp;<b>OP 1.3</b>: Clicar com o botão esquerdo do mouse
<br>
<br>&emsp;<b>GOAL 2</b>: Preencher as informações de login
<br>&emsp;&emsp;<b>OP 2.1</b>: Preencher o campo de login
<br>&emsp;&emsp;<b>OP 2.2</b>: Preencher o campo de senha
<br>&emsp;&emsp;<b>OP 2.3</b>: Deslocar o cursor do mouse para o botão "login"
<br>&emsp;&emsp;<b>OP 2.4</b>: Clicar com o botão esquerdo do mouse
<br>
<br>&emsp;<b>GOAL 3</b>: Visualizar questão
<br>&emsp;<b>METHOD 3.A</b>: Através do PDF
<br>&emsp;(SEL. RULE: O usuário queira ver a questão no formato <i>pdf</i>)
<br>&emsp;&emsp;<b>OP 3.A.1</b>: Deslocar o cursor do mouse para o link "PDF"
<br>&emsp;&emsp;<b>OP 3.A.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;<b>METHOD 3.B</b>: Através do HTML
<br>&emsp;(SEL. RULE: O usuário queira ver a questão numa página <i>html</i>)
<br>&emsp;&emsp;<b>OP 3.B.1</b>: Deslocar o cursor do mouse para o link "HTML"
<br>&emsp;&emsp;<b>OP 3.B.1</b>: Clicar com o botão esquerdo do mouse
<br>
<br>&emsp;<b>GOAL 4</b>: Submeter questão
<br>&emsp;&emsp;<b>METHOD 4.A</b>: Escolher questão e enviar
<br>&emsp;&emsp;&emsp;<b>OP 4.A.1</b>: Deslocar o cursor do mouse para o campo de seleção de questão
<br>&emsp;&emsp;&emsp;<b>OP 4.A.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;&emsp;<b>OP 4.A.3</b>: Selecionar questão a ser submitada
<br>&emsp;&emsp;&emsp;<b>OP 4.A.4</b>: Deslocar o cursor do mouse para o botão "Escolher arquivo"
<br>&emsp;&emsp;&emsp;<b>OP 4.A.5</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;&emsp;<b>OP 4.A.6</b>: Importar arquivo com a questão respondida
<br>&emsp;&emsp;&emsp;<b>OP 4.A.7</b>: Deslocar o cursor do mouse para o botão "submit"
<br>&emsp;&emsp;&emsp;<b>OP 4.A.8</b>: Clicar com o botão esquerdo do mouse
<br>
<br>&emsp;<b>GOAL 5</b>: Visualizar se a questão foi aceita
<br>&emsp;&emsp;<b>OP 5.1</b>: Apertar F5 até que o veredito não seja "Not Answered Yet"
</p>

### 4.2 Gerenciar contest como professor

<p>
<b>GOAL 0</b>: Gerenciar contest
<br>&emsp;<b>GOAL 1</b>: Encontrar contest
<br>&emsp;&emsp;<b>OP 1.1</b>: Descer a página até encontrar o contest desejado
<br>&emsp;&emsp;<b>OP 1.2</b>: Deslocar o cursor do mouse para o botão "Join"
<br>&emsp;&emsp;<b>OP 1.3</b>: Clicar com o botão esquerdo do mouse
<br>
<br>&emsp;<b>GOAL 2</b>: Preencher as informações de login
<br>&emsp;&emsp;<b>OP 2.1</b>: Preencher o campo de login
<br>&emsp;&emsp;<b>OP 2.2</b>: Preencher o campo de senha
<br>&emsp;&emsp;<b>OP 2.3</b>: Deslocar o cursor do mouse para o botão "login"
<br>&emsp;&emsp;<b>OP 2.4</b>: Clicar com o botão esquerdo do mouse
<br>
<br>&emsp;<b>GOAL 3</b>: Visualizar todas as submissões
<br>&emsp;&emsp;<b>OP 3.1</b>: Deslocar o cursor do mouse para o botão "Todas as submissões"
<br>&emsp;&emsp;<b>OP 3.2</b>: Clicar com o botão esquerdo
<br>
<br>&emsp;<b>GOAL 4</b>: Visualizar a tabela de pontuação
<br>&emsp;&emsp;<b>OP 4.1</b>: Deslocar o cursor do mouse para o botão "Score"
<br>&emsp;&emsp;<b>OP 4.2</b>: Clicar com o botão esquerdo
<br>
<br>&emsp;<b>GOAL 5</b>: Acessar a ferramenta Sherlock
<br>&emsp;&emsp;<b>OP 5.1</b>: Deslocar o cursor do mouse para o botão "Sherlock"
<br>&emsp;&emsp;<b>OP 5.2</b>: Clicar com o botão esquerdo
<br>
<br>&emsp;<b>GOAL 6</b>: Visualizar estatísticas
<br>&emsp;&emsp;<b>OP 6.1</b>: Deslocar o cursor do mouse para o botão "Estatísticas"
<br>&emsp;&emsp;<b>OP 6.2</b>: Clicar com o botão esquerdo
<br>
<br>&emsp;<b>GOAL 7</b>: Alterar senha
<br>&emsp;&emsp;<b>OP 7.1</b>: Deslocar o cursor do mouse para o botão "Trocar senha"
<br>&emsp;&emsp;<b>OP 7.2</b>: Clicar com o botão esquerdo
<br>
<br>&emsp;<b>GOAL 8</b>: Fazer Logout
<br>&emsp;&emsp;<b>OP 8.1</b>: Deslocar o cursor do mouse para o botão "Logout"
<br>&emsp;&emsp;<b>OP 8.2</b>: Clicar com o botão esquerdo
<br>
</p>

## 5. Referências Bibliográficas

- BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.
- DIAPER, Dan; STANTON, Neville. "The handbook of task analysis for human-computer interaction". Mahwah, NJ: Lawrence Erlbaum Associates, 2004.


## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 03/10/2020 | Criação do documento de CMN-GOMS | Todos os integrantes |
