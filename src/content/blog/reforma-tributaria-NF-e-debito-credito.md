---
author: Papo Fiscal
pubDatetime: 2026-03-11T19:46:00Z
modDatetime: 2026-04-14T08:58:00Z
title: Notas Fiscais de Débito e Crédito na Reforma Tributária
slug: reforma-tributaria-notas-fiscais-de-debito-e-credito
featured: false
draft: false
tags:
  - Reforma Tributária
  - Nota Técnica
  - NF-e
  - DF-e
  - Ajustes SINIEF
  - CONFAZ
  - Sped
description: Publicado o Ajuste SINIEF 49/2025 regulamentando a emissão de notas de débito e crédito em vendas com pagamento antecipado, perdas de estoque, redução de valores e retornos por recusa. Produzindo efeitos a partir de 4 de maio de 2026.
---

O CONFAZ publicou o Ajuste SINIEF 49/2025 definindo regras para emissão de notas de débito e crédito em vendas com pagamento antecipado, perdas de estoque, redução de valores e retornos por recusa. Adequando a legislação do ICMS às novas regras da Reforma Tributária relacionadas à emissão de notas fiscais. ⚠️ Produzindo efeitos a partir de 4 de maio de 2026.

Inclusive, foi publicada a nova versão 3.2.2 do Guia Prático da EFD ICMS IPI, com orientações sobre CBS e IBS, e Ajuste SINIEF 49/2025:

🆕 Alterações no registro C100: inclusão da exceção nº 11 de orientação:

- _Não devem ser escriturados os documentos fiscais que carreguem informações exclusivamente acerca dos novos tributos criados na Reforma Tributária do Consumo e que não versem sobre ICMS ou IPI._
- _Por outro lado, os documentos fiscais emitidos nas operações previstas no Ajuste SINIEF 49/25 que envolvam tanto os novos tributos da Reforma Tributária do Consumo quanto ICMS ou IPI devem ser regularmente escriturados na EFD em relação a estes tributos._

Já o Comitê Gestor do IBS lança a **Cartilha Orientativa para Emissão da NF-e do IBS – volume 1** com orientações abrangentes, abordando quase todas as operações fiscais relacionadas a nota de débito e crédito.

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    📌 Ponto importante: o Ato Conjunto nº 1/2025 flexibilizou a exigência dessas obrigações nesse período de adaptação. Ele prevê que não haverá aplicação de penalidades até o primeiro dia do quarto mês subsequente à publicação do regulamento, que ainda não foi publicado. <br><br>
    Na prática, o Fisco não estará punindo o descumprimento das formalidades neste momento.
    Então, embora a obrigação exista na norma, não é razoável exigir rigor absoluto enquanto o próprio regulamento ainda não foi editado.
  </span>
</div>

## Sumário

## Notas Fiscais de Débito

As notas fiscais de débito têm por finalidade registrar acréscimos no valor devido de IBS e CBS na apuração do emitente, em decorrência de ajustes ou eventos que modifiquem o débito originalmente apurado.

Quando aplicável, o valor de IBS e CBS informados também geram crédito correspondente para o contribuinte indicado como destinatário do documento, conforme as regras legais e operacionais vigentes.

A NT 2025.002, que trata das adequações da NF-e para a reforma tributária, prevê uso dos seguintes tipos de nota de débito:

- 01 = Transferência de créditos para Cooperativas;
- 02 = Anulação de Crédito por Saídas Imunes/Isentas;
- 03 = Débitos de notas fiscais não processadas na apuração;
- 04 = Multa e juros;
- 05 = Transferência de crédito na sucessão;
- 06 = Pagamento antecipado;
- 07 = Perda em estoque;
- 08 = Desenquadramento do SN

Contudo o Ajuste SINIEF 49/2025 relacionou ao ICMS apenas duas operações para nota de débito:

- 06 = Pagamento antecipado;
- 07 = Perda em estoque;

Ou seja, uma nota de débito tipo `04 = Multa e juros` por exemplo, está relacionada apenas ao IBS/CBS, logo esse tipo de nota não terá informações de ICMS e não será escriturada na EFD ICMS/IPI.

A Cartilha Orientativa do CGIBS por sua vez trouxe orientações para todas as operações de nota de débito, exceto para a `08 = Desenquadramento do SN`.

