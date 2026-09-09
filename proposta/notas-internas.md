# Notas internas — NÃO ENVIAR AO CLIENTE

## O que ajustar antes de mandar

| Campo | Onde | Situação |
|---|---|---|
| `[SEU NOME / EMPRESA]` | HTML + MD, cabeçalho e assinatura | marcador |
| `[SEU E-MAIL]` | HTML + MD, assinatura | marcador |
| `[SEU TELEFONE]` | HTML + MD, assinatura | marcador |
| `[CNPJ]` | HTML + MD, assinatura | marcador |
| `[LINK]` | mensagem-whatsapp.md | marcador |
| Hora avulsa R$ 180/h | seção Condições | **confira contra o seu valor** |

Deixei seu e-mail fora dos arquivos de propósito — coloque o endereço comercial
que você quiser usar nesse cliente, não necessariamente o pessoal.

## Como o R$ 38.000 foi construído

Base: R$ 150/hora.

| Módulo | Horas | Valor |
|---|---:|---:|
| 01 · Site institucional (5 páginas, design, SEO) | ~57h | R$ 8.500 |
| 02 · Loja: catálogo, busca, carrinho, conta de cliente | ~50h | R$ 7.500 |
| 03 · Checkout + gateway (Pix, cartão, webhooks, e-mails) | ~43h | R$ 6.500 |
| 04 · Frete por CEP | ~20h | R$ 3.000 |
| 05 · Painel administrativo | ~60h | R$ 9.000 |
| 06 · QA, deploy, cadastro, treinamento, 30 dias | ~23h | R$ 3.500 |
| **Total** | **~253h** | **R$ 38.000** |

São ~10 semanas a 25h/semana. Se você trabalha mais horas por semana, o prazo
encurta, mas **não anuncie isso** — a folga é o seu colchão de risco.

Se seu valor/hora for outro, recalcule os seis módulos na mesma proporção. Não
mexa só no total: a tabela por módulo é o que dá credibilidade ao número, e ela
precisa fechar.

## Riscos — vigiar na descoberta

1. **API dos Correios.** O calculador antigo saiu do ar e o CWS novo exige
   contrato e credencial. Se ela não tiver contrato, o caminho é Melhor Envio
   (agregador, sem contrato próprio). Por isso a proposta diz "Correios **ou**
   Melhor Envio" — não prometa Correios direto antes de confirmar.
2. **"Até 50 produtos" precisa de definição.** 50 produtos com 5 variações cada
   são 250 SKUs de cadastro. Na Fase 1, deixe escrito se o teto é produto-pai ou
   SKU. É a brecha de escopo mais provável desse projeto.
3. **Painel administrativo é o módulo mais caro e o mais vago.** R$ 9.000 e ~60h.
   Congele as telas no design, por escrito, antes de codar. Todo pedido de
   "só mais um relatorizinho" sai daí.
4. **Nota fiscal.** Loja que vende produto físico precisa emitir. Deixei como
   opcional de R$ 4.500 e sinalizado na proposta justamente para não virar
   discussão em novembro. Se ela não emite hoje, isso depende do contador dela e
   pode virar caminho crítico.
5. **Cartão — nunca tocar em dado de cartão.** Tokenização pelo SDK do gateway,
   sempre. Se em algum momento o dado do cartão passar pelo servidor da Entend,
   entra escopo de PCI que não está orçado e que você não quer.
6. **Mercado Pago x Pagar.me.** Para o porte dela, Mercado Pago: onboarding mais
   simples, Pix nativo, documentação melhor. Pagar.me tem taxa melhor em volume,
   mas exige mais burocracia. Recomende MP a menos que ela já tenha Pagar.me.
7. **Fotos de produto.** Papelaria costuma não ter foto padronizada. Está fora do
   escopo por escrito. Se ela pedir, orçar à parte.
8. **Site atual não auditado.** Ver abaixo.

## Ressalva de apuração

Não consegui abrir `www.entend.com.br` nem o Archive.org enquanto montava isto —
ambos bloqueados pela política de rede do ambiente. Não sei, portanto:

- em que plataforma o site atual roda;
- se já existe alguma venda ou catálogo online;
- que tráfego e posicionamento de Google existem para preservar com redirects;
- qual é a identidade visual atual;
- quantos instrutores e cursos existem hoje (afeta direto o módulo 01).

Isso está registrado como premissa dentro da proposta. **Antes de enviar, abra o
site e confira.** Se houver algo grande lá — principalmente e-commerce já em
operação, ou dezenas de cursos com página própria — o módulo 01 e o cadastro
mudam de tamanho.

## Se ela travar no preço

O caminho que **não** está na proposta, e que eu manteria no bolso: montar em
Nuvemshop ou Loja Integrada com tema sob medida sai por R$ 15.000 a R$ 19.000 e
umas 6 semanas. Em troca, ela paga mensalidade de plataforma e comissão por
venda, e o código não é dela.

Não ofereça isso de saída — ela pediu loja própria, e "próprio" é o argumento de
valor do orçamento inteiro. Use só se a alternativa for perder o projeto.

## Sazonalidade — a conta do prazo

De 09/09/2026 a 01/12/2026 são ~12 semanas. O projeto leva 10. Cabe com duas
semanas de folga, desde que assine em setembro. Se escorregar para novembro,
renegocie o prazo em vez de comprimir — e nunca lance loja nova em cima do pico
de dezembro.
