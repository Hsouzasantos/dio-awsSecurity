# Relatorio de Implementação de Serviços AWS
Data: 04/06/2024 </br>
Empresa: Abstergo Industries </br>
Responsável: Hugo Santos

## Introdução
<p>Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Hugo Santos. O objetivo do projeto foi elencar 3 serviçoes AWS, com a finalidade de realizar diminuição de custos imediatos</p>

## Descrição do Projeto
<p>O projeto terá 3 etapas de implemnetação de ferramentas, cada uma com seus objetivos especificos e estão descritas em cada etapa do projeto</p>

### Etapa 1
 - Gerenciamento de Identidade e Acesso (IAM):

    * Benefícios:
      <p>O IAM permite controlar quem tem acesso a quais recursos da AWS na sua organização. Você pode criar usuários e grupos, definir políticas de acesso detalhadas e monitorar atividades para garantir que apenas usuários autorizados tenham acesso aos seus dados e sistemas.</p>
      
  * Utilização: O IAM pode ser utilizado para:
    * Controlar o acesso a servidores EC2, bancos de dados RDS e armazenamento S3.
    * Permitir que usuários externos acessem recursos específicos com permissões limitadas.
    * Implementar autenticação multifator (MFA) para adicionar uma camada extra de segurança.
  * Cenário:
    <p>Uma empresa de distribuição de medicamentos precisa conceder acesso a um aplicativo web a representantes de vendas externos. O acesso deve ser limitado apenas aos dados dos clientes relevantes para cada representante, e a empresa precisa garantir que apenas usuários autorizados e autenticados possam acessar o aplicativo.</p>

## Etapa 2
  - Criptografia de Dados:

    * Benefícios:
      <p>A AWS oferece diversas opções para criptografar seus dados em repouso e em trânsito, protegendo-os contra acesso não autorizado, mesmo em caso de violação de dados.</p>

    * Utilização: Você pode criptografar:
      * Discos de instâncias EC2 com o Amazon Elastic Block Store (EBS).
      * Bancos de dados RDS com criptografia de banco de dados.
      * Objetos S3 com criptografia de servidor ou criptografia de lado do cliente.
     
    * Cenário:
      <p>Uma empresa de distribuição de medicamentos precisa armazenar dados confidenciais de pacientes, como histórico médico e informações de seguro, em um banco de dados na AWS. A empresa precisa garantir que esses dados estejam protegidos contra acesso não autorizado, mesmo em caso de violação de dados.</p>

Etapa 3
  - Rede Privada Virtual (VPC):

    * Benefícios:
      <p>A VPC permite criar uma rede virtual privada e isolada dentro da AWS, isolando seus recursos de outras redes e da internet pública.</p>
      
    * Utilização:
      * Você pode utilizar a VPC para:
      * Isolar seus bancos de dados e aplicativos críticos.
      * Controlar o tráfego de rede entre seus recursos.
      * Implementar listas de controle de acesso (ACLs) para restringir o acesso à sua rede.
     
    * Cenário
      <p>Uma empresa de distribuição de medicamentos precisa isolar seus aplicativos e dados críticos de outros recursos na AWS e da internet pública. A empresa precisa garantir que apenas usuários e serviços autorizados possam acessar esses recursos.</p>
     
Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado garantir que apenas pessoas especificas tenham acesso aos dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Hugo Santos
