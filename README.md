Carlos Alexandre de Oliveira Fraga

Projeto para Prova Delphi App 

Permita gerar e visualizar o SQL gerado,onde seja possível ao usuário inserir as tabelas, condições e colunas.

Permite  ao usuario informar o tempo de evento que cada  iteração deverão aguardar para executar a tarefa.

Permite Inserir 10 registros dinamicamente de forma aleatória  e projetar os valores  em  Obter total e Obter Total Divisões.

                      
Pré-requisitos:
 
Sistema Operacional  Windows

Executando os testes do Sistema Prova Delphi App:

Os testes do software são executados, usando os procedimentos e documentos de script de teste. Para que a fase de execução de teste, seja realizada com sucesso.

Exemplificando:Etapas de testes:

Sistema de Prova Delphi App:


1.0)   Tela Tarefa 01:

1.1) Memo Campo:

Passo 1 -No campo Memo o usuário informa o(s) nome(s) do(s) Campo(s) da Tabela , caso o usuário deixar o campo vázio.

Passo 2 -Clique no botão 'Gerar SQL'.
Passo 3 -Resultado esperado: Uma mensagem exibindo Tal: "Favor informar o(s) nome(s) do(s) campo(s) da tabela.Tente novamente obrigado".



1.2) Memo Nome da Tabela:

Passo 1 -No campo Memo Tabela o usuário informa o nome da Tabela , caso o usuário deixar o campo vázio.

Passo 2 -Clique no botão 'Gerar SQL'.

Passo 3 -Resultado esperado: Uma mensagem exibindo  tal: "Favor informar o nome da tabela.Tente novamente obrigado".

1.3) Ainda no Memo Nome da Tabela:

Passo 1 -No campo Memo Tabela o usuário informa o nome da Tabela , caso o usuário preencher com mais de um nome de tabela.

Passo 2 -Clique no botão 'Gerar SQL'.

Passo 3 -Resultado esperado: Uma mensagem exibindo  tal: "É permitido informar apenas uma tabela para a geração do SQL".


1.4) Memo Condições:

Passo 1 -No campo Memo Condições o usuário informa o nome da Tabela , caso o usuário deixar o campo vázio.

Passo 2 -Clique no botão 'Gerar SQL'.

Passo 3 -Resultado esperado: Uma mensagem exibindo  tal: "Favor informar as condições para a geração do SQL.Tente novamente obrigado".


1.5) Botão Gerar SQL:

Passo 1 -Usuário clique no botão 'Gerar SQL'.

Passo 2 -Resultado esperado: Disponibilizar no campo Memo SQL Gerado pelo usuário.


2.0) Tarefa 02:

2.1) Campo tempo da tarefa 01:

Passo 1 -No campo informe o tempo da tarefa 01 , caso o usuário deixar o campo vázio.

Passo 2 -Clique no botão 'Executar'.

Passo 3 -Resultado esperado: Uma mensagem exibindo  tal: "Favor informar o tempo para primeira tarefa.Tente novamente obrigado".


2.2) Campo tempo da tarefa 02:

Passo 1 -No campo informe o tempo da tarefa 02 , caso o usuário deixar o campo vázio.

Passo 2 -Clique no botão 'Executar'.

Passo 3 -Resultado esperado: Uma mensagem exibindo  tal: "Favor informar o tempo para segunda  tarefa.Tente novamente obrigado".

2.3) Botão Executar:

Passo 1 -Usuário clique no botão 'Executar'.

Passo 2 -Resultado esperado: Disponibilizar barras de progressos das tarefas Um e Dois e

exibe mensagem do fim das tarefas tal:Tarefas 100% finalizadas com sucesso.


3.0) Tela Tarefa 03:

3.1) Botão Obter Total:

Passo 1 – Usuário clique no botão 'Executar'.

Passo 3 -Resultado esperado: Disponibiliza Total obtido no campo Total R$.



