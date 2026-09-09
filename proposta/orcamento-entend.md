# Proposta — Entend
## Site institucional + loja virtual própria

| | |
|---|---|
| **Para** | Eugenie Néri — Entend |
| **De** | [SEU NOME / EMPRESA] |
| **Data** | 09 de setembro de 2026 |
| **Validade** | 30 dias (até 09/10/2026) |
| **Referência** | ENT-2026-09 |

---

## 1. Entendimento

Eugenie, o que você descreveu são duas frentes num projeto só:

1. **Renovar a presença institucional da Entend** — cursos, instrutores e marca,
   num site moderno, rápido e que funcione bem no celular.
2. **Abrir um canal de venda direta** — livraria e papelaria em loja virtual
   própria, vendendo para o público que já conhece e confia na Entend.

A segunda frente é a que muda o jogo: hoje a marca gera relacionamento e não
gera transação. Uma loja bem-feita transforma quem já acompanha os cursos em
comprador recorrente, sem depender de marketplace nem de comissão de terceiro.

A loja será **desenvolvida sob medida em Node.js com banco de dados próprio** —
não é tema alugado de plataforma. Isso significa mensalidade de plataforma zero,
liberdade total de regra de negócio e código que é da Entend. Em contrapartida,
exige um projeto de verdade, e é isso que este orçamento descreve.

**Uma ressalva de honestidade:** não consegui abrir o entend.com.br enquanto
montava esta proposta (bloqueio de rede do ambiente que usei). O escopo assume
construção do zero. Se o site atual tiver conteúdo, integrações ou posicionamento
no Google que valham a pena preservar, isso ajusta alguns itens — e é a primeira
coisa que reviso com você.

---

## 2. O relógio: dezembro

Duas sazonalidades da Entend caem no mesmo lugar: **papelaria vive de volta às
aulas** e **matrícula de curso concentra em janeiro e fevereiro**. Loja que nasce
em março perde as duas e espera doze meses pela próxima.

Para estar no ar, indexada no Google e pronta para receber tráfego em janeiro, o
alvo de lançamento é **início de dezembro de 2026**. De hoje até lá são cerca de
12 semanas, e o projeto leva 10. Cabe — com decisão fechada ainda em setembro.

Não é pressa de vendedor: é o único motivo pelo qual eu recomendaria começar
agora em vez de em janeiro.

---

## 3. Escopo

### 3.1 Site institucional
Design moderno e responsivo, cinco páginas:

- **Home** — proposta de valor, destaques de cursos e vitrine da loja
- **Quem Somos** — história, missão e diferencial da Entend
- **Instrutores** — perfis individuais, formação e áreas de atuação
- **Produtos / Cursos** — catálogo de cursos com página própria por curso
- **Contato** — formulário, mapa, WhatsApp e redes

Inclui: layout desenhado sob medida (não template), navegação e rodapé
completos, formulário com envio por e-mail e proteção antispam, páginas legais
(privacidade e termos) e banner de cookies para conformidade com a LGPD.

### 3.2 Loja virtual (livraria e papelaria)
Aplicação própria em **Node.js + banco de dados**, para **até 50 produtos**:

- Vitrine com categorias, destaques e produtos relacionados
- Busca e filtros por categoria, faixa de preço e disponibilidade
- Página de produto com galeria de imagens, descrição, estoque e variações
  (cor, tamanho, formato)
- Ficha específica para livro: autor, editora, ISBN, ano, edição e número de páginas
- Carrinho persistente, com atualização de quantidade e cálculo em tempo real
- Cadastro e login de cliente, com histórico de pedidos e rastreio

### 3.3 Checkout e pagamento
- Checkout em página única, otimizado para celular
- **Pix** com QR Code e confirmação automática
- **Cartão de crédito** com parcelamento
- Integração via **Mercado Pago ou Pagar.me** (definimos qual na Fase 1)
- Confirmação por webhook — o pedido só avança quando o pagamento é aprovado
- E-mails automáticos: pedido recebido, pagamento aprovado, pedido enviado
- Validação de endereço por CEP e checagem de estoque antes de fechar

### 3.4 Frete
- Cálculo por CEP via **API dos Correios** (ou Melhor Envio, conforme a Fase 1)
- Múltiplas modalidades com prazo e valor por opção
- Regras configuráveis de frete grátis (por valor de pedido ou região)
- Retirada na loja, se houver ponto físico

### 3.5 Painel administrativo
Área restrita, para a equipe operar sem depender de mim:

