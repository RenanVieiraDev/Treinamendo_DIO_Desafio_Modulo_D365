Desafio do Bootcamp DIO - Programação C# com CRM Dynami

<h1>Versão 1.0.0.1</h1>
Instalação e versões:

Na solução que contêm a versão 1.0.0.1 deverá
ser baixado e instalado somenta a solução com o nome "ConclusoTreinamentoDIO" que está no arquivo ConclusoTreinamentoDIO_1_0_0_1.zip.
Após baixa-lá importe para o ambiente Power Apps desejado.

Descrição e requisitos da versão 1.0.0.1:

  O aplicativo  foi criado com um conceito Model Driven utilizando como Datasource o contexto do formulário em execução,
apresentado nas aulas.

Requisitos:
 - Contêm Cabeçalho;
 - Contêm um campo de entrada de texto do tipo caixa de combinação (ComboBox) permitindo a seleção do curso;
 - contêm Detalhe (componente do tipo Gallery);
 - O Campo de entrada de texto é do tipo caixa de combinação (ComboBox), permitindo a seleção do instrutor.
 - Contêm um fluxo do Power Automate que quando um novo registro de instrutor for criado, envie um e-mail (endereço do e-mail será o informado no cadastro do instrutor).

<h1>Versão 1.0.0.2</h1>
Instalação e versões:

Na solução que contêm a versão 1.0.0.2 deverá
ser baixada e instalada no ambiente Power Apps desejado e junto
contêm um projeto em c# que contêm 4 plugins 1 actione 2 workflows
baixe esse projeto que está no arquivo Projeto_Treinamento_Dio_c#.rar.

Logo você poderar aditar esse projeto em qualquer editor de codigo desejado,
fortimente indico o visula studio.

Informações da aplicação

- 1ª Plugin realiza a validação da tabela account, a verificação se da no campo de email para validar se foi informado o email.
- 2ª Plugin Verifica se o telefone informado para o registro de account existe em algum registro de contato, caso aja, ele vincula o registro do contato ao registro de account sendo criada no momento.
- 3ª Plugin ao criar um registro de account o plugin valida se o campo website contêm valor e caso sim ele cria uma tarefa vinculado ao account sendo criado no momento.
- 4ª Plugin assinc ele tem ação de criar 10 registro da tabela de contato e nomear cada contato com o nome do account sendo criado no momento.
- 5ª Action, essa action tem por finalidade pegar o Cep informado pelo usuario e popular o endereço da tabela aluno que está sendo criada no monento,
  para a execução desta ação, crie ou edite un registro da tabela Aluno, informe um CEP valido no campo CEP e click no botão "pegar cep".
  Inform:
      ![image](https://github.com/RenanVieiraDev/Treinamendo_DIO_Desafio_Modulo_D365/assets/47308053/d417fe20-5901-49ff-96ec-b32d71f12f4e)

  - 6ª Workflow 1, valida se o Aluno contem mais mais de 2 registro da tabela "Aluno x Cursos Disponiveis" contem mais de 2 como "em curso" caso contenha mais de 2 como "SIM" ele barra a inclusão do aluno ao curso.
  - 7ª Workflow 2, quando o Aluno é inserido em um curso disponivel é criado um calendario do aluno informando as datas das aulas por periodo.


