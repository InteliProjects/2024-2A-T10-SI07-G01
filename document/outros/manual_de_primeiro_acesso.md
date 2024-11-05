# Manual de Primeiro acesso
## Integrantes do Grupo Hermes

Este manual foi desenvolvido pelos seguintes membros do Grupo Hermes:

- [Celine Souza](https://www.linkedin.com/in/celine-souza-1a38aa225?trk=blended-typeahead)
- [Eduardo Henrique Oliveira](https://www.linkedin.com/in/eduardo-hos/)
- [Marcelo Sitton](https://www.linkedin.com/in/marcelo-sitton-878248271?trk=blended-typeahead)
- [Paulo Octavio De Paula](https://www.linkedin.com/in/paulooctaviodepaula?trk=blended-typeahead)
- [Pedro Faria](https://www.linkedin.com/in/pedro-faria-santos-10b4061b7/)
- [Pedro Henrique Lima](https://www.linkedin.com/in/pedrohenrique-oliveira-lima/)
- [Thiago Goulart](https://www.linkedin.com/in/thiago-goulart-de-oliveira?trk=blended-typeahead)

Cada membro contribuiu com seu conhecimento e expertise para a elaboração deste manual de configuração do SAP Business One.
## Sumário

[Índice de Figuras](#índice-de-figuras)

[1.0 Introdução](#10-introdução)

[1.1 Configurações Específicas do Módulo de Vendas](#11-configurações-específicas-do-módulo-de-vendas)

[1.2 Configurações Detalhadas](#12-configurações-detalhadas)

- [1.2.1 Informações Básicas da Empresa](#121-informações-básicas-da-empresa)
- [1.2.2 Configurações Gerais da Empresa](#122-configurações-gerais-da-empresa)
- [1.2.3 Plano de Contas](#123-plano-de-contas)
- [1.2.4 Informações Bancárias](#124-informações-bancárias)
- [1.2.5 Determinação da Conta Contábil](#125-determinação-da-conta-contábil)
- [1.2.6 Centros de Custo](#126-centros-de-custo)
- [1.2.7 Despesas](#127-despesas)
- [1.2.8 Depósitos](#128-depósitos)
- [1.2.9 Grupos de Itens](#129-grupos-de-itens)
- [1.2.10 Impostos](#1210-impostos)
- [1.2.11 Condições de Pagamento](#1211-condições-de-pagamento)
- [1.2.12 Cartões](#1212-cartões)
- [1.2.13 Usuários e Senhas](#1213-usuários-e-senhas)
- [1.2.14 Tipos de Envio](#1214-tipos-de-envio)
- [1.2.15 Configuração do Documento](#1215-configuração-do-documento)

[1.3 Conclusão Geral](#13-conclusão-geral)

## Índice de Figuras
- Figura 1 - Configurações Específicas do Módulo de Vendas
- Figura 2 - Configurações Gerais da Empresa
- Figura 3 - Plano de Contas
- Figura 4 - Informações Bancárias
- Figura 5 - Determinação da Conta Contábil
- Figura 6 - Centros de Custo
- Figura 7 - Despesas
- Figura 8 - Depósitos
- Figura 9 - Grupos de Itens
- Figura 10 - Impostos
- Figura 11 - Condições de Pagamento
- Figura 12 - Cartões
- Figura 13 - Usuários e Senhas
- Figura 14 - Territórios
- Figura 15 - Grupos de Comissão
- Figura 16 - Vendedores
- Figura 17 - Níveis de Vendas
- Figura 18 - Grupos de Clientes
- Figura 19 - Grupos de Fornecedores
- Figura 20 - Usuários
- Figura 21 - Níveis de Compra
- Figura 22 - Tipos de Envio
- Figura 23 - Configuração do Documento

# 1.0 Introdução

Esta seção contém capturas de tela que ilustram as configurações iniciais do [Business Blueprint](https://docs.google.com/spreadsheets/d/17h9jbzN-kycmq2ROnW8qaJH_fN3VUC2H/edit?usp=sharing&ouid=114656974096315700212&rtpof=true&sd=true) fornecido pela empresa G2, que são os dados mestres. Cada imagem está alinhada com a seção correspondente do BBP. Veja as configurações a seguir. 

## 1.1 Configurações Específicas do Módulo de Vendas

Nesta subseção, o grupo *Hermes* abordou as configurações detalhadas realizadas no módulo de vendas, seguindo as diretrizes estabelecidas no *Business Blueprint* (BBP) da *G2 Tecnologia*. As configurações foram ajustadas para atender às particularidades do cliente, garantindo uma gestão eficiente das operações de vendas e o cumprimento das exigências contábeis e fiscais. A seguir, apresenta-se as principais configurações implementadas, acompanhadas de descrições e capturas de tela que ilustram o processo.

### 1.1.1 Determinação de Conta Contábil - Vendas

As contas contábeis foram configuradas de acordo com o *BBP (Business Blueprint)* fornecido pela empresa. O mapeamento de contas abrange categorias como contas a receber, adiantamentos, variações cambiais e juros, garantindo que todas as operações de vendas sejam devidamente registradas e controladas conforme os requisitos contábeis e fiscais estabelecidos para o ano de 2024.

<div align="center">
<p><b>Figura 1</b> - Determinação de Conta Contábil - Vendas</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_Vendas_xzccry.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_Vendas_xzccry.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Seleção do Período:* 2024
    - Assegura que as transações de vendas deste ano sejam devidamente contabilizadas.
- *Contas a Receber:* Conta contábil padrão para operações de recebimento de clientes.
- *Cliente padrão para nota fiscal de saída e pagamento:* Não configurado.
- *Permitir modificação das contas controle:* Ativado.

### 1.1.2 Determinação de Conta Contábil - Geral

As contas contábeis foram configuradas para atender às necessidades gerais da empresa, assegurando que as transações comuns, como ajustes de estoque, variações de preço e compensações, estejam devidamente categorizadas. O mapeamento de contas inclui alocações para compensações de mercadorias, ajustes de inventário e outras operações essenciais para o controle financeiro.

<div align="center">
<p><b>Figura 2 </b> - Determinação de Conta Contábil - Geral</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_geral_fxzohu.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_geral_fxzohu.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Seleção do Período:* 2024
- *Conta de Estoque:* Mercadorias para Revenda
- *Conta de Custo de Produtos Vendidos:* Custo das Mercadorias Revendidas
- *Conta de Alocação:* Variação do Custo Médio
- *Conta de Ajuste de Estoque Negativo:* Ajuste de Inventário
- *Conta de Material em Processo:* Importação em Andamento

### 1.1.3 Exemplo de Configuração de Grupo de Itens

Esta configuração define grupos de itens e seus respectivos métodos de planejamento, fornecimento e avaliação. A categorização dos itens é essencial para o controle adequado de estoque e para o cálculo correto dos custos de produção.

<div align="center">
<p><b>Figura 3</b> - Exemplo de Configuração de Grupo de Itens</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724376581/config-grupo-itens_qc94tg.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724376581/config-grupo-itens_qc94tg.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Grupo de Itens:* Itens
- *Método de Planejamento:* Nenhum
- *Método de Suprimento:* Comprar
- *Método de Avaliação Padrão:* Preço médio móvel
- *Classificação de Itens p/ Impostos:* Material
- *Tipo de Material:* Matéria-Prima
- *Fonte do Produto:* Nacional, exceto as indicadas nos códigos 3 a 5

### 1.1.4 Condição de Pagamento

As condições de pagamento foram definidas para garantir flexibilidade e segurança nas transações comerciais, com prazos de pagamento bem estabelecidos e métodos de pagamento alinhados às práticas da empresa.

<div align="center">
<p><b>Figura 4</b>- Condição de Pagamento</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724376862/exemplo-confição-de-pagamento_yvzmrg.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724376862/exemplo-confição-de-pagamento_yvzmrg.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Código da Condição de Pagamento:* 217
- *Data de Vencimento Baseada em:* Data do documento
- *Dias de Tolerância:* 256
- *Número de Prestações:* 1
- *Contas a Receber em Aberto:* Transferência bancária

### 1.1.5 Cartão de Crédito

O s cartões de crédito foram configurados com contas específicas para controle e registro das despesas associadas, permitindo uma gestão financeira mais eficaz.]

<div align="center">
<p><b>Figura 5</b> - Cartão de Crédito</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724377363/definicao-cartao-credito_nxjpdb.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724377363/definicao-cartao-credito_nxjpdb.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Cartão de Crédito:* Itaú - Mastercard (G2-Beto)
- *Conta do Razão:* 1.01.01.02.04
- *Identificação da Empresa:* G2 Informática Ltda

### 1.1.6 Definição de Territórios

Os territórios foram configurados para refletir a organização geográfica da empresa, facilitando a gestão das operações de vendas e a alocação de recursos de acordo com as regiões.

<div align="center">
<p><b>Figura 6</b> - Definição de Territórios</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724377682/territorios_f3yvs8.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724377682/territorios_f3yvs8.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Território:* Pernambuco
- *Território Superior:* Nordeste
- *Ordem do Local:* Último

### 1.1.7 Definição de Vendedores/Compradores

A configuração dos vendedores e compradores foi realizada para permitir um controle eficiente das comissões e das atividades comerciais, assegurando que cada colaborador esteja devidamente registrado e com suas informações atualizadas.

<div align="center">
<p><b>Figura 7</b> - Definição de Vendedores/Compradores</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724377774/vendedores-compradores_iwg524.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724377774/vendedores-compradores_iwg524.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Vendedor/Comprador:* Diversos
- *Grupo de Comissões:* Network
- *% da Comissão:* 25%

### 1.1.8 Níveis de Venda

Os níveis de venda foram definidos para estruturar o processo de vendas, com etapas claras e porcentagens de conclusão associadas, ajudando na previsão e acompanhamento das oportunidades de negócio.

<div align="center">
<p><b>Figura 8</b> - Níveis de venda</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724378031/niveis-de-venda_e33gdd.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724378031/niveis-de-venda_e33gdd.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Nível:* Telefomema
- *Número da Etapa:* 1
- *Porcentagem Final:* 5%

## 1.2 Configurações Gerais do Sistema

Nesta subseção, são apresentadas as configurações gerais do sistema feitas pelo grupo *Hermes*, a fim de garantir que o ambiente ERP esteja alinhado com as necessidades operacionais e regulamentares da empresa.

### 1.2.1 Contas Bancárias da Empresa

As contas bancárias da empresa foram configuradas para garantir que todas as transações financeiras sejam registradas de forma precisa, com contas específicas para cada banco e controle de cheques. Esta configuração é essencial para a reconciliação bancária, permitindo um controle eficaz do fluxo de caixa e garantindo a precisão dos registros contábeis.

<div align="center">
<p><b>Figura 9</b> - Contas Bancárias da Empresa</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724375029/ContasBancariasDaEmpresa_u0yq0e.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724375029/ContasBancariasDaEmpresa_u0yq0e.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome da Conta Bancária:* Diversos (Banco do Brasil, Santander, Bradesco, Itaú)
    - As contas bancárias foram configuradas para incluir várias instituições financeiras, cada uma com suas especificações.
- *Código do Banco:* Diversos
    - O código do banco foi inserido para cada conta, facilitando a identificação e a integração com o sistema bancário.
- *Número da Conta:* Variado conforme o banco
    - Os números de conta foram devidamente registrados para garantir a exatidão das transações financeiras.
- *Conta do Razão:* 1.01.01.02.04 (para contas da G2 Análise)
    - A conta do razão para essas contas bancárias foi configurada para centralizar as transações, assegurando clareza nos relatórios financeiros.

### 1.2.2 Detalhes da Empresa - Inicialização Básica

As configurações básicas da empresa foram estabelecidas para definir os parâmetros iniciais do sistema, incluindo a moeda padrão, modelo de plano de contas, e outros detalhes cruciais para o funcionamento do ERP. Essas configurações asseguram que o sistema esteja alinhado com as necessidades operacionais e regulamentares da empresa, permitindo uma operação eficiente e conforme as normas locais.

<div align="center">
<p><b>Figura 10</b> - Detalhes da empresa Inicialização Básica</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724346913/DetalhesDaEmpresaBasico_ues5s3.jpg"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724346913/DetalhesDaEmpresaBasico_ues5s3.jpg" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Modelo do Plano de Contas:* BR_CoA
    - O plano de contas foi configurado de acordo com os padrões contábeis brasileiros, essencial para a conformidade com as normas fiscais.
- *Moeda do Sistema:* Real
    - O Real foi definido como a moeda padrão para todas as transações, garantindo consistência e facilidade de cálculo.
- *Suporte Multilíngue:* Ativado
    - A funcionalidade multilíngue foi ativada para suportar operações internacionais e atender a uma base de usuários diversificada.
- *Utilizar Estoque Permanente:* Ativado
    - A opção de estoque permanente foi habilitada para garantir um controle contínuo e preciso dos níveis de estoque, utilizando o método de avaliação do preço médio móvel.

### 1.2.3 Configurações do Documento Geral

As configurações do documento geral foram estabelecidas para definir como os documentos de venda, compra e outros documentos operacionais serão geridos no sistema. Estas configurações asseguram que os processos sigam os padrões estabelecidos pela empresa, facilitando a administração de transações e garantindo a conformidade com as práticas internas.

<div align="center">
<p><b>Figura 11</b> - Configurações do Documento Geral</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/ConfiguraçõeDocumentoGeral_jvtvwh.jpg"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/ConfiguraçõeDocumentoGeral_jvtvwh.jpg" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Calcular Lucro Bruto:* Ativado
    - Esta configuração permite que o sistema calcule automaticamente o lucro bruto das transações, facilitando a análise financeira.
- *Origem do Preço Base:* Último preço de compra
    - O preço base utilizado para cálculos é o último preço de compra registrado, assegurando que o custo mais recente seja considerado nas transações.
- *Método de Arredondamento:* Por moeda
    - As transações são arredondadas de acordo com a moeda utilizada, garantindo consistência e precisão nos registros financeiros.

### 1.2.4 Moedas

A configuração das moedas foi realizada para definir as principais moedas utilizadas pela empresa nas suas transações. Isso garante que todas as operações financeiras possam ser realizadas de forma precisa e conforme as taxas de câmbio aplicáveis, permitindo a conversão e o registro correto das transações internacionais.

<div align="center">
<p><b>Figura 12</b> - Moedas</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/Moedas_suvf2g.jpg"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/Moedas_suvf2g.jpg" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Código da Moeda:* Diversos (CAN, EUR, R$, USD)
    - As principais moedas foram configuradas no sistema, abrangendo Dólar Canadense, Euro, Real e Dólar Norte-Americano.
- *Descrição Internacional:* Nome das moedas conforme padrão internacional (Dólar Canadense, Euro, Real, Dólar Norte Americano)
    - Cada moeda foi registrada com sua descrição internacional para garantir clareza nas transações.
- *Centésimo Nome:* Centavo
    - A nomenclatura para os centavos foi estabelecida, assegurando precisão nos cálculos e na apresentação dos valores.

### 1.2.5 Configurações Gerais PN

As configurações gerais do PN (Planejamento de Necessidades) foram estabelecidas para assegurar que todos os parâmetros para cálculos de necessidades e reabastecimento de materiais estejam configurados de acordo com as práticas operacionais da empresa. Isso é fundamental para manter o fluxo contínuo de materiais e evitar rupturas no estoque.

<div align="center">
<p><b>Figura 13</b> - Configurações Gerais PN</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724346913/ConfiguraçõesGeraisPN_phb6ie.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724346913/ConfiguraçõesGeraisPN_phb6ie.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Método de Administração:* Em todas as transações
    - O sistema aplica o método de administração de estoque em todas as transações, garantindo um controle abrangente e eficaz.
- *Depósito Padrão:* Depósito geral
    - Foi definido um depósito padrão onde os itens serão armazenados, facilitando o gerenciamento de inventário.
- *Importe Retido na Fonte:* Ativado
    - Configura a retenção de impostos na fonte, assegurando conformidade fiscal e simplificação dos processos de contabilidade.

### 1.2.6 Configurações Gerais Estoque

As configurações gerais de estoque foram configuradas para definir como os itens de inventário serão geridos, incluindo métodos de avaliação, unidade de medida padrão e outras especificações importantes para o controle de estoque. Estas configurações são essenciais para manter a precisão dos registros de inventário e otimizar o fluxo de materiais.

<div align="center">
<p><b>Figura 14</b> - Configurações Gerais Estoque</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/ConfiguraçõesGeraisEstoque_kbt9f5.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/ConfiguraçõesGeraisEstoque_kbt9f5.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Método de Avaliação:* Preço médio móvel
    - O preço médio móvel foi escolhido como método de avaliação para suavizar as flutuações de custo ao longo do tempo.
- *Unidade de Medida de Estoque:* Unidade de medida específica para controle de estoque.
    - Define a unidade de medida padrão a ser utilizada no controle de estoque, assegurando uniformidade nos registros.
- *Definir Método de Estoque por:* Depósito
    - O controle de estoque é gerido por depósito, permitindo uma visão detalhada e precisa da localização dos itens.

### 1.2.7 Configurações Gerais Exibir

As configurações de exibição determinam como os dados serão apresentados aos usuários no sistema, permitindo uma interface de usuário que seja eficiente e fácil de utilizar. Estas configurações são vitais para garantir que os usuários tenham acesso às informações necessárias de forma clara e organizada.

<div align="center">
<p><b>Figura 15</b> - Configurações Gerais Exibir</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/ConfiguraçõesGeraisExibir_oldauu.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724346912/ConfiguraçõesGeraisExibir_oldauu.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Exibir Itens Inativos:* Configurado para mostrar itens inativos no documento, garantindo que todas as opções estejam visíveis para o usuário, mesmo que inativas.
    - Esta configuração permite que os itens inativos ainda sejam visualizados no sistema, assegurando que todas as informações relevantes estejam acessíveis.

### 1.2.8 Configuração de Centro de Custos

A configuração dos centros de custos foi realizada para permitir o controle detalhado das despesas e receitas da empresa, dividindo-as em diferentes centros de custo. Isso facilita a análise financeira e a tomada de decisões estratégicas.

<div align="center">
<p><b>Figura 16</b> - Configuração de centro de custos</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724375887/centro-de-custos_iqxhtf.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724375887/centro-de-custos_iqxhtf.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Dimensão:* Departamento
    - Os centros de custos foram configurados por departamento, permitindo a atribuição precisa de custos e receitas.
- *Efetivo Desde:* 19/08/2024
    - As configurações estão em vigor desde 19 de agosto de 2024, assegurando que todos os lançamentos subsequentes sigam essas regras.
- *Regra de Distribuição:* Definida para cada centro de custo individualmente, permitindo a alocação precisa dos recursos.

### 1.2.9 Determinação de Conta Contábil - Compras

A determinação das contas contábeis para compras foi configurada para garantir que todas as transações de compras sejam registradas corretamente, assegurando a conformidade com os requisitos fiscais e contábeis.

<div align="center">
<p><b>Figura 17</b> - Determinação de Conta Contábil - Compras</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_Compras_gsgiej.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_Compras_gsgiej.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Conta de Arredondamento:* 4.01.02.01.06 - Arredondamento por Diferenças de Moeda
    - Conta utilizada para ajustes de arredondamento em transações de compras, assegurando precisão nos registros financeiros.
- *Conta de Encerramento do Período:* 6.02.02.01.01 - Resultado Final de Exercício
    - Esta conta é utilizada para fechar o período contábil, garantindo que todas as despesas e receitas sejam devidamente consolidadas.
- *Ganhos por Diferença de Câmbio:* 3.01.02.01.01 - Variações Cambiais Ativas
    - Conta destinada ao registro de ganhos provenientes de variações cambiais em transações internacionais.

### 1.2.10 Determinação de Conta Contábil - Estoque

A configuração das contas contábeis para estoque assegura que todas as movimentações de estoque sejam registradas de forma adequada, facilitando a gestão de inventário e a precisão nos relatórios financeiros.

<div align="center">
<p><b>Figura 18</b> - Determinação de Conta Contábil - Estoque</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_Estoque_uwe1j0.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724375512/Determinação_de_Conta_Contábil_-_Estoque_uwe1j0.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Conta de Estoque:* 1.01.01.01.01 - Mercadorias para Revenda
    - Conta responsável pelo registro do valor das mercadorias em estoque, essencial para o controle de inventário.
- *Conta de Ajuste de Estoque Negativo:* 5.03.01.01.03 - Ajuste de Inventário
    - Utilizada para ajustes de inventário, especialmente em situações onde o estoque está negativo, garantindo a precisão dos registros.
- *Conta de Variação de Preço:* 5.03.01.01.01 - Variação do Custo Médio
    - Conta destinada a registrar as variações no custo médio dos itens em estoque, assegurando que as flutuações de custo sejam contabilizadas corretamente.

### 1.2.11 Configuração de IRF

A configuração do IRF (Imposto Retido na Fonte) foi estabelecida para garantir que os impostos sejam devidamente retidos e registrados, em conformidade com as exigências fiscais.

<div align="center">
<p><b>Figura 19</b> - Configuração de IRF</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724376701/imposto-retino-fonte_yd2bpd.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724376701/imposto-retino-fonte_yd2bpd.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Categoria:* Entrada - Nota Fiscal
    - A categoria foi definida para entradas com base em notas fiscais, assegurando que os impostos sejam corretamente aplicados nas compras.
- *Taxa:* Variável conforme o tipo de imposto, como PIS, COFINS, IRRF, CSLL
    - As alíquotas foram configuradas de acordo com a legislação vigente, para diferentes tipos de impostos retidos.
- *Conta Contábil:* Diversas contas atribuídas para cada tipo de imposto, como PIS, COFINS, IRRF, CSLL
    - As contas contábeis específicas foram definidas para cada tipo de imposto, garantindo que os valores sejam corretamente alocados.

### 1.2.12 Cadastro de Usuário

O cadastro de usuários no sistema foi configurado para permitir o controle de acesso e atribuições de funções específicas, assegurando que cada colaborador tenha acesso somente às funcionalidades pertinentes ao seu papel.

<div align="center">
<p><b>Figura 20</b> - Cadastro de Usuário</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724377475/exemplo-cadastro-usuario_pajvhg.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724377475/exemplo-cadastro-usuario_pajvhg.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Código do Usuário:* g2014
    - Identifica o usuário pelo código g2014, facilitando o controle de acesso.
- *Nome do Usuário:* Bruna Oliveira
    - Nome da colaboradora associada ao código de usuário, garantindo que as transações sejam rastreáveis.
- *E-mail:* [bruna_oliv_sant@icloud.com.br](mailto:bruna_oliv_sant@icloud.com.br)
    - O e-mail de contato foi registrado para comunicação e notificações internas.
- *Departamento:* Geral
    - O usuário foi atribuído ao departamento Geral, permitindo acesso às funcionalidades relevantes.

### 1.2.13 Níveis de Compra

Os níveis de compra foram configurados para definir etapas específicas no processo de compras, permitindo um acompanhamento mais detalhado e preciso das transações, desde a solicitação até o fechamento.

<div align="center">
<p><b>Figura 21</b> - Níveis de Compra</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724377877/niveis-de-compra_ckz38y.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724377877/niveis-de-compra_ckz38y.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Nível:* Telefomema
    - Primeira etapa do processo de compras, onde o contato inicial com o fornecedor é realizado.
- *Número da Etapa:* 1
    - Definida como a primeira etapa no processo de compra.
- *Porcentagem Final:* 5%
    - A etapa de telefonema representa 5% do progresso total no processo de compras.

### 1.2.14 Tipos de Envio

A configuração dos tipos de envio foi realizada para categorizar os diferentes métodos de envio utilizados pela empresa, assegurando que os processos logísticos sejam geridos de maneira eficiente.

<div align="center">
<p><b>Figura 22</b> - Tipos de Envio</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724378171/tipos-de-envio_tvxtvz.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724378171/tipos-de-envio_tvxtvz.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Nome do Tipo de Envio:* CLOUD, LU ADDON, LU SAP, etc.
    - Vários tipos de envio foram configurados para cobrir diferentes parceiros e serviços, como CLOUD, LU ADDON, e LU SAP.
- *Web site:* Vários (Parceiros, SAP, Outros)
    - Cada tipo de envio foi associado a um website específico para facilitar a gestão de logística.
- *Ativo:* Ativado para todos os tipos de envio
    - Todos os tipos de envio configurados estão ativos, garantindo que possam ser selecionados para operações.

### 1.2.15 Configuração do Documento

As configurações de documentos foram definidas para garantir que todos os documentos gerados pelo sistema estejam em conformidade com as políticas internas da empresa, assegurando a precisão e a consistência nas transações.

<div align="center">
<p><b>Figura 23</b> - Configuração do Documento</p>
<a href="https://res.cloudinary.com/dmornatkl/image/upload/v1724378266/Configuração_de_Documento_vmppl5.png"><img src="https://res.cloudinary.com/dmornatkl/image/upload/v1724378266/Configuração_de_Documento_vmppl5.png" width="80%"></a>

<sup><b>Fonte:</b> Material produzido pelo Grupo Hermes (2024)</sup>
</div>

**Configurações Principais:**

- *Calcular Lucro Bruto:* Ativado
    - Configuração para calcular automaticamente o lucro bruto nas transações de venda.
- *Origem do Preço Base:* Último preço de compra
    - Define o último preço de compra como referência para cálculos de custo.
- *Observações dos Documentos:* Incluem observações manuais
    - As observações nos documentos incluem notas manuais para maior detalhamento.

## 1.3 Conclusão Geral

Nessa seção, foi apresentada de forma objetiva as principais configurações do Business Blueprint (BBP) para a empresa. O documento abrange uma ampla gama de temas para a implementação do sistema, organizados em tópicos detalhados:

1. **Informações Básicas da Empresa**: Configurações que incluem nome, endereço, dados de contato, informações contábeis e as preferências de moedas e métodos de avaliação de estoque.
2. **Configurações Gerais da Empresa**: Incluindo opções de alerta, condições de pagamento, formatos de data e hora, casas decimais, e métodos para números de série e lotes.
3. **Plano de Contas**: Especificações para o plano de contas, fornecido em formato Excel, que será usado para a contabilidade da empresa.
4. **Informações Bancárias**: Detalhamento das contas bancárias utilizadas pela empresa.
5. **Determinação da Conta Contábil**: Diretrizes para o lançamento de transações, divididas em vendas, compras, lançamentos gerais e estoque.
6. **Centros de Custo**: Definição e configuração das dimensões e centros de custo da empresa.
7. **Despesas**: Incluindo despesas de importação e adicionais.
8. **Depósitos**: Configuração dos depósitos que a empresa utilizará.
9. **Grupos de Itens**: Definição dos grupos de itens para o controle de estoque.
10. **Impostos**: Configuração detalhada de impostos, incluindo Imposto Retido na Fonte (IRF) e códigos de imposto.
11. **Condições de Pagamento**: Lista e configuração das condições de pagamento utilizadas.
12. **Cartões**: Informações e configurações detalhadas para o uso de cartões de crédito.
13. **Usuários e Senhas**: Definição dos usuários e suas credenciais.
14. **Territórios, Grupos de Comissão, Vendedores e Níveis de Vendas**: Configuração de territórios, grupos de comissão, vendedores e estágios de vendas.
15. **Grupos de Clientes e Fornecedores**: Definição dos grupos de clientes e fornecedores.
16. **Tipos de Expedição**: Configuração dos tipos de expedição utilizados pela empresa.
17. **Configurações Iniciais de Documento**: Parâmetros para as configurações iniciais de documentos em todo o sistema.

Assim, essas configurações são para assegurar que o sistema SAP Business One esteja adaptado às necessidades específicas da empresa, garantindo uma base para a sua operação.
## Dedicatória

Em homenagem à nossa jornada e ao espírito de perseverança que nos guiou, dedicamos este trabalho com as palavras inspiradoras de Guimarães Rosa:

> "O correr da vida embrulha tudo.
A vida é assim: esquenta e esfria,
aperta e daí afrouxa,
sossega e depois desinquieta.
O que ela quer da gente é coragem"
> 

Que estas palavras nos lembrem sempre da importância da coragem e da resiliência em nossa caminhada profissional e pessoal.