- **Produtos** — cadastro, edição, upload de imagens, categorias, variações
- **Estoque** — saldo por produto, baixa automática na venda, alerta de mínimo
- **Pedidos** — lista, busca, detalhe completo e histórico do cliente
- **Gestão de entrega** — mudança de status (recebido, em separação, enviado,
  entregue), inclusão de código de rastreio e notificação automática ao cliente
- **Usuários** — acessos com níveis de permissão
- Painel inicial com vendas do período, pedidos pendentes e produtos em falta

### 3.6 SEO e performance
- SEO técnico: títulos, meta descrições, URLs limpas, sitemap.xml e robots.txt
- Dados estruturados (Schema.org) para produto, curso e organização — é o que faz
  preço e disponibilidade aparecerem direto no resultado do Google
- Otimização mobile e de Core Web Vitals (imagens, carregamento, cache)
- Google Analytics 4 e Search Console configurados
- Redirecionamentos 301 do site atual, para não perder o que já está indexado

### 3.7 Entrega
- Testes em navegadores e aparelhos reais
- Compras de teste ponta a ponta, incluindo estorno
- Publicação, domínio, SSL e backup automático configurados
- Cadastro dos até 50 produtos iniciais
- Treinamento gravado da equipe + manual do painel
- **30 dias de acompanhamento pós-lançamento inclusos**

---

## 4. Investimento

| Módulo | Valor |
|---|---:|
| 1. Site institucional — 5 páginas, design e SEO | R$ 8.500 |
| 2. Loja: catálogo, busca e carrinho (até 50 produtos) | R$ 7.500 |
| 3. Checkout e pagamentos (Pix + cartão) | R$ 6.500 |
| 4. Cálculo de frete (Correios / API) | R$ 3.000 |
| 5. Painel administrativo e gestão de pedidos | R$ 9.000 |
| 6. Testes, publicação, treinamento e 30 dias de acompanhamento | R$ 3.500 |
| **Total** | **R$ 38.000** |

**Prazo: 10 semanas** a partir da assinatura.

### Se preferir dividir em duas etapas

Os módulos são independentes o suficiente para o site entrar no ar antes da loja:

| Etapa | Escopo | Valor | Prazo |
|---|---|---:|---|
| **Etapa 1** | Site institucional completo, no ar | R$ 8.500 | 3 a 4 semanas |
| **Etapa 2** | Loja, checkout, frete e painel | R$ 29.500 | + 6 a 7 semanas |

O valor total é o mesmo. A vantagem é ter presença nova mais cedo e diluir o
investimento; a desvantagem é uma semana a mais no total.

---

## 5. Opcionais

Ficaram fora do escopo inicial, como conversamos. Preços firmes, caso queira
incluir agora ou depois:

| Item | Valor |
|---|---:|
| Cupons de desconto e promoções | R$ 2.800 |
| Recuperação de carrinho abandonado | R$ 2.500 |
| Blog / área de conteúdo com CMS | R$ 3.500 |
| Integração de NF-e (Bling, Tiny ou Omie) | R$ 4.500 |
| Venda e matrícula de cursos online pelo site | R$ 9.000 |
| Programa de fidelidade (pontos ou cashback) | R$ 6.500 |
| Marketplace multi-vendedor | a partir de R$ 25.000 |
| Aplicativo mobile (iOS e Android) | a partir de R$ 45.000 |

**Sobre a NF-e:** vale destacar que loja virtual que vende produto físico precisa
emitir nota. Se a Entend já emite pelo sistema do contador ou por ERP próprio,
não há nada a fazer e o custo é zero. Se você quiser que o site emita sozinho a
cada venda, é o item de R$ 4.500 acima. Sinalizo agora para não virar surpresa
perto do lançamento.

**Sobre a venda de cursos:** é o opcional com melhor retorno na sua situação. O
site já vai listar os cursos; permitir matrícula e pagamento ali mesmo aproveita
toda a estrutura de checkout que a loja já terá.

---

## 6. Cronograma

| Semana | Etapa |
|---|---|
| 1 – 2 | Descoberta, arquitetura e modelagem do banco |
| 2 – 4 | Design de interface: institucional, loja e painel |
| 4 – 6 | Site institucional |
| 5 – 8 | Loja e painel administrativo |
| 7 – 9 | Checkout, pagamentos e frete |
| 9 – 10 | Testes, cadastro de produtos, treinamento e lançamento |

Assinando até o fim de setembro, o lançamento cai no começo de dezembro.

---