Vejamos primeiro as operações de débito do Ajuste SINIEF:

### Pagamento antecipado

Quando o contribuinte receber um pagamento antecipado relativo a fornecimento futuro, deverá emitir nota fiscal de débito do tipo “06 – Pagamento Antecipado”, para o destaque dos tributos devidos sobre o valor recebido, nos termos do art. 10, § 4º, inciso I, da Lei Complementar nº 214/2025.

O Ajuste SINIEF 49/2025 define o seguinte:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3">
  <ul class="flex flex-col gap-2">
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Cláusula segunda Na hipótese prevista no inciso I da cláusula primeira, o contribuinte emitirá NF-e de saída, contendo, além dos demais requisitos exigidos:</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">I - no campo “finNFe - Finalidade de emissão da NF-e”, o código “6=Nota de débito”;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">II - no campo “tpNFDebito - Tipo de Nota de Débito”, o código “06=Pagamento antecipado”;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">III - no campo “natOp - Descrição da Natureza da Operação”, o texto “Venda para entrega futura - Pagamento antecipado”;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">IV - no campo "Código Fiscal de Operações e Prestações" - "CFOP", o código 5.922 ou 6.922, conforme o caso;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">V - sem destaque do ICMS.</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Parágrafo único. A emissão da NF-e que trata o “caput" não dispensa a emissão da NF-e de venda, no momento da efetiva saída da mercadoria, contendo, além dos demais requisitos exigidos:</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">I - o destaque do ICMS, quando houver;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">II - no campo “refNFe - Chave de acesso da NF-e referenciada”, a chave de acesso da NF-e prevista no "caput";</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">III - no campo “finNFe - Finalidade de emissão da NF-e” o código “1=NF-e normal”.</li>
  </ul>
</div>

Conforme consta na cartilha do CGIBS, deverá ser emitida uma nota fiscal de débito para cada recebimento antecipado, no momento do efetivo recebimento, aplicando-se a mesma classificação tributária e alíquota incidente sobre o bem ou serviço a ser fornecido.

Os débitos de IBS correspondentes à antecipação serão registrados no período de apuração em que ocorrer o recebimento antecipado. Quando houver direito à apropriação de crédito pelo adquirente, este será reconhecido no momento da extinção do débito do fornecedor, observadas as mesmas regras aplicáveis às notas fiscais de fornecimento.

Por ocasião do efetivo fornecimento do bem ou serviço, conforme disposto no art. 10, § 4º, inciso II, da Lei Complementar nº 214/2025, o contribuinte deverá emitir a nota fiscal de fornecimento com o valor total da operação, referenciando as notas fiscais de débito de antecipação previamente emitidas, no Grupo de Notas Fiscais de Antecipação.

Ao processar a nota fiscal de fornecimento, o sistema de apuração assistida do IBS deduzirá, de forma automática, o valor do IBS já destacado nas notas fiscais de débito de antecipação emitidas anteriormente, desde que a nota fiscal de fornecimento contenha o referenciamento das chaves de acesso das notas de antecipação, evitando a duplicidade de lançamento de débitos na apuração do contribuinte emitente.

### Perda em estoque

Quando ocorrer perda de bens materiais em estoque, nos termos do art. 47, § 6º da Lei Complementar nº214/2025, os créditos de IBS apropriados relativos a esses bens, bem como os créditos vinculados a serviços a eles relacionados, deverão ser estornados da apuração mediante a emissão de nota fiscal de débito do tipo “07 – Perda em Estoque”.

Caso o bem perdido tenha sido adquirido de terceiros, deverá ser referenciado na nota fiscal de débito:

- o documento fiscal referente à aquisição do bem;
- o documento fiscal referente aos serviços vinculados à aquisição do bem.

