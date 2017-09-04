# Synet

## Sistema Synet

O sistema foi desenvolvido para ser usado na web apenas.

- Gestão de Clientes
    Cadastro de clientes.
    Ativação e Desativação de Clientes.
    Painel de Gerenciamento de Clientes.
    Central do Cliente. (Area dedicada ao acesso do cliente)
        Gera segunda via de boletos
        visualizar histórico financeiro
        solicitar alteração de dados cadastrais
    Multiplos Contratos
    Google Maps com a localização do endereço de instalação do contrato do cliente.


- Central de Revendas
    cadastre revendedores
    Revendedor tem acesso único a central de revendas, controlando seus proprios clientes.

- Agenda
    Crie entradas na agenda toda vez que uma nova ordem de serviço for criada.

- Ordem de Serviço
    Abertura de chamados de ordem pelo cliente via Central do Cliente ou via telefone.
    Impressão de ordem de serviço para o técnico

- Cadastro de Planos
    Cadastro de perfil de plano (categoria)
    cadastro dos planos

- Pagamento
    Boleto Bancário
    Gateways (via API, fácil e rápido de implementar)
    Cielo (pendente de homologação - cada empresa deve homologar o seu - homologamos por R$ 600,00)

- Bloqueio e Desbloqueio de Clientes
    Bloqueio automático de clientes inadimplentes.
    Desbloqueio automático baseado na baixa de pagamentos via boleto (pendente automatizar a baixa de pagtos via cartão).


- Financeiro
    Billing Completo (Internet)
    Contas a Pagar e Receber
    Fluxo de Caixa e Conciliação Bancária
    NF Modelo 21 (arquivo tem limite de 990 item por doc fiscal, inicio em .001)

- Cobrança
    Cartas de Cobrança via email e correio tradicional (SPC, Jurídico, primeiro aviso, segundo aviso, etc..)

- Servidores e Rede
    Integrado com a rede mikrotik.
    Integrado com a rede BFW3.
    Pode ser facilmente integrado com outras redes e servidores.

- Estoque
    controle de patrimonio.
    relatorio de items no estoque.
    transferencia de items de um estoque para outro (almoxarifados diferentes)

- Relatórios
    bloqueios
        Bloqueados pelo sistema (inadimplencia)
        bloqueados a pedido do cliente
    estatísticas (Gráficos)
        Equipamentos por Torre
        Assinantes por Planos
        Ordem de Serviço
    contas
        boletos emitidos
    logs
        logs de acesso
    anatel
        SICI - Sistema de Coleta de Informações (ANATEL)

- Backup
    backup automatico do banco de dados (via cronjobs)


- Mais Informações
    Clientes ilimitados (versão na nuvem esta limitado para no máximo 600 clientes)
    Rádios e RB ilimitados.
    Importamos o seu banco de dados por R$ 300,00


- Ambiente de Instalação
    Servidor Linux Debian 8 x64 (Jessie), PHP versão 5.3+, MySQL 5.5+, Python, Nginx 1.10+ ou Apache 2.2.2+



## Custo de um software alternativo no mercado
  Cerca de R$ 300,00 mensal + valor de adesão (R$ 600,00 ~ R$ 1000,00) para o primeiro ano.
	Por Ano: R$ 4.160,00 (R$ 20.160,00 - 6 anos)
	Por Ano: R$ 9.400,00 (R$ 50.400,00 - 6 anos)


## Preco Final do sistema Synet (codigo fonte e banco de dados mysql incluso)
	Entre R$ 68.000,00 ~ R$ 86.000 (depende dos modulos incluídos)
  ou
	Sistema na nuvem para gerenciar até 600 clientes por R$ 180,00 /mês (inclui: gerador de NF de Serviços Mod. 21)