## 7. Manutenção mensal

Loja não é obra entregue: é sistema que roda todo dia, com pagamento e estoque
em jogo. Depois do lançamento:

| Plano | Valor | O que inclui |
|---|---:|---|
| **Essencial** | R$ 1.200/mês | Hospedagem gerenciada, backups diários, monitoramento, atualizações de segurança, correção de defeitos e até 6h/mês de ajustes |
| **Crescimento** | R$ 2.900/mês | O anterior + até 18h/mês de melhorias, acompanhamento de conversão e relatório mensal |

Os 30 dias seguintes ao lançamento já estão inclusos no projeto. A mensalidade
começa depois disso. Não é obrigatória, mas sistema com pagamento integrado sem
ninguém olhando é risco real.

---

## 8. Custos de terceiros

Pagos pela Entend direto ao fornecedor e em nome da Entend. Não passam por mim e
não estão embutidos nos valores acima.

| Item | Faixa estimada |
|---|---|
| Domínio (registro.br) | ~R$ 40/ano |
| Hospedagem e banco de dados | R$ 80 a R$ 350/mês |
| Certificado SSL | R$ 0 (incluso na publicação) |
| Mercado Pago / Pagar.me — Pix | ~0,99% por transação |
| Mercado Pago / Pagar.me — cartão | ~3,5% a 5% conforme prazo de recebimento |
| Envio de e-mails transacionais | R$ 0 a R$ 120/mês |
| Frete | custo por envio, cobrado do cliente |

Valores de mercado em setembro de 2026, para dimensionamento. Fecho os
fornecedores com você na Fase 1.

---

## 9. Condições comerciais

- **Pagamento:** 40% na assinatura, 30% na aprovação do design, 30% na entrega.
  Parcelamento em até 5 vezes disponível.
- **2 rodadas de revisão por etapa.** Rodadas adicionais a R$ 180/h.
- **Garantia de 90 dias** para correção de defeitos após o lançamento.
- **Código-fonte, domínio e todas as contas em nome da Entend.** Você não fica
  presa a mim nem a ninguém — é a principal vantagem de não usar plataforma alugada.
- Prazos contam da assinatura e dependem de retorno em até 3 dias úteis nas
  etapas de aprovação.
- Validade desta proposta: 30 dias.

---

## 10. Fora do escopo

Listado para não haver surpresa:

- Cupons de desconto, fidelidade, marketplace multi-vendedor e app mobile
  (orçados na seção 5)
- Emissão de NF-e (opcional na seção 5)
- Produção fotográfica dos produtos — posso orçar à parte ou indicar quem faça
- Redação de textos institucionais e descrições de produto além dos fornecidos
- Verba e gestão de mídia paga (Google Ads, Meta Ads)
- Operação logística, embalagem e atendimento ao cliente
- Traduções e versões em outros idiomas

---

## 11. Premissas

- Não foi possível auditar o entend.com.br antes desta proposta. Havendo conteúdo,
  integrações ou histórico de SEO relevantes, revemos os números na Fase 1.
- Catálogo de até 50 produtos. Acima disso, cadastro adicional é orçado à parte.
- Textos, fotos e dados dos instrutores e cursos são fornecidos pela Entend.
- Assume-se CNPJ ativo apto a receber pagamento online e conta habilitada no
  gateway escolhido.

---

## 12. Para fechar, preciso saber

1. Quantos produtos você quer no ar no lançamento — e quanto é livro e quanto é papelaria?
2. As fotos dos produtos já existem? Em que qualidade?
3. Quantos instrutores entram na página, e você já tem foto e bio de cada um?
4. Quantos cursos vão para o site? Cada um precisa de página própria?
5. Tem preferência entre Mercado Pago e Pagar.me? Já tem conta em algum?
6. A emissão de nota fiscal já funciona hoje de alguma forma?
7. Tem loja física? Faz sentido oferecer retirada no local?
8. Existe manual de marca e identidade visual, ou criamos junto?
9. Quem da equipe vai operar o painel no dia a dia?
10. O lançamento em dezembro faz sentido para você?

---

## 13. Próximos passos

1. **Uma conversa de 30 minutos** esta semana, para eu ver a operação e fechar as
   dúvidas acima.
2. Assinatura e início.
3. Primeira entrega visual em duas semanas — você vê o site desenhado antes de
   qualquer linha de código de tela.

---

**[SEU NOME / EMPRESA]**
[SEU E-MAIL] · [SEU TELEFONE] · [CNPJ]
