# 💸 App de Gestão Finceira e Comercial com Vibe Coding

## Contexto e Problema
Muitos pequenos negócios, especialmente lojas de roupas infantis e microempreendedores individuais (MEIs), enfrentam dificuldades para controlar entradas e saídas de dinheiro. A ausência de ferramentas simples de gestão financeira compromete o fluxo de caixa e a tomada de decisões, dificultando o crescimento sustentável.

## Público-Alvo
- MEIs (Microempreendedores Individuais)
- Pequenos negócios locais que precisam de uma solução prática e acessível para organizar suas finanças.

## Objetivo do Produto
Oferecer um aplicativo simples e intuitivo que permita ao empreendedor:
- Registrar clientes e suas compras.
- Controlar recebimentos e pagamentos.
- Acompanhar o fluxo de caixa de forma clara.
- Facilitar a tomada de decisão com relatórios básicos e personalizados.

## Princípio de Design Universal
A solução será desenvolvida com base em Design Universal, garantindo:
- Acessibilidade: interface clara, com contraste adequado, fontes legíveis e navegação intuitiva.
- Inclusão: suporte para diferentes perfis de usuários, independentemente de idade, nível de escolaridade ou familiaridade com tecnologia.
- Experiência consistente: funcionamento fluido em diferentes dispositivos (smartphones, tablets, computadores).
- Usabilidade ampliada: recursos pensados para reduzir barreiras e permitir que o máximo de pessoas utilize o aplicativo com facilidade.

## Funcionalidades-Chave
1. Cadastro de clientes
   - Informações: nome, CPF, telefone, endereço.
   - Possibilidade de editar e excluir registros.
2. Classificação automática de transações
   - Diferenciar entradas (recebimentos) e saídas (pagamentos).
   - Categorizar por tipo (ex.: venda, despesa fixa, compra de estoque).
3. Registro de entradas e saídas de numerário
   - Inserção manual de valores.
   - Histórico de movimentações.
4. Gestão de saldos de clientes
   - Atualização automática do saldo devedor conforme compras e pagamentos.
   - Visualização individual por cliente.
5. Relatórios simples e personalizados
   - Fluxo de caixa (diário, semanal, mensal).
   - Relatório de clientes (inadimplentes, ativos).
   - Exportação em formato básico (PDF ou Excel).

## Plano de MVP (Produto Mínimo Viável)

### Principais Telas
- Tela de Login/Cadastro: acesso seguro ao sistema.
- Dashboard inicial: visão geral do fluxo de caixa.
- Cadastro de clientes: formulário simples.
- Registro de transações: entradas e saídas.
- Relatórios básicos: fluxo de caixa e clientes.

### Recursos Necessários
- Banco de dados simples (SQLite ou Firebase).
- Interface amigável e acessível (mobile-first, com princípios de Design Universal).
- Funções básicas de CRUD (Create, Read, Update, Delete).
- Algoritmo simples para classificação de transações.

### Validação Inicial
- Testar com 5 a 10 pequenos empreendedores locais.
- Coletar feedback sobre:
  - Facilidade de uso.
  - Clareza dos relatórios.
  - Utilidade do controle de clientes e fluxo de caixa.
  - Inclusão e acessibilidade da interface.
- Ajustar funcionalidades conforme necessidades reais.

## Tom Educativo
Este aplicativo será construído com foco em simplicidade, acessibilidade e inclusão, permitindo que qualquer empreendedor, mesmo sem experiência em tecnologia, consiga utilizá-lo para organizar suas finanças. O MVP deve ser enxuto, mas funcional, garantindo que o usuário perceba valor logo nos primeiros usos.


Resultado final no lovable: link >> https://vitrine-contabil.lovable.app/

<img width="1896" height="897" alt="image" src="https://github.com/user-attachments/assets/1dc6e63f-ad4a-438e-9e98-803821fbc946" />
<img width="1906" height="916" alt="image" src="https://github.com/user-attachments/assets/733c256f-891d-4014-b1dd-9f6d3408f8d2" />

### Resumo

O site “GestãoFácil – Controle Financeiro para MEI” oferece relatórios de fluxo de caixa, análise de entradas e saídas, categorização de transações e visão consolidada de clientes, ajudando pequenos negócios a acompanhar sua saúde financeira.

# Resumo das funcionalidades principais do site de relatórios

## Análise do negócio por período
- Exibe resultados consolidados do mês atual.
- Permite exportar relatórios para acompanhamento externo.

## Fluxo de caixa detalhado
- Mostra o total de entradas (R$ 4.529,50) e saídas (R$ 2.300,00).
- Calcula automaticamente o resultado líquido (R$ 2.229,50).

## Entradas por categoria
- Exemplo: Vendas (R$ 429,50) e Recebimentos (R$ 100,00).
- Facilita identificar quais fontes geram maior receita.

## Saídas por categoria
- Exemplo: Despesas fixas (R$ 800,00) e compra de estoque (R$ 1.500,00).
- Ajuda a visualizar onde estão os maiores gastos.

## Relatórios de clientes
- Permite acompanhar movimentações e saldos relacionados a clientes.
- Apoia na gestão de inadimplência e relacionamento.

## Integração com outras áreas do sistema
- Links diretos para Dashboard, Clientes, Produtos, Vendas, Transações e Configurações.
- Cria uma visão integrada da gestão financeira.

---
O módulo de relatórios do **GestãoFácil** é voltado para MEIs e pequenos negócios, oferecendo uma visão clara e acessível das finanças. Ele combina simplicidade com organização por categorias, permitindo que o empreendedor entenda rapidamente o desempenho do negócio e tome decisões mais informadas.

- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
  O refinamento feito do PRD no copilot ajudou bastane a não consimir todo os creditos. 
  - O que não funcionou como o esperado?
  Os dados criados pelo sistema sao apenas simulados e não atualiza quando inserimos novos dados por não ser salvos em nunhum banco de dados, o que seria resolvido se habilitasse o lovable cloud.   
  - O que aprendeu sobre conversar com IAs?
  Aprendi que quanto mais detalhadas e precisas as informaçoes, nos será devolvido um resultado melhor.