3.2) Botão Obter Total Divisões:

Passo 1 – Usuário clique no botão 'Obter Total Divisões'.

Passo 3 -Resultado esperado: Disponibiliza Total da divisões obtido no campo Total da Divisoes R$


Testes de estilo de codificação:

As convenções de estilo de codificação são usadas em alguns de exemplo para ajudar na clareza e consistência. As convenções de notação "húngaras" são usadas. Elas se

tornaram uma prática de codificação comum na programação do Win32. Elas incluem notações de prefixo variável que dão a nomes de variáveis uma sugestão do tipo da variável.


Exemplificando: Algumas Etapas Testes de estilo de codificação:


Passo 1 - Nome Declaração de Unidade :

Passo 2 - Nome função  tais: fExecaoParametros , fExecaoParametrosTfTarefa02 efObterTotal.

Passo 3 - Nome variável  tais: sValor , ffloat , dValorDivisao  e dValorTotalDivisao. 

Passo 4 - Nome Formulário tais:  uProvaDelphiApp , ufTarefa1 , ufTarefa2 , e ufTarefa3.

Passo 5 - Nome Procedimento  tais: pFtModelTarefa02Threads , pCriarClientDataSetDataSource  e pDestroiClientDataSetDataSource.



Ferramentas utilizadas no desenvolvimento do Projeto Prova Delphi App :


Passo 1 - Windows 10 Home Single Language

Passo 2 - Delphi 10.4 Community Edition (licença Estudante)


Versão do Sistema Prova Delphi App:

Passo 1 - Versão 1.0 -( Atualizado em 23/05/2022)

Desenvonvedor: Carlos Alexandre de Oliveira Fraga 

Telefone:    021 -994463083

WhatsApp: 021 -994463083

e-Mail: cfraga03@yahoo.com.br


Perfil:


Atuação no Instituto Nacional de Câncer(INCA) desde  05/2000 até 01/2022   na área de Tecnologia da Informação, com análise e projeto de sistemas, levantamento de requisitos

e regras de negócio, mapeamento de processos e modelagem de dados, padrão de qualidade das rotinas e

processos, impacto das alterações, garantia da integridade dos sistemas, com acompanhamento e validação e desenvolvimento de Sistemas Instiuicionais.


Projetos Desenvolvidos:

Objetivo Estratégico: Contribuir para o desenvolvimento tecnológico do complexo produtivo da saúde.

Linha de Ação:Contribuir para a produção, integração e difusão do conhecimento na área do câncer,

promovendo sua aplicação na qualificação dos recursos humanos e dos serviços.

Objetivos:

 Desenvolver e implantar banco de dados multi-agente e analítico temporal no Centro de Transplante de

Medula Óssea(CEMO);

 Gerenciar informações, indicadores, faturamento, rastreabilidade e controle de estoque;

 Integrar com outros Sistema Institucionais, prestando auxílio aos responsáveis por tomadas de decisões

a curto, médio e longo prazo.

 Serviços contemplados tais: laboratório de Citogenética, laboratório de Imunologia, Laboratório de

Oncovirologia, laboratório de Imunogenética, laboratório de Células Tronco, Assistência médica, Apoio

Admnistrativo, Banco de Sangue de Cordão Umbilical e Placentário (BSCUP), laboratório de

Criopreservação, Faturamento, Transplante de medula óssea, Gerenciamento Familiares dos doadores

Aparentados , Tratamento Tabagismo e Internação Hospitalar.


Sistemas:

Sistema de Informação laboratotial para histocompatibilidade(SisHLA)

Sistema de Gestão do Centro de Medula Óssea(SGC)

Sistema Inca Livre do Tabagismo(SisPIL)

Sistema da Central de Internação do INCA(SisCII)



Agradecimentos;

A Deus pela iluminação divina, Softplan por me selecionar para participar do processo seletivo para a vaga de Desenvolvedor Delphi e minha esposa minha grande companheira.