O Ajuste SINIEF 49/2025 define o seguinte:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3">
  <ul class="flex flex-col gap-2">
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Cláusula terceira Na hipótese prevista no inciso II da cláusula primeira, o contribuinte emitirá NF-e de saída, contendo, além dos demais requisitos exigidos:</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">I - no campo “finNFe - Finalidade de emissão da NF-e”, o código “6=Nota de débito”;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">II - no campo “tpNFDebito - Tipo de Nota de Débito”, o código “07=Perda em estoque”;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">III - no campo "Código Fiscal de Operações e Prestações" - "CFOP", o código 5.927;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">IV - no campo “natOp - Descrição da Natureza da Operação”, o texto “Baixa de Estoque”;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">V - sem destaque do ICMS.</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">VI - no campo "infAdFisco - Informações Adicionais de Interesse do Fisco", a explicação com a motivação de emissão da NF-e, contendo a justificativa da baixa do estoque;</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">no “Grupo E. Identificação do Destinatário da Nota Fiscal eletrônica”, as informações do próprio emitente da NF-e.</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">§ 1º A NF-e de que trata o "caput" deverá ser escriturada conforme a legislação de cada unidade federada.</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">§ 2º O contribuinte deverá efetuar o estorno do ICMS creditado da mercadoria que vier a ser objeto de extravio, perecimento, deterioração, furto ou roubo, conforme a legislação de cada unidade federada.</li>
  </ul>
</div>

Na Nota Fiscal de débito por perda do estoque, não terá destaque do ICMS, certo? Então, em que momento acontecerá o estorno do crédito do ICMS? Deverá ser emitida outra NF só pra estornar o ICMS?

Conforme consta no Ajuste SINIEF 49/2025 ficará sem destaque do ICMS. Então a princípio o estorno do crédito do ICMS vai ocorrer por ajuste na apuração do ICMS, conforme a regra de cada estado.

Agora as demais operações de débito da Cartilha Orientativa do Comitê Gestor do IBS:

### Transferência de créditos para Cooperativas

Esta nota fiscal de débito deve ser emitida pelo associado sujeito ao regime regular de apuração do IBS, com a finalidade de transferir à respectiva cooperativa — quando esta for optante pelo regime específico previsto no art. 271 da Lei Complementar nº 214/2025 — os créditos decorrentes de aquisições de bens e serviços fornecidos com redução de 100% da alíquota, nos termos do art. 271, inciso I, da referida lei.

O valor do IBS informado será lançado a débito na apuração do emitente e a crédito na apuração da cooperativa destinatária.

O valor a ser transferido fica limitado ao montante de créditos efetivamente apropriados e não utilizados pelo cooperado no período de apuração. Caso o valor destacado na nota fiscal exceda o limite de créditos disponíveis, o valor excedente não produzirá efeitos na apuração assistida, sendo desconsiderado pelo sistema do Comitê Gestor do IBS.

### Anulação de crédito por saídas imunes/isentas

O art. 51 da Lei Complementar nº 214/2025 estabelece que devem ser anulados, proporcionalmente, os créditos vinculados a aquisições utilizadas em operações subsequentes imunes ou isentas, ressalvadas as hipóteses excepcionadas pelo próprio dispositivo legal.

O sistema de apuração assistida do IBS apresentará, ao final de cada período de apuração, o valor sugerido de anulação, calculado a partir dos valores e códigos informados nas notas fiscais de fornecimento emitidas pelo contribuinte.

A anulação efetiva dos créditos deverá ser formalizada mediante a emissão de nota fiscal de débito do tipo “02 – Anulação de Crédito por Saídas Imunes/Isentas”, observando-se o período de ajustes definido em regulamento e devendo ser informado na nota fiscal o grupo “Ajuste de Competência”.

A emissão da referida nota é condição necessária para que o valor seja lançado como débito na apuração assistida, promovendo a regularização do saldo de créditos do contribuinte conforme previsto na legislação aplicável.

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    📌 Grupo Ajuste de Competência: o grupo "gAjusteCompet" da NF-e será preenchido nas hipóteses de emissão de notas de débito, que tenham por finalidade a realização de ajustes nos saldos de apuração que não requeiram a indicação de nenhuma operação específica ocorrida no período. O valor do IBS será lançado no período de competência informado no respectivo campo da nota fiscal.  
  </span> <br><br>
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    Cenários de uso, conforme indicador “Ajuste de Competência” (ind_gAjusteCompet) da tabela de CST do IBS e da CBS:
  </span>
  <ul class="flex flex-col gap-2">
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Nota fiscal de débito do tipo "02=Anulação de Crédito por Saídas Imunes/Isentas" (art. 51 da Lei Complementar nº214/2025);</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Nota fiscal de débito do tipo "03=Débitos de notas fiscais não processadas na apuração".</li>
</div>

