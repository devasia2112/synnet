## Sistema Synet

O sistema encontra-se em constante desenvolvimento e atualização e pode ser ofereçido como serviço na web ou instalado localmente em um servidor web.
A seguir segue um resumo das principais funcionalidades já desenvolvidas e em estágio de desenvolvimento.

- Painel de Controle com estatísticas em tempo real.
- Administração
    - Cobrança
        - Cartas de Cobrança via email e correio tradicional (SPC, Jurídico, primeiro aviso, segundo aviso, etc..)
    - Contas
        - Entradas (Cadastro e Contas Atrasadas)
        - Saídas (Cadastro, Contas Atrasadas, Contas Essenciais e Contas por Fornecedores)
        - Bancos (Conta Corrente, Conta Poupança e Conta Cobrança para Emissão de Boletos)
        - Centro de Custo
        - Fluxo de Caixa e Conciliação Bancária
    - Empresa
        - Dados da Empresa
            - Cadastro da Empresa
            - Administração dos Dados de Cadastro da Empresa
        - Sede da Empresa
            - Cadastro de Sede da Empresa
            - Administração dos Dados de Cadastro da Sede da Empresa
        - Setor
            - Cadastro de Setor
            - Administração dos Dados do Setor
        - Cargo
            - Cadastro de Cargo
            - Administração de Dados de Cargos
        - Fiscal
            - Dados de Clientes (Exportar PF e PJ)
            - Dados de Produtos (Exportar)
            - [Dados NFSC Mod. 21](https://github.com/deepcell/Nfsc21) (Gerador dos Arquivos e Consulta das NFSC já Geradas - arquivo tem limite de 990 item por doc fiscal, inicio em .001)
            - Dados NF-e (Gerador e Consulta)
            - Dados NFS-e (Gerador e Consulta via API da eNotas Gateway)
    - Gestão de Clientes
        - Cadastro de clientes.
        - Consulta e Administração Geral de Clientes.
        - Ativação e Desativação de Clientes.
        - Central do Cliente. (Area dedicada ao acesso do cliente)
        - Gerar segunda via de boletos
        - Visualizar histórico financeiro
        - Solicitar alteração de dados cadastrais
        - Multiplos Contratos
        - Google Maps com a localização do endereço de instalação do contrato do cliente.
    - Gestão de Fornecedores
        - Cadastro de Fornecedores
        - Adminstração de Fornecedores
    - Gestão de Funcionários
        - Cadastro de Funcionários
        - Adminstração de Funcionários
    - Gestão de Veículos
        - Cadastro de Veículos
        - Adminstração de Veículos
    - Central de Revendas
        - Cadastrar Revendedores
        - Revendedor tem acesso único a central de revendas, controlando seus proprios clientes.
    - Cadastro de Serviços e Planos
        - Cadastro de Serviços
        - Cadastro de perfil de plano (categoria)
        - cadastro de planos
        - Administração de Serviços e Planos
- Operacional
    - Suporte
    - Agenda
        - Crie entradas na agenda toda vez que uma nova ordem de serviço for criada.
    - Ordem de Serviço
        - Abertura de chamados de ordem pelo cliente via Central do Cliente ou via telefone.
        - Impressão de ordem de serviço para o técnico
    - Orçamento
    - Tools
        - Endereço de Instalação de Contratos mostrados no google mapas.
    - Equipamento
        - Cadastro de Equip.
        - Administração de Equip.
        - Consulta de Transceptor
        - Administração de Equip. na Oficina
    - Estação
        - Cadastro de Estação
        - Administração de Estação
    - Torre
        - Cadastro de Torre
        - Administração de Torre
    - Transceptor
        - Cadastro de Transceptor
        - Administração de Transceptor
        - Indexar Transceptor com Torre
    - Servidor
        - Tipo de Servidor
            - Cadastro e Administração
        - Servidor
            - Cadastro e Administração
        - Range de IP
            - Cadastro e Administração
        - Servidor BFW (v2)
            - Cadastro e Administração de White List
        - Servidor BFW (v3)
            - Cadastro e Administração do SQUID(prebloqueio)
            - Cadastro e Administração QoS
            - Cadastro e Administração Reserve
        - Servidor BFW (Execuções: Gerar, Mover e Recarregar Arquivos)
        - [Servidor Mikrotik (API)](https://github.com/deepcell/Mikrotik)

- Inventário
    - Estoque
        - Entrada 
        - Sada
        - Consulta por Local
        - Transferência de Estoque de um local para outro
        - Depósito
            - Cadastrar
            - Consultar
    - Produto
        - Consultar
    - Pedidos

- Usuário e Grupos
    - Grupos de Acesso
        - Cadastrar
        - Administrar
        - Consultar
        - Atribuir Grupos a Usuários
    - Usuários
        - Senhas
        - Contas Bancárias (Usado com a Folha de Pagamento de Funcionários)
    - Perfil do Usuário (Funcionário)
    - Bloqueio de Tela (Desbloqueio com Senha)

- Relatórios
    - Rentabilidade
    - Financeiro
    - Ganhos
    - Comissões
    - Bloqueios
        - por Cliente
        - por parte da Empresa
            - Pré-Bloqueio
            - Bloqueio
            - Bloqueio automático de clientes inadimplentes.
            - Desbloqueio automático baseado na baixa de pagamentos via boleto (pendente automatizar a baixa de pagtos via cartão).

    - Contratos
    - Estoque
    - Ordem de Serviço
    - Pedidos
    - Estatísticas
    - Contas Bancárias
    - Logs
    - ANATEL (Relatório SICI - Sistema de Coleta de Informações)

- Configurações
    - Painel de Controle
    - Tarefas Agendadas
    - Atividade de Conta
    - Meus Logs do Sistema
    - Informaçes do Servidor
    - Servidor Radius
    - Backup
        - backup automatico do banco de dados (via cronjobs)

- Auto Ajuda
    - F.A.Q.
    - Material de Apoio (Videos)



*** Meios de Pagamento
    - Homologação de Boleto Bancário direto com o Banco (Homologamos por R$ 600,00)
    - Boletos via Gateways (via API, fácil e rápido de implementar - sem custo adicional)
    - Homologação de Cartão de Crédito via Cielo (Homologamos por R$ 600,00)


- Mais Informações
    - Clientes ilimitados
    - Rádios e RB ilimitados.
    - Importamos o seu banco de dados por R$ 350,00


- Ambiente de Instalação
    - Servidor Linux Debian 8 x64 (Jessie), PHP versão 5.3+, MySQL 5.5+, Python 2.7+, Nginx 1.10+ ou Apache 2.2.2+



#### Custo de um software alternativo no mercado.

| Software      | Mensal   | Anual  | Adesão           |
| ------------- | -------- | ------ | ----------------:|
| Mercado       | R$300    | R$3600 | R$ 600 ~ R$ 1000 |

<em>Adesão no primeiro ano apenas.</em>


#### Preco Final do sistema Synet (código fonte e banco de dados mysql incluso)

| Software      | ~~Mensal~~   | Anual  | Adesão          | **Source Code**     |
| ------------- | ------------ | ------ | --------------- | ------------------- |
| Synet         | R$180        | R$2160 | R$600           | R$70.000 ~ R$86.000 |

~~Sistema na nuvem para gerenciar até 600 clientes (inclui todos os módulos, inclusive o gerador de NF de Serviços Mod. 21)~~

<em>Adesão no primeiro ano apenas, o valor da adesão é usado para cobrir despesas com instalação, configuração e customização do sistema Synet do cliente.</em>

**O valor do código fonte depende da quantidade de módulos que será entregue no produto final. Aplica-se licença de redistribuição ou revenda**


Caso não haja o interesse em adiquirir o código fonte completo, alguns modulos estao disponiveis separadamente no repositório, totalmente gratuíto, porem como os modulos foram sendo desenvolvidos em momentos diferentes, vai precisar de atualização para que eles funcionem de forma integrada.

No momento estou trabalhando para disponibilizar uma versão open source e um servidor para testes.

Para doações por favor enviar: 
- Bitcoin: `39fNfmdJEL77CLuYXe3WzTgeYbF346LE9i`
- Dogecoin: `DP6jE9QfJYDnW9fLp6YWdzudo6TKLYbUnU`
- Litecoin: `LL5DKT63SQngT2j1az8EV7fpikgAxMTbqk`
- Zcash: `t1Ma3hV7mNMR3Npp8eGeZzq1G2amdpAPuxg`
- Monero: `4828JWzwtXtMYesdzsGv3WEgFobS9VPTyd6rpo86eMrCa9P7A8RXcKjHDoEjhHFRW27tAZMd7ks2dW76wnxsZs6DNmmBQue`
- Zcoin: `a32UsRrGM5q9m6g8D4z9AtDPLCEoJxAdHw`
- PayPal email: `deepcell@gmail.com`
