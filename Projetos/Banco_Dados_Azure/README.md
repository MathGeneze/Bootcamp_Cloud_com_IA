# Guia Azure - Criando seu Primeiro Banco de Dados SQL

<!--------------- 📌 Introdução -------------->
## 📌 Introdução
> Este repositório faz parte de um exercício prático para quem está começando a explorar **serviços de banco de dados em nuvem**. O foco aqui é aprender como **criar e configurar um Banco de Dados SQL** utilizando o **Microsoft Azure**, uma das principais plataformas de computação em nuvem do mercado.
>
> Abaixo você encontrará um passo a passo detalhado, além de dicas para usar o serviço de forma eficiente e econômica.

&nbsp;

<!--------------- 📒 Sumário -------------->
## 📒 Sumário
- [➥ O que é o Azure SQL Database?](#o-que-é-o-azure-sql-database)
- [➨ Passo a Passo: Criando o Banco de Dados](#passo-a-passo-criando-o-banco-de-dados)
- [➨ Dicas Úteis](#dicas-úteis)
- [➦ Conclusão](#conclusão)

&nbsp;

<!--------------- 🌐 O que é o Azure SQL Database -------------->
<a id="o-que-é-o-azure-sql-database"></a>
## 🌐 O que é o Azure SQL Database?
> O **Azure SQL Database** é um serviço de banco de dados relacional totalmente gerenciado, baseado no SQL Server. Ele oferece alta disponibilidade, escalabilidade, segurança e backup automático, sem que você precise se preocupar com a infraestrutura.
>
> Vantagens principais:
> - **Totalmente gerenciado pela Microsoft** 
> - **Backup automático e alta disponibilidade** 
> - **Escalabilidade vertical e horizontal** 
> - **Ideal para aplicações web e de negócios** 

&nbsp;

<!--------------- ♻️ Passo-a-passo: Criando o Banco de Dados -------------->
<a id="passo-a-passo-criando-o-banco-de-dados"></a>
## ♻️ Passo a Passo: Criando o Banco de Dados

1. Acesse o portal do Azure  
   🔗 [https://portal.azure.com](https://portal.azure.com)

2. No menu lateral, clique em **"Criar um recurso"**  
   - Procure por **SQL Database** e clique em **Criar**

3. Preencha os dados iniciais:
   - **Assinatura** e **Grupo de Recursos** (crie um novo se necessário)
   - **Nome do Banco de Dados** (ex: `meu-banco-dados`)
   - Em **Servidor**, clique em **Criar novo** e defina:
     - Nome do servidor (ex: `meuservidor123`)
     - Localização (ex: Brazil South)
     - Nome de usuário e senha do administrador

4. Escolha o modelo de compra:
   - Plano de uso: `Uso geral` ou `Desenvolvimento/Teste` para economizar
   - Configure o tamanho e desempenho de acordo com seu projeto

5. Configure os **requisitos de rede**:
   - Permitir acesso a partir de serviços do Azure
   - Adicionar seu IP atual (para conseguir acessar o banco localmente)

6. Clique em **Revisar + Criar** e, depois da validação, clique em **Criar**

&nbsp;

<!--------------- 💡 Dicas Úteis -------------->
<a id="dicas-úteis"></a>
## 💡 Dicas Úteis
> - Use um **grupo de recursos** exclusivo para bancos, facilitando o gerenciamento.
> - Para testes e aprendizado, utilize a opção **Desenvolvimento/Teste** que reduz os custos.
> - Sempre defina **regras de firewall** com segurança: apenas os IPs necessários devem ter acesso.
> - Após a criação, você pode se conectar ao banco pelo **Azure Data Studio**, **SQL Server Management Studio (SSMS)** ou via script Python/Power BI.

&nbsp;

<!--------------- ✅ Conclusão -------------->
<a id="conclusão"></a>
## ✅ Conclusão
> Criar um **banco de dados SQL no Azure** é uma ótima forma de começar a trabalhar com **soluções de dados escaláveis** e profissionais. O serviço oferece praticidade, segurança e desempenho — ideal para quem está aprendendo ou desenvolvendo aplicações reais.
