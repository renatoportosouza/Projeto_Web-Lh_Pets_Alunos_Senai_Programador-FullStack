Projeto_Web-Lh_Pets
Este repositório contém o código para o projeto web LH Pets, um sistema de cadastro de clientes com funcionalidades de back-end. O projeto foi desenvolvido como parte de um desafio de aprendizado e demonstra a criação de rotas, interação com banco de dados e hospedagem local.

Descrição
O projeto LH Pets consiste em um sistema web para cadastro de clientes, onde é possível listar os clientes cadastrados em um banco de dados. O sistema foi desenvolvido utilizando as seguintes tecnologias:

Linguagem: C#
Framework: ASP.NET
Banco de dados: SQL Server
Funcionalidades
Rotas:
/: Exibe a versão inicial do projeto ("LH Pets - Protótipo 1").
/index: Exibe a página inicial "index.html" fornecida pelo Front-end.
/listaClientes: Exibe a lista de clientes cadastrados no banco de dados.
Pré-requisitos
Para executar este projeto, você precisará ter os seguintes softwares instalados e configurados em seu computador:

SQL Server
SQL Server Management Studio (SSMS)
VSCode
Instruções de instalação
Instalação do SQL Server:
Consulte o tutorial: CodBack_InstalacaoSQL.pdf (anexado ao card).
Instalação do SQL Server Management Studio:
Consulte o tutorial: CodBack_SSMS_Install_Login_Script.pdf (anexado ao card).
Configuração do banco de dados:
Crie um banco de dados no SQL Server para armazenar os dados dos clientes.
Configure a string de conexão com o banco de dados no arquivo Banco.cs.
Executando o projeto
Clone este repositório para o seu computador.
Abra o projeto no VSCode.
Restaure os pacotes NuGet, se necessário.
Execute o projeto.
Acesse o sistema através do seu navegador, utilizando as rotas descritas acima.
Estrutura do projeto
Banco.cs: Contém a classe responsável pela conexão e interação com o banco de dados.
Program.cs: Contém a classe principal e as rotas do sistema.
index.html: Página inicial do sistema (fornecida pelo Front-end).
Contribuição
Este projeto foi desenvolvido para fins de aprendizado. Contribuições e melhorias são bem-vindas.