### Débitos de notas fiscais não processadas da apuração

Ao final de cada período de apuração, e após a disponibilização da prévia da apuração assistida pelo sistema do Comitê Gestor do IBS, caberá ao contribuinte verificar a integridade das informações processadas, assegurando que todos os documentos fiscais de fornecimento tenham sido devidamente reconhecidos pelo sistema.

Caso sejam identificadas notas fiscais de fornecimento não processadas, o contribuinte enquadrado no regime regular de apuração deverá, durante o período de ajustes definido em regulamento, emitir uma nota fiscal de débito do tipo `03 – Débitos de Notas Fiscais Não Processadas na Apuração`, de forma a garantir que o saldo final do período reflita corretamente o total de débitos devidos.

A emissão dessa nota fiscal deverá observar as seguintes orientações técnicas:

- O emitente e o destinatário deverão ser o próprio contribuinte (mesmo CNPJ base);
- Cada item da nota fiscal corresponderá a um documento fiscal não processado, informando no campo o valor total do débito do documento faltante;
- Em cada item, deverá ser referenciada a chave de acesso do documento fiscal não processado, no grupo VC01 `<DFeReferenciado>`.

A nota fiscal de débito do tipo 03 produzirá efeitos exclusivamente na apuração do fornecedor, não gerando créditos automáticos para os adquirentes, ainda que os valores correspondentes sejam extintos na apuração do emitente. Os créditos do adquirente somente poderão ser apropriados após o efetivo processamento das notas fiscais originais pelo sistema do Comitê Gestor do IBS, momento em que serão identificadas todas as informações fiscais e cadastrais necessárias ao correto tratamento das operações no sistema de apuração assistida.

O sistema de apuração assistida garantirá o tratamento adequado aos débitos destacados, de modo a prevenir a existência de lançamentos em duplicidade e preservar a consistência dos saldos apurados.

### Multa e juros recebidos

Nos termos do art. 12, § 1º, II, da Lei Complementar nº214/2025, a nota fiscal de débito do tipo “04 – Multa e Juros” deverá ser emitida pelo fornecedor sempre que houver recebimento de acréscimos moratórios relativos a pagamentos efetuados com atraso pelo adquirente, correspondentes a fornecimentos realizados, com o objetivo de complementar a base de cálculo do IBS. A nota fiscal de débito desse tipo deverá ser emitida no momento do recebimento desses valores, e os respectivos débitos de IBS serão incluídos no período de apuração do recebimento.

Cada item da nota fiscal de débito deverá referenciar o item da nota fiscal original a que se relaciona o acréscimo moratório, aplicando-se a mesma classificação tributária e a mesma alíquota efetiva incidente sobre o fornecimento original.

A extinção do débito decorrente da nota fiscal de débito de multa e juros, quando o adquirente for contribuinte do regime regular de apuração, gerará o correspondente crédito de IBS, observadas as regras aplicáveis.

Na hipótese de inobservância da obrigatoriedade de emissão da nota fiscal de débito pelo fornecedor, o adquirente poderá regularizar a operação mediante a emissão de nota fiscal de crédito.

### Transferência de crédito na sucessão

Nos termos do parágrafo único do art. 55 da Lei Complementar nº 214/2025, a empresa fundida, cindida ou incorporada que possua créditos de IBS apropriados e não utilizados poderá transferi-los à(s) empresa(s) sucessora(s), observadas as condições legais aplicáveis.

A efetivação da transferência deverá ocorrer por meio da emissão, pela empresa sucedida, de nota fiscal de débito do tipo “05 – Transferência de Crédito de Sucessão”, informando no campo destinatário a empresa sucessora que receberá o crédito.

Havendo mais de uma empresa sucessora, deverão ser emitidas notas fiscais distintas, uma para cada destinatária dos créditos transferidos.

## Notas Fiscais de Crédito

Têm por finalidade reduzir o débito de IBS na apuração do contribuinte emitente e, quando aplicável, gerar o correspondente lançamento a crédito na apuração do contribuinte destinatário.

A NT 2025.002, que trata das adequações da NF-e para a reforma tributária, prevê uso dos seguintes tipos de nota de crédito:

