# Atividade mapeado o domínio

## Quais as entidades de domínio?
R: Produto, Estoque, Histórico de Vendas, Ordem de Compra, Fornecedor

## Quais as ações (casos de uso) que essa aplicação deve ter?
R:
- Rastreamento Individual de Produto:
  - Atribuir número de identificação único a cada produto.
  - Adicionar informações extras (como tamanho e cor) para cada produto.

- Definição de Quantidades Mínimas de Estoque:
  - Definir um limite mínimo de estoque para cada produto.
    
- Recebimento de Alertas de Estoque Baixo:
  - Enviar alertas por e-mail.
  - Enviar notificações no sistema de gerenciamento de estoque.
    
- Visualização de Histórico de Vendas e Estoque:
  - Visualizar quantidade de produtos vendidos em um período.
  - Visualizar lucro gerado por produto.
  - Identificar produtos mais vendidos em cada período.
  - Observar tendências de estoque ao longo do tempo.
    
- Criação e Gerenciamento Automático de Ordens de Compra:
  - Criar ordens de compra automaticamente com base nas quantidades mínimas de estoque e nas tendências de vendas.
    
- Integração com Fornecedores:
  - Receber atualizações automáticas sobre os prazos de entrega de novas remessas.
