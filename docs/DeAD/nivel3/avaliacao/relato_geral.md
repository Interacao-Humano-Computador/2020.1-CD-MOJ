# Relato geral da avaliação do protótipo de alta fidelidade

## Introdução

<p style="text-indent: 20px; text-align: justify">
Nesse documento será listada as respostas para as perguntas levantadas no planejamento da avaliação do protótipo de alta fidelidade. As avaliações foram realizadas conforme o que está descrito no <a class="link" href="../planejamento">documento de planejamento</a>.
</p>

## Perguntas a serem respondidas

- **O sistema é eficaz?** Sim
- **O sistema é eficiente?** Na maoria das tarefas sim, mas peca em alguns aspectos, como pesquisa dos contests (relatada nos documentos de avaliação)
- **O sistema é seguro?** Sim
- **O sistema é útil?** Sim
- **O sistema é aprendível?** Sim
- **Uma vez aprendido, as funcionalidades do sistema são de fácil lembraça?** Sim
- **Todas as opções disponíveis ao usuário estão visíveis?** Na maioria sim, exceto pelo falso botão do "CD-MOJ" na barra de menu
- **As opções são de fácil acesso?** A maioria sim, mas para baixar uma submissão a opção não é de fácil acesso na página da questão
- **A quantidade de janelas (páginas) é coerente com o guia de estilo?** Sim
- **A estrutura das tarefas no design auxilia o usuário a realizar seus objetivos?** Sim
- **O usuário consegue a realizar seus objetivos com o mínimo de passos possíveis?** Sim
- **O usuário tem controle e liberdade adequados?** Sim
- **Os padrões de design são respeitados?** Sim
- **O usuário consegue reconhecer os elementos da interface ao invés de memorizá-los?** Sim
- **A interface é consistente e padronizada?** Sim
- **A interface possui estética e design minimalista?** Sim

## Problemas encontrados

### Avaliação heurística

- 7 - Flexibilidade e eficiência de uso
    - **local onde ocorreu:** na página de contests
    - **contexto:** O usuário ao visualizar a lista de contests, vendo o botão do scoreboard
    - **causa:** Não ter uma explicação do que esse botão faz
    - **efeito sobre o usuário:** Desorientação
    - **efeito sobre a tarefa:** Leve atraso
    - **sugestões de solução:** Colocar uma tooltip explicando

- 2 - Compatibilidade do sistema com o mundo real
    - **local onde ocorreu:** Em todas as páginas
    - **contexto:** Ao tentar voltar à página inicial do sistema, o usuário se sente perdido ao tentar acessar o item "CD-MOJ" na barra de menu
    - **causa:** Quebra o padrão de outros sites, onde a logo ou o nome do site leva à página inicial
    - **efeito sobre o usuário:** Confusão, desorientação e frustração
    - **efeito sobre a tarefa:** Atraso
    - **sugestões de solução:** Fazer com que o item "CD-MOJ" redirecione para a página inicial do sistema

- 2 - Compatibilidade do sistema com o mundo real e 7 - Flexibilidade e eficiência de uso
    - **local onde ocorreu:** Na página de contests
    - **contexto:** O usuário ao procurar um contest específico na lista de contests
    - **causa:** Não ter uma opção de busca
    - **efeito sobre o usuário:** Irritação
    - **efeito sobre a tarefa:** Atraso significativo
    - **sugestões de solução:** Colocar uma opção de busca

### Teste de usabilidade

#### Tarefas:

- **Tarefa 1:** Responder uma questão de um contest específico
- **Tarefa 2:** Visualizar um scoreboard e/ou lista de submissões de um contest específico
- **Tarefa 3:** Baixar uma submissão já enviada

#### Problemas gerais

- Página inicial ser a página de contests públicos
    - **local onde ocorreu:** em todo o protótipo
    - **descrição e justificativa:** é um problema pois causa confusão sobre aonde procurar os contests
    - **efeito sobre o usuário:** confusão
    - **efeito sobre a tarefa:** atraso
    - **sugestões de solução:** mudar a home para a página de últimas novidades ou criar uma nova página para ser a home

#### Tarefa 1

- Botão "CD-MOJ" na barra principal não redireciona para a home
    - **local onde ocorreu:** no header
    - **descrição e justificativa:** não redirecionar para a home
    - **efeito sobre o usuário:** confusão
    - **efeito sobre a tarefa:** nenhum
    - **sugestões de solução:** fazer o botão redirecionar para home

#### Tarefa 2

- Não é claro inicialmente aonde encontrar as submissões
    - **local onde ocorreu:** na tela de questões
    - **descrição e justificativa:** por muitas vezes a tabela é cortada exibindo apenas o titulo. E falta de caminhos alternativos para a realização da tarefa.
    - **efeito sobre o usuário:** confusão
    - **efeito sobre a tarefa:** atraso
    - **sugestões de solução:** manter a tabela de submissões na página de contest, mas adicionar um botão na tela de questão que abre uma modal (caixa de diálogo) na qual as submissões dessa questão são listadas. Possivelmente colocar da mesma forma do botão de scoreboard no contest um botão que abre a mesma modal citada anteriormente

- Não é claro inicialmente aonde encontrar ajuda sobre a pontuação no scoreboard
    - **local onde ocorreu:** na tela de scoreboard
    - **descrição e justificativa:** poucos participantes encontraram o que cada pontuação representa.
    - **efeito sobre o usuário:** dificuldade na interpretação dos dados apresentados
    - **efeito sobre a tarefa:** Atraso
    - **sugestões de solução:** colocar um ícone que representa ajuda "?" do lado do cabeçalho de pontos que mostra como visualizar e compreender os dados.

#### Tarefa 3

- Opção de baixar presente apenas na página do contest
    - **local onde ocorreu:** na tela de contest e questão
    - **descrição e justificativa:** opção de baixar presente apenas na página do contest
    - **efeito sobre o usuário:** confusão
    - **efeito sobre a tarefa:** atraso
    - **sugestões de solução:** adicionar opção de baixar a última submissão enviada no nome do arquivo listado na página de questão. E também deixar a opção de baixar na modal citada na solução do problema de submissões na tarefa 2.

## Referências

- ROSA, José. "Avaliação e Projeto no Design de Interfaces". 2AB Editora, 2010.
- BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.

## Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 28/11/2020 | Criação do documento | Todos os integrantes |
| 2.0 | 01/12/2020 | Adição dos problemas encontrados | Igor Paiva E Rhuan Carlos |