- 01 = Multa e juros;
- 02 = Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25);
- 03 = Retorno por recusa total na entrega ou por não localização do destinatário na tentativa de entrega;
- 04 = Redução de valores;
- 05 = Transferência de crédito na sucessão

Contudo o Ajuste SINIEF 49/2025 relacionou ao ICMS apenas duas operações para nota de crédito:

- 03 = Retorno por recusa total na entrega ou por não localização do destinatário na tentativa de entrega;
- 04 = Redução de valores

A Cartilha Orientativa do CGIBS por sua vez apresenta orientações para todas as operações de nota de crédito, exceto para a `02 = Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25)`.

Vejamos primeiro as operações de débito do Ajuste SINIEF:

### Retorno por recusa ou não localização do destinatário

Nos termos do art. 10 da Lei Complementar nº 214/2025, o fato gerador do IBS e da CBS ocorre no momento do fornecimento, caracterizado pelo art. 3º, II, “a”, como a entrega ou disponibilização do bem material. Assim, quando a entrega não se concretizar, em razão da recusa do destinatário ou de sua não localização, não se configura o fato gerador, e portanto, o imposto não será devido.

Entretanto, considerando que a legislação do ICMS adota o conceito de circulação da mercadoria como fato gerador, a nota fiscal original não poderá ser cancelada, uma vez que houve o efetivo transporte do bem.

Para fins de desfazimento do débito de IBS e CBS, o contribuinte deverá emitir uma nota fiscal de crédito do tipo “03 – Retorno por Recusa na Entrega ou por Não Localização do Destinatário na Tentativa de Entrega”, informando a si próprio como emitente e destinatário no arquivo XML.

O Ajuste SINIEF 49/2025 define o seguinte:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3">
  <ul class="flex flex-col gap-2">
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Quando a entrega não ocorrer (total ou parcial), o remetente da NF-e original deve emitir NF-e de entrada com:</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">finNFe = 5 (Nota de crédito)</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">tpNFCredito = 03 (Retorno por recusa ou não localização)</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">natOp = Retorno por Recusa ou Não Localização</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Itens não entregues no grupo prod</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">refNFe da nota original</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Destaque do ICMS, quando aplicável</li>
  </ul>
</div>

#### Recusa parcial:

**Destinatário não contribuinte**: remetente emite a nota de crédito conforme citado acima;

**Destinatário contribuinte**: destinatário emite nota de débito, com:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border">
  <ul class="flex flex-col gap-1">
    <li class="sm:text-sm text-xs text-[#8b5cf6]">finNFe = 6 (Nota de débito)</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">tpNFDebito = 09 (Retorno por Recusa Parcial)</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">natOp: Retorno por Recusa Parcial</li>
  </ul>
</div>

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    ⚠️ Cabe destacar que o código "09 (Retorno por Recusa Parcial)" para “tpNFDebito - Tipo de Nota de Débito” ainda não consta na NT 2025.002, ficando impossivel seu cumprimento com o atual leiaute da NF-e. Mas é provável que o leiaute seja devidamente atualizado até 4 de maio de 2026, data que inicia a vigência do Ajuste SINIEF 49/2025.
  </span>
</div>

#### 🚨 Eventos obrigatórios em caso de recusa total ou não localização:

Destinatário deve registrar:

- Operação não Realizada ou Desconhecimento da Operação

Transportador deve registrar:

- Insucesso na Entrega da NF-e ou Insucesso na Entrega do CT-e

### Redução de valores ou quantidades

A nota fiscal de crédito do tipo `04 – Redução de Valores` deverá ser utilizada quando, não sendo mais possível o cancelamento do documento fiscal, for identificada a necessidade de redução do valor do IBS destacado, seja em razão de erro de destaque a maior, seja pela entrega parcial da quantidade consignada no documento fiscal original.

