# Especificações do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr>
<th colspan="2">Cliente</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Pessoas que precisam encontrar alguém para realizar determinado serviço.
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
Encontrar profissionais de forma simples e ter informações suficientes para decidir se aquela pessoa é confiável e adequada para realizar o serviço.
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Profissional</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Profissionais que procuram oportunidades para trabalhar.
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
Apresentar suas habilidades, divulgar os serviços que realizam e encontrar possíveis clientes.
</td>
</tr>
</tbody>
</table>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

<table>
<tbody>
<tr>
    <td>Eu como …</td>
    <td>… quero/desejo …</td>
    <td>… para ....</td>
</tr>
<tr>
    <td>Cliente</td>
    <td>encontrar profissionais que realizem o serviço que preciso</td>
    <td>conseguir contratar alguém de forma mais fácil</td>
</tr>
<tr>
    <td>Cliente</td>
    <td>visualizar informações sobre o profissional</td>
    <td>saber se ele possui experiência com o serviço que preciso</td>
</tr>
<tr>
    <td>Cliente</td>
    <td>pesquisar profissionais por tipo de serviço</td>
    <td>encontrar pessoas que realmente trabalham com o que estou procurando</td>
</tr>
<tr>
    <td>Profissional</td>
    <td>cadastrar os serviços que realizo</td>
    <td>divulgar meu trabalho e encontrar possíveis clientes</td>
</tr>
<tr>
    <td>Profissional</td>
    <td>receber solicitações de pessoas interessadas no meu serviço</td>
    <td>conseguir novas oportunidades de trabalho</td>
</tr>
<tr>
    <td>Profissional</td>
    <td>informar minha disponibilidade</td>
    <td>evitar receber solicitações em períodos em que não posso realizar o serviço</td>
</tr>
</tbody>
</table>

## Requisitos

### Requisitos Funcionais

<tbody>
<table>

<tr>
    <td>ID</td>
    <td>Descrição</td>
    <td>Prioridade</td>
</tr>
<tr>
    <td>RF-01</td>
    <td>O sistema deve permitir que o usuário realize seu cadastro como cliente ou profissional.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-02</td>
    <td>O sistema deve permitir que o profissional cadastre os serviços que oferece.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-03</td>
    <td>O sistema deve permitir que o profissional cadastre suas habilidades e experiências.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-04</td>
    <td>O sistema deve permitir que o cliente pesquise profissionais por tipo de serviço.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-05</td>
    <td>O sistema deve permitir que o cliente visualize o perfil do profissional.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-06</td>
    <td>O sistema deve permitir que o cliente consulte as avaliações de um profissional.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-07</td>
    <td>O sistema deve permitir que o cliente entre em contato com um profissional.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-08</td>
    <td>O sistema deve permitir que o cliente envie uma solicitação de serviço para um profissional.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-09</td>
    <td>O sistema deve permitir que o profissional visualize as solicitações de serviço recebidas.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-10</td>
    <td>O sistema deve permitir que o profissional aceite uma solicitação de serviço.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RF-11</td>
    <td>O sistema deve permitir que o profissional informe sua disponibilidade para realizar serviços.</td>
    <td>Média</td>
</tr>
<tr>
    <td>RF-12</td>
    <td>O sistema deve permitir que o cliente avalie o profissional após a realização do serviço.</td>
    <td>Média</td>
</tr>
<tr>
    <td>RF-13</td>
    <td>O sistema deve permitir que o profissional atualize suas informações cadastrais.</td>
    <td>Média</td>
</tr>
<tr>
    <td>RF-14</td>
    <td>O sistema deve permitir que o profissional atualize os serviços que oferece.</td>
    <td>Média</td>
</tr>
<tr>
    <td>RF-15</td>
    <td>O sistema deve permitir que o profissional recuse uma solicitação de serviço.</td>
    <td>Média</td>
</tr>

</tbody>
</table>

**Prioridade: Alta / Média / Baixa.  

### Requisitos Não Funcionais

<tbody>
<table>

<tr>
    <td>ID</td>
    <td>Descrição</td>
    <td>Prioridade</td>
</tr>
<tr>
    <td>RNF-01</td>
    <td>O sistema deve possuir uma interface simples e fácil de utilizar.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RNF-02</td>
    <td>O sistema deve ser compatível com dispositivos móveis e computadores.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RNF-03</td>
    <td>O sistema deve proteger os dados pessoais dos usuários contra acessos não autorizados.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RNF-04</td>
    <td>O sistema deve armazenar os dados dos usuários de forma segura.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RNF-05</td>
    <td>O sistema deve apresentar mensagens claras para informar erros ou problemas durante a utilização.</td>
    <td>Média</td>
</tr>
<tr>
    <td>RNF-06</td>
    <td>O sistema deve apresentar tempo de resposta adequado nas principais operações realizadas pelos usuários.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RNF-07</td>
    <td>O sistema deve organizar as informações de forma clara e legível.</td>
    <td>Alta</td>
</tr>
<tr>
    <td>RNF-08</td>
    <td>O sistema deve estar disponível para utilização, exceto durante períodos de manutenção.</td>
    <td>Média</td>
</tr>

</tbody>
</table>
**Prioridade: Alta / Média / Baixa.

