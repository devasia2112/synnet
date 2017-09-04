## Sistema Synet

O sistema foi desenvolvido para ser usado na web apenas.


- Gestão de Clientes
    - Cadastro de clientes.
    - Ativação e Desativação de Clientes.
    - Painel de Gerenciamento de Clientes.
    - Central do Cliente. (Area dedicada ao acesso do cliente)
        - Gera segunda via de boletos
        - visualizar histórico financeiro
        - solicitar alteração de dados cadastrais
    - Multiplos Contratos
    - Google Maps com a localização do endereço de instalação do contrato do cliente.


- Central de Revendas
    - cadastre revendedores
    - Revendedor tem acesso único a central de revendas, controlando seus proprios clientes.

- Agenda
    - Crie entradas na agenda toda vez que uma nova ordem de serviço for criada.

- Ordem de Serviço
    - Abertura de chamados de ordem pelo cliente via Central do Cliente ou via telefone.
    - Impressão de ordem de serviço para o técnico

- Cadastro de Planos
    - Cadastro de perfil de plano (categoria)
    - cadastro dos planos

- Pagamento
    - Boleto Bancário
    - Gateways (via API, fácil e rápido de implementar)
    - Cielo (pendente de homologação - cada empresa deve homologar o seu - homologamos por R$ 600,00)

- Bloqueio e Desbloqueio de Clientes
    - Bloqueio automático de clientes inadimplentes.
    - Desbloqueio automático baseado na baixa de pagamentos via boleto (pendente automatizar a baixa de pagtos via cartão).


- Financeiro
    - Billing Completo (Internet)
    - Contas a Pagar e Receber
    - Fluxo de Caixa e Conciliação Bancária
    - NF Modelo 21 (arquivo tem limite de 990 item por doc fiscal, inicio em .001)

- Cobrança
    - Cartas de Cobrança via email e correio tradicional (SPC, Jurídico, primeiro aviso, segundo aviso, etc..)

- Servidores e Rede
    - Integrado com a rede mikrotik.
    - Integrado com a rede BFW3.
    - Pode ser facilmente integrado com outras redes e servidores.

- Estoque
    - controle de patrimonio.
    - relatorio de items no estoque.
    - transferencia de items de um estoque para outro (almoxarifados diferentes)

- Relatórios
    - bloqueios
        - Bloqueados pelo sistema (inadimplencia)
        - bloqueados a pedido do cliente
    - estatísticas (Gráficos)
        - Equipamentos por Torre
        - Assinantes por Planos
        - Ordem de Serviço
    - contas
        - boletos emitidos
    - logs
        - logs de acesso
    - anatel
        - SICI - Sistema de Coleta de Informações (ANATEL)

- Backup
    - backup automatico do banco de dados (via cronjobs)


- Mais Informações
    - Clientes ilimitados (versão na nuvem esta limitado para no máximo 600 clientes)
    - Rádios e RB ilimitados.
    - Importamos o seu banco de dados por R$ 300,00


- Ambiente de Instalação
    - Servidor Linux Debian 8 x64 (Jessie), PHP versão 5.3+, MySQL 5.5+, Python, Nginx 1.10+ ou Apache 2.2.2+



#### Custo de um software alternativo no mercado.

| Software      | Mensal   | Anual  | <em>Adesão</em>  |
| ------------- | -------- | ------ | ----------------:|
| Mercado       | R$300    | R$3600 | R$ 600 ~ R$ 1000 |

<em>primeiro ano apenas.</em>


#### Preco Final do sistema Synet (codigo fonte e banco de dados mysql incluso)

| Software      | ~~Mensal~~   | Anual  | <em>Adesão</em> | **Source Code**     |
| ------------- | ------------ | ------ | --------------- | ------------------- |
| Synet         | R$180        | R$2160 | R$600           | R$68.000 ~ R$86.000 |

~~Sistema na nuvem para gerenciar até 600 clientes (inclui todos os módulos, inclusive o gerador de NF de Serviços Mod. 21)~~

<em>primeiro ano apenas, o valor da adesão é usado para cobrir despesas com instalação, configuração e customização do sistema Synet do cliente.</em>

**O valor do código fonte depende da quantidade de módulos que será entregue no produto final. Aplica-se licença de redistribuição ou revenda**


Caso não haja o interesse em adiquirir o código fonte ou a versão na nuvem, nós ainda disponibilizamos os módulos separadamente em nosso repositório no github, totalmente gratuíto.

Para testar o sistema online, acesse esse [link](https://synet.review/system/)

Para doações por favor enviar bitcoin para o endereço: `1N4ukayY7vuyxJyGQuJkKjymamjUeXLBaa`
ou PayPal para o email: `deepcell@gmail.com`