O Ajuste SINIEF 49/2025 define o seguinte:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3">
  <ul class="flex flex-col gap-2">
    <li class="sm:text-sm text-xs text-[#8b5cf6]">Se a NF-e de saída não puder ser cancelada, o remetente deve emitir NF-e de entrada (nota de crédito) com:</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">finNFe = 5 (Nota de crédito)</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">tpNFCredito = 04 (Redução de valores ou quantidades)</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">CFOP inverso ou CFOP genérico de entrada</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">natOp: Redução de valores ou quantidades</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">infAdFisco com justificativa</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">refNFe apontando a NF-e a ser reduzida</li>
    <li class="sm:text-sm text-xs text-[#8b5cf6]">A NF-e deve conter apenas os valores/quantidades a serem deduzidos.</li>
  </ul>
</div>

Com as multas previstas sobre o cancelamento de notas fiscais pela LC 2014/2025, que amplia o impacto financeiro sobre erros documentais, este seria o novo processo mais adequado para correção de informações nas notas fiscais.

Art. 341-G prevê multa para quem cancelar documento fiscal:

- Multa de 66% do tributo de referência — Cancelamento após ocorrência do fato gerador
- Multa de 33% do tributo de referência — Cancelamento após o prazo legal

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    📌 Importante: nunca foi possível corrigir uma nota para reduzir imposto destacado e a NT 2025.002 até então citava que as notas de débito e crédito não seriam aplicadas para ICMS. Contudo o Ajuste SINIEF 49/2025 muda a regra do jogo, agora quando destacado a maior, tanto o ICMS quanto o IBS e CBS, é através da nota de redução de valores que podemos fazer o processo de correção, inclusive do ICMS.
  </span>
</div>

Agora as demais operações de crédito da Cartilha Orientativa do Comitê Gestor do IBS:

### Multa e juros pagos

Nos termos do art. 12, § 1º, II, da Lei Complementar nº214/2025, é obrigatória a emissão de nota fiscal de débito do tipo “04 – Multa e Juros” pelo fornecedor, sempre que houver o recebimento de acréscimos moratórios decorrentes de pagamentos efetuados com atraso pelo adquirente, com a finalidade de complementar a base de cálculo do IBS do respectivo fornecimento.

Mas caso o fornecedor deixe de emitir a referida nota fiscal, o adquirente poderá suprir a omissão mediante a emissão de nota fiscal de crédito do tipo “01 – Multa e Juros”, devendo:

- referenciar corretamente os itens da nota fiscal de aquisição original; e
- aplicar sobre os valores dos acréscimos pagos, proporcionalizados por item objeto de incidência dos acréscimos, a mesma tributação incidente sobre o fornecimento original.

A apropriação do crédito pelo adquirente emitente estará condicionada ao aceite do fornecedor, mediante emissão de evento específico, uma vez que gerará em sua apuração um débito de igual valor e, cumulativamente, à extinção desse débito pelo fornecedor.

### Transferência de crédito na sucessão

Nos termos do parágrafo único do art. 55 da Lei Complementar nº 214/2025, a empresa fundida, cindida ou incorporada que possua créditos de IBS apropriados e não utilizados poderá transferi-los à(s) empresa(s) sucessora(s).

Preferencialmente, a transferência deverá ser formalizada mediante a emissão, pela empresa sucedida, de nota fiscal de débito do tipo “05 – Transferência de Crédito de Sucessão”.

Entretanto, caso o CNPJ da empresa sucedida se torne inapto para emissão de documentos fiscais eletrônicos antes da efetivação da transferência, esta poderá ser realizada mediante a emissão, pela(s) empresa(s) sucessora(s), de nota fiscal de crédito do tipo “05 – Transferência de Crédito na Sucessão”.

Cada empresa sucessora deverá emitir uma nota fiscal de crédito, informando no campo destinatário a empresa sucedida e indicando o valor do IBS correspondente ao crédito a ser transferido, a ser apropriado como crédito pela emitente (sucessora).

O valor total dos créditos a serem apropriados — somatório de todas as notas fiscais de crédito emitidas pelas sucessoras — ficará limitado ao montante de crédito acumulado e não utilizado na apuração da empresa sucedida.

A nota fiscal de crédito emitida somente produzirá efeitos na apuração assistida do IBS tanto da empresa sucedida quanto da(s) sucessora(s) quando, cumulativamente:

- todas as empresas sucessoras envolvidas (se houver mais de uma) tiverem emitido o evento de manifestação favorável. Esta anuência será formalizada através do evento “Manifestação sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão”, apontando para a respectiva nota fiscal de crédito;
- tiver sido emitida a manifestação favorável pelo fisco competente, através do evento “Manifestação do Fisco sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão”, apontando para a respectiva nota fiscal de crédito.

---

Gostou deste conteúdo? Compartilhe com seus colegas e amigos que também podem se beneficiar destas informações.

Até a próxima! 👋

<div class="flex flex-row">
	<a href="https://whatsapp.com/channel/0029VbBUvmuLSmbZAV6U9810" 
		target="_blank" 
		title="Inscreva-se no WhatsApp Canal do Papo Fiscal" 
		rel="nofollow">
      <svg
        width="20"
        height="20"
        viewBox="0 0 20 20"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        ><path
          d="M13.8337 11.6667C13.667 11.5833 12.5837 11.0833 12.417 11C12.2503 10.9167 12.0837 10.9167 11.917 11.0833C11.7503 11.25 11.417 11.75 11.2503 11.9167C11.167 12.0833 11.0003 12.0833 10.8337 12C10.2503 11.75 9.66699 11.4167 9.16699 11C8.75033 10.5833 8.33366 10.0833 8.00033 9.58334C7.91699 9.41668 8.00033 9.25001 8.08366 9.16668C8.16699 9.08334 8.25033 8.91668 8.41699 8.83334C8.50033 8.75001 8.58366 8.58334 8.58366 8.50001C8.66699 8.41668 8.66699 8.25001 8.58366 8.16668C8.50033 8.08334 8.08366 7.08334 7.91699 6.66668C7.83366 6.08334 7.66699 6.08334 7.50033 6.08334C7.41699 6.08334 7.25033 6.08334 7.08366 6.08334C6.91699 6.08334 6.66699 6.25001 6.58366 6.33334C6.08366 6.83334 5.83366 7.41668 5.83366 8.08334C5.91699 8.83334 6.16699 9.58334 6.66699 10.25C7.58366 11.5833 8.75033 12.6667 10.167 13.3333C10.5837 13.5 10.917 13.6667 11.3337 13.75C11.7503 13.9167 12.167 13.9167 12.667 13.8333C13.2503 13.75 13.7503 13.3333 14.0837 12.8333C14.2503 12.5 14.2503 12.1667 14.167 11.8333C14.167 11.8333 14.0003 11.75 13.8337 11.6667ZM15.917 4.08334C12.667 0.833344 7.41699 0.833344 4.16699 4.08334C1.50033 6.75001 1.00033 10.8333 2.83366 14.0833L1.66699 18.3333L6.08366 17.1667C7.33366 17.8333 8.66699 18.1667 10.0003 18.1667C14.5837 18.1667 18.2503 14.5 18.2503 9.91668C18.3337 7.75001 17.417 5.66668 15.917 4.08334ZM13.667 15.75C12.5837 16.4167 11.3337 16.8333 10.0003 16.8333C8.75033 16.8333 7.58366 16.5 6.50033 15.9167L6.25033 15.75L3.66699 16.4167L4.33366 13.9167L4.16699 13.6667C2.16699 10.3333 3.16699 6.16668 6.41699 4.08334C9.66699 2.00001 13.8337 3.08334 15.8337 6.25001C17.8337 9.50001 16.917 13.75 13.667 15.75Z"
          fill="green"
        /></svg>
      <span class="text-sm text-green-600">Siga o Papo Fiscal no WhatsApp e não perca nenhuma novidade</span>
  </a>
</div>

---

Precisando de apoio jurídico?

Entre já em contato com o nosso parceiro o advogado Rodrigo Zanis!

Serviços personalizados e de excelência na área da advocacia, de forma inovadora, eficaz e ágil.

<div class="text-center gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 hover:scale-105 hover:-translate-y-1 p-3">
  <a href="https://rodrigozanis.adv.br" target="_blank" class="no-underline hover:underline">
    <div>
      <img src="/assets/logo-rz-consultoria-e-assessoria-juridica.png" class="h-48 w-48 mx-auto" alt="logo advogado Rodrigo Zanis">
      <p class="text-xl font-medium text-black">Advogado Rodrigo Zanis</p>
      <strong class="text-slate-500">Consultoria e Assesoria Jurídica</strong>
    </div>
  </a>
</div>

---
