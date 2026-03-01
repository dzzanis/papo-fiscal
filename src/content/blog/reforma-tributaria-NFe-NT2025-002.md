---
author: Papo Fiscal
pubDatetime: 2025-05-03T07:58:00Z
modDatetime: 2026-03-01T10:19:00Z
title: Nota Técnica 2025.002 - Adequações da NF-e à reforma tributária
slug: reforma-tributaria-nf-e-nt-2025-002
featured: false
draft: false
tags:
  - Reforma Tributária
  - Nota Técnica
  - DF-e
  - NF-e
  - NFC-e
description: A versão 1.34 da Nota Técnica 2025.002 apresenta novas definições para adequação do leiaute da NF-e à reforma tributária.
---

O Portal da Nota Fiscal Eletrônica divulgou a versão 1.34 da Nota Técnica nº 2025/002, trazendo mais atualizações nas regras de emissão de NF-e em razão da Reforma Tributária.

Confira as principais novidades.

🚫 **Regras de validação desabilitadas:**

- UB26-15 – Rejeição: Grupo de redução de alíquota do IBS Estadual informado indevidamente
- UB45-15 – Rejeição: Grupo de redução de alíquota do IBS Municipal informado indevidamente
- UB64-15 – Rejeição: Grupo de redução de alíquota da CBS informado indevidamente

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    📌 Essas regras rejeitavam a emissão da nota quando informado simultaneamente alíquota zero e o grupo de redução (gRed)
  </span>
</div>

🔄 **Regras de validação alteradas:**

- UB26-20 – IBS Estadual
- UB45-20 – IBS Municipal
- UB64-20 – CBS

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    📌 Removendo a exigência da alíquota ser maior que zero para permitir a aplicação da redução.
  </span>
</div>

Com isso, passa a admitir o envio do grupo de redução nos casos em que:

- A tabela cClassTrib indica redução
- Mas a alíquota é zero por força legal

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3 mx-6">
  <span class="sm:text-sm text-xs text-[#8b5cf6]">
    ⚠️ Importante: a nova versão mantém o posicionamento da versão 1.33. Em que embora o não preenchimento dos campos do IBS e CBS não rejeite a emissão da nota fiscal, esses dados são obrigatórios a partir de 01/01/2026, conforme o art. 348 da Lei Complementar nº 214/2025. Recomendamos então a adequação imediata para garantir a conformidade legal no prazo.
  </span>
</div>

## Sumário

## Histórico de Atualização das Notas Técnicas

Já foram publicadas diversas notas técnicas apresentando adequações dos leiautes dos DF-es (NF-e, NFC-e, CT-e, CT-e OS, BP-e, NF3-e, NFCom e NFS-e Nacional) à reforma tributária,que entrarão em vigor em [janeiro de 2026](https://papofiscal.blog/posts/reforma-tributaria-cronograma/). Veja a seguir um histórico das notas técnicas criadas para a NF-e.

### RT - Nota Técnica 2024.002

[Clique para baixar a RT - Nota Técnica 2024.002](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=DaB0yzqdbRU=)<br>
<span class="text-sm">Versão 1.10 - Publicada em 6 de dezembro de 2024</span>

Esta foi a primeira nota técnica definida conjuntamente entre os Estados, Municípios e Receita Federal do Brasil, modificando o leiaute da NF-e (modelo 55) e NFC-e (modelo 65). Inserindo os grupos e campos relacionados a tributação do Imposto sobre Bens e Serviços (IBS), Contribuição sobre Bens e Serviços (CBS) e Imposto Seletivo (IS), em atendimento as alterações previstas na EC 132/2023 para implementação da Reforma Tributária.

A versão 1.0 publicada em 01 de agosto de 2024 continha 41 páginas. Já a versão 1.10 de 06 de dezembro, passou a compor 67 páginas. Descrevendo além de novos campos, uma série de regras de validação e novos eventos.

### Nota Técnica 2025.002 v1.01

[Clique para baixar a Nota Técnica 2025.002 v1.01](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=wuVuolIzJLs=)<br>
<span class="text-sm">Versão 1.01 - Publicada em 15 de abril de 2025</span>

Esta Nota Técnica substitui a RT NT 2024.002, atualizando as definições dos novos eventos, regras de validação e leiaute da NF-e e NFC-e referente à Reforma Tributária do Consumo.

A versão 1.00 publicada em 28 de março de 2025 continha 48 páginas. Já a versão 1.01 de 15 de abril, passou a compor 50 páginas.

### Nota Técnica 2025.002 v.1.10

[Clique para baixar a Nota Técnica 2025.002 v.1.10](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=B7DBKw%20UPbs=)<br>
<span class="text-sm">Versão 1.10 - Publicada em 9 de junho de 2025</span>

Esta versão acresentou várias atualizações, como novos campos, criando e alterando regras de validação, e novos eventos para apuração do IBS/CBS, passando a compor 66 páginas.

Dentre as principais alterações destacou-se a dispensa das empresas do Simples Nacional e os MEIs de preencher os novos campos de IBS e CBS nas NF-e e NFC-e, nas emissões realizadas ao longo de 2026. A obrigatoriedade para o Simples Nacional vale a partir de janeiro de 2027. A alteração compatibilizou as regras de validação com a dispensa prevista no artigo 348, inciso III, alínea “c” da Lei Complementar 214/2025.

Outro destaque foi a criação do grupo específico de informações que envolvem antecipação de pagamento. Para referenciar os documentos fiscais relacionados às antecipações financeiras ocorridas antes da efetiva entrega de mercadorias ou prestação de serviços. Por exemplo, casos de operações de venda com entrega futura, nas quais o comprador realiza pagamentos e aguarda a disponibilidade dos bens adquiridos.

### Nota Técnica 2025.002 v.1.20

[Clique para baixar a Nota Técnica 2025.002 v.1.20](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=YFz9is%20R6tw=)<br>
<span class="text-sm">Versão 1.20 - Publicada em 30 de julho de 2025</span>

Esta versão alterou detalhamentos do cronograma, acresentou novos campos, criou e alterou regras de validação, e alterou o nome de eventos, passando a compor 69 páginas.

As principais alterações foram:

- Ajuste na regra de validação referente a obrigatoriedade de informação do IBS e CBS, dispensando os emitentes `CRT 2=Simples Nacional, excesso sublimite de receita bruta`. Assim estes contribuintes terão esta obrigação somente a partir 04/01/2027, conforme previsto no art. 348 da Lei Complementar 214/2025;
- Novo tipo de nota de crédito: `3- Retorno`;
- Alterações nos grupos de informações da tributação monofásica.
- ⚠️ Acrescentou esse alerta sobre a obrigatoriedade dos Eventos em 2026:

  Os eventos integram as obrigações acessórias do Imposto sobre Bens e Serviços (IBS) e da Contribuição sobre Bens e Serviços (CBS). E são indispensáveis para a correta apuração dos tributos e de créditos de imposto. Eles visam garantir a integridade e a rastreabilidade das operações realizadas pelos contribuintes, servindo como base de dados para o controle e a transparência do novo modelo tributário.

  De acordo com o artigo 348, §1º, da Emenda Constitucional, os contribuintes estarão dispensados do recolhimento do IBS e da CBS relativamente aos fatos geradores ocorridos entre 1º de janeiro e 31 de dezembro de 2026, desde que cumpram integralmente as obrigações acessórias previstas na legislação.

  Nesse contexto, a apresentação correta e tempestiva dos eventos mencionados neste item é condição essencial para que o contribuinte possa usufruir da dispensa do recolhimento dos tributos nesse período de transição. O não cumprimento dessas obrigações poderá implicar na perda desse benefício, sujeitando o contribuinte ao recolhimento normal dos tributos devidos.

  **Portanto, os eventos devem ser registrados, a partir de janeiro/2026, sempre que a situação concreta exigir, respeitando os critérios e prazos estabelecidos pela legislação, como forma de garantir o direito à dispensa e de contribuir para a efetividade do novo sistema tributário.**

### Nota Técnica 2025.002 v.1.30

[Clique para baixar a Nota Técnica 2025.002 v.1.30](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=6vT0rTNhFLY=)<br>
<span class="text-sm">Versão 1.30 - Publicada em 3 de outubro de 2025</span>

As principais alterações foram:

- Mudanças nos detalhamentos do cronograma;
- Novo campo de data da previsão de entrega ou disponibilização do bem;
- Novo evento relacionado à apuração de IBS e CBS: `Código 112150 - Atualização da Data de Previsão de Entrega`;
- Novas finalidades para as notas de débito/crédito;
- E expanção significativa das regras de validação;

### Nota Técnica 2025.002 v.1.31

[Clique para baixar a Nota Técnica 2025.002 v.1.31](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=xxtjiU7xjnk=)<br>
<span class="text-sm">Versão 1.31 - Publicada em 11/11/2025</span>

Principais alterações:

- Atualizações em regras de validação, como B25-80, B25-90, B25-100, Q01-20, S01-20, UB56-10 e VC02-30;
- Inclusão de observação explicativa nas regras de validação UB27-10, UB46-10 e UB65-10, sem impacto nas validações;
- Rejeição 1001 (para finalidade “Nota de Débito” e “Nota de Crédito”): estendida essa regra para operação de compra governamental, rejeitando a inclusão dos tributos atuais (ICMS, PIS, COFINS, ISS ou IPI). E criada uma exeção, não se aplicando essa regra quando a finalidade for “Nota de Crédito” e o tipo de crédito for `3 = Retorno`.
- Rejeições 745 e 748 (sem informações de PIS/COFINS): além das “Notas de Débito” e “Notas de Crédito”, a exceção para a exigência de PIS e COFINS passa a incluir a operação de compra governamental `tpOperGov = 2-Recebimento do pagamento`.

### Nota Técnica 2025.002 v.1.32

[Clique para baixar a Nota Técnica 2025.002 v.1.32](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=8H1QDj2ADhQ=)<br>
<span class="text-sm">Versão 1.32 - Publicada em 25/11/2025</span>

Correção nas regras de validação B25b-20, 3BA02-10, 3BA02-70 e NA01-20.

1️⃣ **B25b-20 – Operação não presencial na NFC-e**: essa validação rejeita emissão de NFC-e quando o indicador de presença (indPres) não corresponde a uma modalidade permitida para esse tipo de documento.

Antes da versão 1.32 a NFC-e só aceitva indPres igual a `1 – Operação presencial` ou `4 – Entrega a domicílio`.

A partir da versão 1.32, também será considerada válida a NFC-e emitida com `5 – Operação presencial fora do estabelecimento`

2️⃣ **3BA02-10 – Chave de acesso referenciada inexistente**: verifica se cada NF-e referenciada (refNFe) realmente existe na base da SEFAZ.

Exceções antes da versão 1.32:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3">
<span class="sm:text-sm text-xs text-[#8b5cf6]">NF-e emitida em contingência (tpEmis = 2, 4 ou 5) ou NFF (tpEmis = 3), desde que a referência seja de até um mês anterior ou exista o EPEC. Esta exceção não se aplica para NF-e com finalidade de crédito (tag: finNF-e = 5). </span>
</div>

A partir da versão 1.32, foi retirada a observação de que a exceção não se aplica para NF-e com finalidade de crédito. Sendo melhor especificado, através da definição dos tipos de nota de crédito para exceção:

- tpNFCredito = `01 – Multa e juros`
- tpNFCredito = `03 – Retorno`

Sendo mantida a exceção já existente para NF-e complementar (finNFe = 2).

3️⃣ **3BA02-70 – Validação em notas de crédito que a nota referenciada existe e não esteja cancelada**: essa regra se aplicava às notas de crédito (finNFe = 5) com tpNFCredito igual a `01 – Multa e juros` ou `03 – Retorno`. A partir da versão 1.32, a redação da regra foi modernizada e ficou mais objetiva:

<div class="text-left text-[#8b5cf6] gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 sm:hover:scale-105 hover:-translate-y-1 p-3">
<span class="sm:text-sm text-xs text-[#8b5cf6]">  - Para cada NF-e referenciada (tag:refNFe):

<ul>
      <li class="sm:text-sm text-xs text-[#8b5cf6] list-none">
      - Acessar BD NFE com Chave de Acesso referenciada (se mod=55)
      </li>
        <li class="sm:text-sm text-xs text-[#8b5cf6] list-none"> - Chave de acesso referenciada deve existir e não estar cancelada. 
        </li>
  </ul>
</span>
</div>

4️⃣ **NA01-20 – Exige o ICMSUFDest em operações interestaduais ao consumidor final**: a partir da versão 1.32 a regra também especifica que notas emitidas em operações governamentais classificadas como “recebimento do pagamento” passam a não exigir o grupo ICMSUFDest, evitando rejeições indevidas.

### Nota Técnica 2025.002 v.1.33

[Clique para baixar a Nota Técnica 2025.002 v.1.33](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=AklZnck3o6I=)<br>
<span class="text-sm">Versão 1.33 - Publicada em 02/12/2025</span>

Altera a data de início de aplicação da regra de validação UB12-10, regra que define a obrigatoriedade de preenchimento dos campos relativos ao IBS e à CBS.

O início dessa obrigatoriedade foi postergado para “Implementação futura”, ou seja, ainda sem data definida.

⚠️ Essa flexibilização assegura que a emissão de notas fiscais não será impedida, embora o preenchimento dos campos CBS e IBS permaneça obrigatório conforme a legislação.

### Nota Técnica 2025.002 v.1.34

[Clique para baixar a Nota Técnica 2025.002 v.1.34](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=IwLPdZ67F5M=)<br>
<span class="text-sm">Versão 1.34 - Publicada em 04/12/2025</span>

Última versão publicada com as seguintes alterações mais relevantes:

- 🚫 Regras de validação desabilitadas: UB26-15, UB45-15 e UB64-15.
- 🔄 Regras de validação alteradas: UB26-20, UB45-20, e UB64-20.

⚠️ A nova versão mantém o posicionamento da versão 1.33. Embora o não preenchimento dos campos do IBS e CBS não rejeite a emissão da nota fiscal, reforçamos que esses dados são obrigatórios a partir de 01/01/2026, conforme o art. 348 da Lei Complementar nº 214/2025.

Vamos seguir, apresentando abaixo, uma visão geral e atualizada de todo o escopo das adequações da NF-e e NFC-e.

## Cronograma

Em Produção, no ano de 2025 as informações de tributação relativas ao IBS, CBS e IS serão opcionais e somente serão validadas se forem preenchidas. A partir de janeiro de 2026, as novas regras de validação referentes a tributação do IBS e da CBS serão aplicadas, entrando em efetiva operacionalização.

<div>
  <span class="dark:text-white/90 relative">Detalhamento do Cronograma para CRT 3=Regime Normal:
    <i class="ph-light ph-info absolute -right-3 group">
      <div class="absolute left-3/4 -translate-x-2/4 bottom-full mb-2 sm:min-w-96 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
        As orientações para CRT 1-Simples Nacional, CRT 2-Simples Nacional-Excesso de Sublimite, CRT 4-MEI e Tributação Monofásica serão publicadas em NT futura, tendo em vista que a tributação do IBS/CBS/IS para estes contribuintes ocorre somente a partir de <code>2027</code>
      </div>
    </i>
  </span>
</div>

|            | Homologação                                                                  | Produção                                                                                                                                                                                                                                                  |
| ---------- | :--------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Julho/25   | IBS/CBS facultativo. Se preenchidos, as Regras de Validação serão aplicadas. | Campos do IBS/CBS ainda não implantados. Caso informados, ocasionará erro de schema.                                                                                                                                                                      |
| Outubro/25 | Idem Homologação Julho/25.                                                   | IBS/CBS facultativo. Se preenchidos, as RV serão aplicadas. <br><br> 💡Sem valor jurídico para os novos tributos.                                                                                                                                         |
| Janeiro/26 | Idem Homologação Julho/25.                                                   | Campos IBS/CBS não serão exigidos por regra de validação, porém permanece obrigatório conforme a legislação vigente. Para as NF-e e NFC-e com IBS/CBS as RV serão aplicadas. <br><br> ⚠️Com valor jurídico para os novos tributos a partir de 01/01/2026. |

## Nota de Débito e Crédito

Foram criadas duas novas finalidades de emissão da nota fiscal eletrônica:

- **Nota de débito**: documenta uma situação na qual o emitente registra um aumento no imposto devido (consequentemente, uma redução no imposto devido pelo adquirente, que é o destinatário);
- **Nota de crédito**: documenta uma situação na qual o emitente registra uma redução no imposto devido (consequentemente, um aumento no imposto devido pelo adquirente, que é o destinatário);

A NT cita que a regulamentação do IBS disporá sobre a utilização de notas de crédito e notas de débito para lançamentos de ajuste, com a finalidade de instrumentalizar a preparação da declaração assistida a ser oferecida para os contribuintes, de maneira automatizada, a partir de documentos fiscais eletrônicos, em cumprimento ao que preconiza a LC 214/2025.

Também, explica que as finalidades de "Nota de Ajuste" e "Nota Complementar" que já existem são casos especiais de "Nota de Débito". Já uma "Nota de Entada" emitida para documentar, por exemplo, a devolução de mercadoria que havia sido vendida para consumidor final é um caso especial de "Nota de Crédito".

Cabe destacar que em 09/12/2025 foi publicado o [Ajuste SINIEF 49/2025](https://www.confaz.fazenda.gov.br/legislacao/ajustes/2025/AJ049_25) compatibilizando a aplicação de notas de crédito e débito também com operações correlacionadas ao ICMS e IPI. Padronizando procedimentos para emissão de documentos fiscais em quatro situações comuns:

- 1 - Venda para entrega futura com pagamento antecipado;
- 2 - Perdas de estoque;
- 3 - Redução de valores ou quantidades quando o cancelamento da NF-e não é possível;
- 4 - Retorno por recusa ou não localização do destinatário.

## Código de Situação Tributária e Código de Classificação da Tributação

Os itens do documento fiscal devem ser classificados de acordo com o Código de Situação Tributária (CST) e o Código de Classificação Tributária (cClassTrib) do IBS, CBS e IS.

Essa tabela, publicada através do "Informe Técnico 2025.002 RTC", está disponível nos portais nacionais dos DF-es. E a classificação dos itens do documento deve ser realizada conforme as previsões legais da Reforma Tributária, vinculando os CST e cClassTrib com as regras de validação.

## Grupo de Identificação da Nota Fiscal Eletrônica

<div class="grid grid-cols-[minmax(0px,_0.94fr)_minmax(0px,_1fr)_minmax(0px,_1fr)] grid-rows-9 p-1 gap-2 ring-1 rounded ring-[#8b5cf6]">
  <div class="row-span-4 row-start-4 w-full flex gap-4 flex-col justify-center items-center">
    <i class="ph-bold ph-arrow-bend-up-right text-4xl text-green-700"></i>
    <div class="w-fit p-1 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500">Grupo B.</span>
      <span class="text-center text-xs text-gray-500">Identificação da NF-e</span>
    </div>
    <i class="ph-bold ph-arrow-bend-down-right text-4xl text-green-700"></i>
  </div>
  <div class="row-span-4 row-start-1 col-start-2 w-full flex gap-2 justify-start items-end">
    <div class="sm:min-w-44 flex flex-col gap-2">
      <span class="sm:min-w-44 text-center sm:text-sm text-xs whitespace-normal text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">dPrevEntrega
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Data da previsão de entrega ou disponibilização do bem. <br> Observação: Não informar este campo para a NFC-e.
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cMunFG
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código de ocorrência do fato gerador do ICMS. Utilizar a Tabela de código de Município do IBGE 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cMunFGIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Cód. do Município de consumo, fato gerador do IBS/CBS. <br>Preecher somente quando se tratar de operação presencial fora do estabelecimento (<code>indPress=5</code>), e não tiver endereço do destinatário (<code>Grupo E05</code>) ou local de entrega (<code>Grupo G01</code>).
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-gray-500 p-1 ring-1 rounded-xl shadow-md relative">finNFe
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Novas finalidades: 5=Nota de crédito 6=Nota de débito
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpNFDebito
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/3 -translate-x-1/3 bottom-full mb-2 min-w-72 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de Nota de Débito: <br>
            01=Transferência de créditos para Cooperativas; <br>
            02=Anulação de Crédito por Saídas Imunes/Isentas; <br>
            03=Débitos de notas fiscais não processadas na apuração; <br>
            04=Multa e juros; <br>
            05=Transferência de crédito de sucessão; <br>
            06=Pagamento antecipado; <br>
            07=Perda em estoque; <br>
            08=Desenquadramento do SN;
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpNFCredito
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/3 -translate-x-1/3 bottom-full mb-2 min-w-72 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de Nota de Crédito: <br>
            01 = Multa e juros; <br>
            02 = Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. <code>450, § 1º</code>, LC 214/25); <br>
            03=Retorno por recusa na entrega ou por não localização do destinatário na tentativa de entrega; <br>
            04=Redução de valores; <br>
            05=Transferência de crédito na sucessão; 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-3 row-start-7 col-start-2 flex justify-start items-center">
    <div class="flex flex-row gap-0.5">
      <span class="sm:min-w-44 text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCompraGov
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Compra Governamental
          </div>
        </i>
      </span>
      <svg 
        xmlns="http://www.w3.org/2000/svg" 
        width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-span-3 row-start-7 col-start-3 gap-1 pl-1 flex justify-start items-center">
    <div class="sm:min-w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpEnteGov
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de ente governamental:
              1=União <br>
              2=Estado <br>
              3=Distrito Federal 
              4=Município
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedutor
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual de redução de alíquota em compra governamental. Conforme <code>art. 472/370</code> da LC 214/24.
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpOperGov
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Tipo de operação com o ente governamental:
            1=Fornecimento <br>
            2=Recebimento do pagamento, conforme fato gerador do IBS/CBS definido no <code>Art. 10 §2º</code> da LC 214/25. 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-10 col-start-2 flex justify-start items-center">
    <div class="flex flex-row gap-0.5">
      <span class="sm:min-w-44 text-center sm:text-sm text-[0.6rem] whitespace-normal text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gPagAntecipado
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de notas de antecipação de pagamento
          </div>
        </i>
      </span>
      <svg 
        xmlns="http://www.w3.org/2000/svg" 
        width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-span-1 row-start-10 col-start-3 gap-1 sm:pl-1 pl-3 flex justify-start items-center">
    <div class="sm:min-w-44 min-w-20 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">refNFe
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Chave de acesso da NF-e de antecipação de pagamento. Podem ser referenciadas até 99 notas de antecipação de pagamento.
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

No `Grupo B. Identificação da Nota Fiscal Eletrônica` houve a inclusão de vários campos. Primeiro, o campo "Data da previsão de entrega ou disponibilização do bem" - `dPrevEntrega`, que de acordo com as regras de validação, poderá ser informado em notas com finalidade “1” (NF-e normal) ou “4” (Devolução de mercadoria), exceto quando a modalidade do frete for igual a "1" (Contratação do Frete por conta do Destinatário - FOB), "4" (Transporte Próprio por conta do Destinatário) ou "9" (Sem Ocorrência de Transporte). Na emissão da nota fiscal, esta data de previsão de entrega não pode ser superior a 3 meses a data de saída da nota, mas foi disponibilizado o novo evento `Código 112150 - Atualização da Data de Previsão de Entrega`, próprio para atualização desta data de previsão, de forma a remover o débito do mês em que foi previsto inicialmente.

O campo de Código do Município de consumo, fato gerador do IBS / CBS – `cMunFGIBS`, tem como finalidade informar o município de ocorrência do fato gerador dos tributos. Será preenchido quando o `indPres = 5 (Operação presencial, fora do estabelecimento)` e a nota fiscal não tiver informações do endereço do destinatário ou local de entrega.

Também consta o campo "Tipo de Nota de Débito" - `tpNFDebito`, com as seguintes opções possíveis:

- 01 = Transferência de créditos para Cooperativas;
- 02 = Anulação de Crédito por Saídas Imunes/Isentas;
- 03 = Débitos de notas fiscais não processadas na apuração;
- 04 = Multa e juros;
- 05 = Transferência de crédito de sucessão;
- 06 = Pagamento antecipado;
- 07 = Perda em estoque;
- 08 = Desenquadramento do SN

A opção `04=Multa e Juros` deverá ser usada nas emissões de notas fiscais para incidência dos tributos IBS e da CBS, quando ocorrer recebimento de juros e multas. O contribuinte que pagar a multa e os juros terá direito ao crédito dos tributos, por isso a necessidade de criação desse campo.

E a inclusão do campo "Tipo de Nota de Crédito" - `tpNFCredito`, com as seguintes opções possíveis:

- 01 = Multa e juros
- 02 = Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25)
- 03 = Retorno por recusa na entrega ou por não localização do destinatário na tentativa de entrega;
- 04 = Redução de valores;
- 05 = Transferência de crédito na sucessão;

A opção `01=Multa e Juros` deverá ser usada caso o fornecedor não emita a nota de débito referente o recebimento de juros e multas, onde o adquirente tem como alternativa emitir uma nota de crédito para se creditar. Esse crédito é condicionado à emissão do evento “Aceite de débito na apuração por emissão de nota de crédito” pelo fornecedor e a quitação do débito correspondente em sua apuração.

Foi também criado o subgrupo de Compra Governamental – `gCompraGov`. Junto a esse subgrupo, temos os seguintes campos:

- `tpEnteGov`: Tipo de ente governamental. Que poderá ser:
  - 1 = União
  - 2 = Estado
  - 3 = Distrito Federal
  - 4 = Município
- `pRedutor`: Percentual de redução de alíquota em compra governamental, conforme o art. 472/370 da LC 214/2024.
- `tpOperGov`: Tipo de operação com o ente governamental. Que pode ser:
  - 1=Fornecimento
  - 2=Recebimento do pagamento, conforme fato gerador do IBS/CBS definido no Art. 10 § 2ºd a LC 214/2024.

## Grupo de notas de antecipação de pagamento

Este grupo deverá ser utilizado para referênciar chaves de NF-e emitidas anteriormente, referente pagamentos antecipados.

- `gPagAntecipado`: Grupo de notas de antecipação de pagamento. Informado para abater as parcelas de antecipação de pagamento, conforme Art. 10. § 4º.
  - `refNFe`: Chave de acesso da NF-e de antecipação de pagamento. Pode ser informado até 99 chaves de NF-e.

Tendo as seguintes regras de validação:

- Rejeição: Chave de acesso referenciada deve existir e não estar cancelada;
- Rejeição: NF-e referenciada de pagamento antecipado informada indevidamente (caso informado para modelo 65 - NFC-e);
- Rejeição: NF-e referenciada de pagamento antecipado inexistente;
- Rejeição: NF-e referenciada de pagamento antecipado deve ser do tipo débito, pagamento antecipado.

## Bem móvel usado e tipo de crédito presumido na Zona Franca de Manaus

O grupo `Grupo I. Produtos e Serviços da NF-e` passa a ter dois novos campos:

- `tpCredPresIBSZFM` permitindo a classificação, para subapuração do crédito presumido do IBS na ZFM, conforme percentuais definidos no art. 450, § 1º, da LC 214/25:

  - 0 = Sem Crédito Presumido
  - 1 = Bens de consumo final (55%)
  - 2 = Bens de capital (75%)
  - 3 = Bens intermediários (90,25%)
  - 4 = Bens de informática e outros definidos em legislação (100%)

- `indBemMovelUsado` para identificar o fornecimento de bem móvel usado, adquirido de pessoa física que não seja contribuinte ou que seja inscrita como MEI.

## Alteração do ICMS normal e ICMS ST

As informações do ICMS da operação própria e ST passam a ter sua ocorrência opcional, pois será futuramente substituído pelo IBS.

⚠️ Precisamos lembrar de considerar a composição da base de cálculo do ICMS, pois isso não será citado em notas técnicas. Se não houver alteração, temos o IBS, CBS e IS compondo a base de cálculo do ICMS no período de transição. Leia o artigo [Reforma tributária: Impactos na Formação de Preços de Venda](https://papofiscal.blog/posts/reforma-tributaria-formacao-precos-de-venda) e saiba mais.

## Grupo de Informações dos Tributos IBS / CBS e IS

Novo grupo `UB. Informações dos tributos IBS / CBS e Imposto Seletivo`, contendo um série de campos relacionados aos novos tributos que deverão ser informados para cada item do documento, e o `Grupo VB. Total do item da NF-e` com o campo `vItem`.

### Esquema gráfico do leiaute, contemplando os grupos de campos do IBS, CBS e Imposto Seletivo.

<div class="grid grid-cols-[minmax(0px,_1fr)_minmax(0px,_0.85fr)_minmax(0px,_1fr)]
  p-1 gap-1 ring-1 rounded ring-0.8b5cf6] overflow-hidden">
  <div class="row-span-2 row-start-1 col-start-1 flex gap-4 flex-col justify-end items-center">
    <div class="w-full max-w-44 min-w-28 p-2 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500">infNFe</span>
    </div>
    <i class="ph-bold ph-arrow-down text-4xl text-green-700"></i>
  </div>
  <div class="row-span-3 row-start-3 col-start-1 flex gap-4 flex-col justify-center items-center">
    <div class="max-w-44 min-w-28 p-2 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500">Grupo H.</span>
      <span class="text-center text-xs text-gray-500">Detalhamento Produtos e Serviços</span>
    </div>
    <i class="ph-bold ph-arrow-down text-4xl text-green-700"></i>
  </div>
  <div class="row-start-6 col-start-1 row-span-3 flex flex-col">
    <div class="w-full flex flex-row gap-0.5 justify-center items-center">
      <span class="grow max-w-44 min-w-24 ml-0 sm:ml-6 text-center text-sm text-gray-500 p-1 border rounded-lg shadow-md relative">prod</span>
      <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-start-6 col-start-2 w-full flex justify-start items-center">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center sm:text-sm text-[0.5rem] text-gray-500 p-1 border rounded-xl shadow-md relative">...
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 translate-x-0 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm text-center rounded px-2 py-1 shadow-lg">
            Campos de produto/serviço já existentes. 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex justify-start items-center pt-0.5">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center sm:text-xs text-[0.54rem] text-[#8b5cf6] p-1 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">indBemMovelUsado
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 translate-x-0 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Ientifica o fornecimento de bem móvel usado, adquirido de pessoa física que não seja contribuinte ou que seja inscrita como MEI
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-8 col-start-2 w-full flex justify-start items-center pt-0.5">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center sm:text-xs text-[0.54rem] text-[#8b5cf6] p-1 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpCredPresIBSZFM
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-24 bottom-full mb-2 sm:min-w-96 min-w-72 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Classificação para subapuração do crédito presumido do IBS na ZFM:
            <ul>
              <li><code>0 = Sem Crédito Presumido</code></li>
              <li><code>1 = Bens de consumo final (55%) </code></li>
              <li><code>2 = Bens de capital (75%) </code></li>
              <li><code>3 = Bens intermediários (90,25%) </code></li>
              <li><code>4 = Bens de informática e outros definidos em legislação (100%)</code></li>
            </ul>
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-9 row-span-11 col-start-1">
    <div class="w-full flex flex-row gap-0.5 justify-center items-center">
      <span class="grow max-w-44 min-w-24 ml-0 sm:ml-6 text-center text-sm text-gray-500 p-1 border rounded-lg shadow-md relative">imposto</span>
      <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-start-9 col-start-2 w-full flex justify-start items-center pt-0.5">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md relative">...
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 translate-x-0 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm text-center rounded px-2 py-1 shadow-lg">
            Grupos dos tributos já existentes 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-10 col-start-2 w-full flex justify-start items-center pt-0.5">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">IS
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 translate-x-0 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Novo grupo referente informações do Imposto Seletivo 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-12 col-start-2 w-full flex justify-start items-start pt-0.5">
    <div class="w-full flex flex-row gap-0.5">
      <span class="grow max-w-40 min-w-20 pl-4 text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">IBSCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 translate-x-0 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Novo grupo referente informações do Imposto de Bens e Serviços - IBS e da Contribuição de Bens e Serviços - CBS
          </div>
        </i>
      </span>
      <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-span-8 row-start-12 col-span-1 col-start-3 w-full gap-1 flex justify-start items-start">
    <div class="w-full max-w-40 min-w-20 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">CST
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Código de Situação Tributária do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cClassTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Código de Classificação Tributária do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">indDoacao
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Indica a natureza da operação de doação, orientando a apuração e a geração de débitos ou estornos conforme o cenário
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBS
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo de Informações do IBS e da CBS
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-[0.6rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBSMono
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo de Informações do IBS e CBS em operações com imposto monofásico
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-[0.6rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gTransfCred
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo para informação de transferências de crédito
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-[0.54rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gAjusteCompet
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-2/4 -translate-x-2/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo para Ajuste de Competência. <br>A obrigatoriedade ou vedação do preenchimento deste grupo está condicionada ao indicador “ind_gAjusteCompet” da tabela CST do IBS e da CBS. 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-[0.54rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gEstornoCred
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-2/4 -translate-x-2/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo para Estorno de Crédito. <br>A obrigatoriedade ou vedação do preenchimento deste grupo está condicionada ao indicador “ind_gEstornoCred” da tabela cClassTrib do IBS e da CBS. 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-[0.54rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCredPresOper
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-2/4 -translate-x-2/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo para Crédito Presumido da Operação. <br>A obrigatoriedade ou vedação do preenchimento deste grupo está condicionada ao indicador “ind_gCredPresOper” da tabela cClassTrib do IBS e da CBS. O valor "1" do indicador “ind_gCredPresOper” significa que o contribuinte pode utilizar o crédito presumido, sem obrigatoriedade (permite, mas não exige). 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-[0.54rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCredPresIBSZFM
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-2/4 -translate-x-2/4 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo para apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM <code>(art. 450, § 1º, LC 214/25)</code>. <br>A obrigatoriedade ou vedação do preenchimento deste grupo está condicionada ao indicador “ind_gCredPresIBSZFM” da tabela CST do IBS e da CBS.  
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="col-start-1 flex flex-col justify-center items-center">
    <div class="w-full max-w-44 min-w-28 p-1 flex flex-col ring-1 ring-[#8b5cf6] rounded-lg shadow-md">
      <span class="text-center text-sm text-[#8b5cf6] relative">vItem
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 translate-x-0 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Valor total do Item, considerando tributos e despesas, correspondente à sua participação no total da nota. A soma dos itens deverá corresponder ao total da nota. 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

### Campos do Imposto Seletivo

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_1fr)] p-4 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-28 flex justify-center p-2 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center text-sm text-[#8b5cf6]">IS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Informações do Imposto Seletivo 
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-end">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">CSTIS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Código de Situação Tributária do Imposto Seletivo 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cClassTribIS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Código de Classificação Tributária do Imposto Seletivo 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vBCIS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Valor da Base de Cálculo do Imposto Seletivo 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pIS
      <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Alíquota do Imposto Seletivo 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pISEspec
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Alíquota específica por unidade de medida apropriada  
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">uTrib
      <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Unidade de Medida Tributável  
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">qTrib
      <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Quantidade Tributável  
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIS
      <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Valor do Imposto Seletivo
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

### Grupo do IBS e CBS

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_1fr)] grid-rows-1 p-4 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-28 flex flex-col gap-2 justify-center p-2 ring-1 ring-[#8b5cf6] rounded-lg shadow-md">
      <span class="text-center text-sm text-[#8b5cf6] relative">gIBSCBS
        <i class="ph-light ph-info absolute left-0 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do IBS e CBS
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vBC
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Base de cálculo do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSUF
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para a UF
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSMun
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para o Município
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS (soma de vIBSUF e vIBSMun)
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCBS
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gTribRegular
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da Tributação Regular.
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gTribCompraGov
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da composição do valor do IBS e da CBS em compras governamentais 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

#### Campos do IBS da UF

<div class="grid grid-cols-3 p-2 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-7 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 sm:pl-14 justify-end items-center">
    <div class="w-full flex justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center text-sm text-[#8b5cf6]">gIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para a UF
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota do IBS de competência das UF
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-2 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Diferimento
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-2 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do diferimento
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Diferimento
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-4 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/3 bottom-full mb-2 min-w-64 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da devolução de tributos no fornecimento de energia elétrica, água, esgoto, gás natural e em outras hipóteses definidas no regulamento.
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-start-4 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do tributo devolvido (“cashback” de desconto na própria Nota Fiscal / Fatura) 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-5 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gRed
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da redução da alíquota
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-5 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota do cClassTrib
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-left rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva do IBS de competência das UF aplicada a Base de Cálculo <br><br>
            Se for compra governamental: <br> 
              <code>pAliqEfet = pIBSUF x (1 – pRedAliq) x (1 - gCompraGov/pRedutor) </code> 
            Senão:<br> 
              <code>pAliqEfet = pIBSUF x (1 – pRedAliq)</code>
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/3 bottom-full mb-2 min-w-64 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS de competência da UF  <br><br>
            Se grupo gRed preenchido:<br>
                <code>vIBSUF = (vBC x gRed/pAliqEfet) - vDif - vDevTrib</code><br>
            Senão:<br> 
                <code>vIBSUF = (vBC x pIBSUF) - vDif - vDevTrib</code>
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

#### Campos do IBS dos Municípios

<div class="grid grid-cols-3 p-2 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-7 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 sm:pl-14 justify-end items-center">
    <div class="w-full flex justify-center p-2 pl-5 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center text-sm text-[#8b5cf6]">gIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para o município
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota do IBS de competência do Município
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-2 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Diferimento
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-2 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do diferimento
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Diferimento
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-4 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da devolução de tributos
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-start-4 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do tributo devolvido (“cashback” de desconto na Fatura) 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-5 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gRed
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da redução da alíquota
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-5 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota do cClassTrib
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-left rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva do IBS de competência do Município aplicada a Base de Cálculo <br><br>
            Se for compra governamental: <br> 
              <code>pAliqEfet = pIBSMun x (1 – pRedAliq) x (1 - gCompraGov/pRedutor) </code> 
            Senão:<br> 
              <code>pAliqEfet = pIBSMun x (1 – pRedAliq)</code>
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/3 bottom-full mb-2 min-w-60 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS de competência do Município.  <br><br>
            Se grupo gRed preenchido:<br>
                <code>vIBSMun = (vBC x gRed/pAliqEfet) - vDif - vDevTrib</code><br>
            Senão:<br> 
                <code>vIBSMun = (vBC x pIBSUF) - vDif - vDevTrib</code>
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

#### Campos da CBS

<div class="grid grid-cols-3 p-2 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-7 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 sm:pl-14 justify-end items-center">
    <div class="w-full flex justify-center p-2 pl-5 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center text-sm text-[#8b5cf6]">gCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da CBS
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota da CBS
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-2 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Diferimento
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-2 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do diferimento
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Diferimento
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-4 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da devolução de tributos
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-start-4 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do tributo devolvido (“cashback” de desconto na Fatura) 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-5 col-start-2 w-full gap-1 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gRed
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da redução da alíquota
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-5 col-start-3 w-full flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-0.5 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva da CBS aplicada a Base de Cálculo  
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

#### Grupo de informações da Tributação Regular

Informar como seria a tributação caso não cumprida a condição resolutória/suspensiva. Por exemplo, em operações com ZFM e ALC, ou em operações com suspensão do tributo. A obrigatoriedade ou vedação do
preenchimento deste grupo está condicionada ao indicador “ind_gTribRegular” da tabela de cClassTrib do IBS e da CBS.

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 px-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] group">gTribRegular
        <i class="ph-light ph-info absolute left-1 ">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da Tributação Regular
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">CSTReg
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Código de Situação Tributária do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cClassTribReg
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código de Classificação Tributária do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfetRegIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da alíquota do IBS da UF
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribRegIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Tributo do IBS da UF
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfetRegIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da alíquota do IBS do Município
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribRegIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Tributo do IBS do Município
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfetRegCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da alíquota da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribRegCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Tributo da CBS
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

#### Campos do IBS e da CBS em Compras Governamentais

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] group">gTribCompraGov
        <i class="ph-light ph-info absolute left-1">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da composição do valor do IBS e da CBS em compras governamentais
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Alíquota do IBS de competência do Estado 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor que seria devido a UF, sem aplicação do <code>Art. 473. da LC 214/2025 </code>
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota do IBS de competência do Município 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor que seria devido ao município, sem aplicação do <code>Art. 473. da LC 214/2025 </code>
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota da CBS 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor que seria devido de CBS, sem aplicação do <code>Art. 473. da LC 214/2025 </code>
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

### Campos do IBS e CBS Monofásico

<div class="grid grid-cols-[minmax(0px,_1fr)_minmax(0px,_1fr)]
            p-2 gap-4 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-col gap-1 justify-end items-start sm:items-end">
    <div class="w-40 sm:w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBSMono
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do IBS e CBS em operações com imposto monofásico
          </div>
        </i>
      </span>
    </div>
    <div class="w-40 sm:w-44 flex flex-col items-center">
      <i class="ph-bold ph-arrow-down text-4xl text-green-700"></i>
    </div>
  </div>
  <div class="row-span-1 row-start-2 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-32 sm:w-36 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gMonoPadrao
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da Tributação Monofásica Padrão (Monofasia dos Combustíveis)
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-2 col-span-1 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">qBCMono
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Quantidade tributada na monofasia
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem do IBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíqutoa ad rem da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMono
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS monofásico
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBSMono
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS monofásica
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-32 sm:w-36 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gMonoReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Uso em operações com combustíveis derivados de petróleo (Gasolina A ou Óleo Diesel A) para retenção do imposto sobre o biocombustível a ser misturado. Art 178 LC 214/25. 
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-3 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">qBCMonoReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Quantidade tributada sujeita à retenção na monofasia  
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemIBSReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem do IBS sujeito a retenção 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMonoReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS monofásico sujeito a retenção, a ser somado ao valor de IBS a ser recolhido. 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemCBSReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem da CBS sujeito a retenção 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBSMonoReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS monofásica sujeita a retenção, a ser somado ao valor de CBS a ser recolhido. 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-4 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-32 sm:w-36 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gMonoRet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Tributação monofásica própria sobre combustíveis retida anteriormente.
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-4 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">qBCMonoRet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Quantidade tributada retida anteriormente  
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemIBSRet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem do IBS retido anteriormente 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMonoRet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS retido anteriormente
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemCBSRet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem da CBS retida anteriormente 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBSMonoRet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS retida anteriormente 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-5 col-start-1 w-full gap-1 pt-1 flex justify-end items-start">
    <div class="w-32 sm:w-36 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gMonoDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Operações com diferimento, aplicado aos biocombustíveis. Exemplo: operação do produtor de biocombustível (usina).  
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-5 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pDifIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do diferimento do imposto monofásico. 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMonoDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS monofásico diferido, a ser deduzido do valor do IBS.
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pDifCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do diferimento do imposto monofásico 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBSMonoDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS Monofásica diferida, a ser deduzido do valor da CBS.
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-6 col-start-1 w-full flex gap-2 justify-end items-start sm:items-end">
    <div class="w-40 sm:w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTotIBSMonoItem
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Total de IBS Monofásico.
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTotCBSMonoItem
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Total da CBS Monofásica.
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

### Campos de Transferências de Crédito

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] group">gTransfCred
        <i class="ph-light ph-info absolute left-1">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Transferências de Crédito 
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Valor do IBS a ser transferido 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS a ser transferida
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

### Campos para Ajuste de Competência

A obrigatoriedade ou vedação do preenchimento deste grupo está condicionada ao indicador “ind_gAjusteCompet” da tabela de CST do IBS e da CBS.

<div class="grid grid-cols-[minmax(0px,_1fr)_minmax(0px,_1fr)]
            p-2 sm:gap-4 gap-1 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-col gap-1 mb-4 justify-between items-end">
    <div class="flex gap-1">
      <span class="sm:w-44 w-32 text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gAjusteCompet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/3 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo dos campos de ajuste de competência
          </div>
        </i>
      </span>
      <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
    <div class="w-40 sm:w-44 flex flex-col items-center sm:mr-4 mr-2">
      <i class="ph-bold ph-arrow-down text-4xl text-green-700"></i>
    </div>
  </div>
  <div class="row-start-1 col-span-1 col-start-2 w-full gap-1 mb-4 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">competApur
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Ano e mês referência do período de apuração <br>(AAAA-MM) 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-2 col-start-1 w-full gap-1 mb-4 flex justify-end items-start">
    <div class="w-36 sm:w-40 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gEstornoCred
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/3 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Estorno de Crédito
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-2 col-span-1 col-start-2 w-full mb-4 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSEstCred
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS a ser estornado
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBSEstCred
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da CBS a ser estornada
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-1 w-full gap-1 mb-4 flex justify-end items-start">
    <div class="w-36 sm:w-40 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCredPresOper
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/3 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Crédito Presumido da Operação
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-3 col-start-2 w-full mb-4 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vBCCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da Base de Cálculo do Crédito Presumido da Operação 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código de Classificação do Crédito Presumido
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-4 col-start-1 w-full gap-1 mb-4 flex justify-end items-start">
    <div class="w-36 sm:w-40 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/3 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido do IBS, quando aproveitado pelo emitente do documento.
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-4 col-start-2 w-full mb-4 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido Condição Suspensiva. Preencher apenas para cCredPres com indicação de Condição Suspensiva. 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-5 col-start-1 w-full gap-1 mb-4 flex justify-end items-start">
    <div class="w-36 sm:w-40 flex flex-col gap-2 grow-0">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gCBSCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/3 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido da CBS, quando aproveitado pelo emitente do documento. 
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-5 col-start-2 w-full mb-4 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido Condição Suspensiva. Preencher apenas para cCredPres com indicação de Condição Suspensiva.  
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-6 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-36 sm:w-40 flex flex-col gap-2 grow-0">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gCredPresIBSZFM
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/3 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo para apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM <code>(art. 450, § 1º, LC 214/25)</code> 
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-6 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">competApur
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Ano e mês referência do período de apuração, seja atual ou retroativo. (AAAA-MM)
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpCredPresIBSZFM
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-72 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Tipo de classificação conforme percentuais definidos no <code>art. 450, § 1º, da LC 214/25</code> para cálculo do crédito presumido na ZFM: <br>
              <ul class="flex flex-col text-start">
                <li><code>0 - Sem Crédito Presumido</code></li>
                <li><code>1 - Bens de consumo final (55%)</code></li>
                <li><code>2 - Bens de capital (75%)</code></li>
                <li><code>3 - Bens intermediários (90,25%)</code></li>
                <li><code>4 - Bens de informática e outros definidos em legislação (100%)</code></li>
              </ul>
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresIBSZFM
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do crédito presumido calculado sobre o saldo devedor apurado 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

## Referenciamento de item de outra NF-e

O `Grupo VC. Referenciamento de item de outro Documento Fiscal Eletrônico - DF-e` para as informações:

- `DFeReferenciado` - Grupo para Documento Fiscal Eletrônico Referenciado
  - `chaveAcesso` - Chave de acesso do DF-e referenciado
  - `nItem` - Número do item do documento referenciado.

## Grupo de Total da NF-e

Novo `Grupo W03. Total da NF-e - IBS / CBS / IS` contendo campos totalizadores.

**`ISTot` Grupo total do imposto seletivo**

- `vIS`: Total do imposto seletivo

**`IBSCBSTot` Totais da NF-e com IBS e da CBS**

- `vBCIBSCBS`: Valor total da BC do IBS e da CBS

- `gIBS` **Grupo de Totais do IBS**:

  - `gIBSUF` _Grupo total do IBS do Estado_:

    - `vDif`: Valor total do diferimento
    - `vDevTrib`: Valor total de devolução de tributos
    - `vIBSUF`: Valor total do IBS da UF

  - `gIBSMunTot` _Grupo total do IBS do Município_:

    - `vDif`: Valor total do diferimento
    - `vDevTrib`: Valor total de devolução de tributos
    - `vIBSMun`: Valor total do IBS da UF

- `vIBS`: Valor total do IBS
- `vCresPres`: Valor total do crédito presumido
- `vCredPresCondSus`: Valor total do crédito presumido em condição suspensiva

- `gCBS` **Grupo total da CBS**:

  - `vDif` Valor total do diferimento
  - `vDevTrib` Valor total de devolução de tributos
  - `vCBS` Valor total da CBS
  - `vCresPres` Valor total do crédito presumido
  - `vCredPresCondSus` Valor total do crédito presumido em condição suspensiva

- `gMono` **Grupo total da Monofasia**:

  - `vIBSMono`: Total do IBS monofásico
  - `vCBSMono`: Total da CBS monofásica
  - `vIBSMonoReten`: Total do IBS monofásico sujeito a retenção
  - `vCBSMonoReten`: Total da CBS monofásico sujeito a retenção
  - `vIBSMonoRet`: Total do IBS monofásico retido anteriormente
  - `vCBSMonoReten`: Total da CBS monofásico retido anteriormente

- `gEstornoCred` **Grupo total do Estorno de Crédito**:
  - `vIBSEstCred`: Valor total do IBS estornado
  - `vCBSEstCred`: Valor total da CBS estornada

`vNFTot`: Valor total da NF-e com IBS / CBS / IS

## Regras de Validação

Diversas regras de validação foram criadas. Destacam-se a rejeição caso não informados os dados do grupo dos tributos IBS e CBS e a validação do valor total da NF-e/NFC-e, que vai considerar os valores de IS, IBS, CBS, IBS monofásico e CBS monofásica como parte integrante do total do documento. Mas no ano de 2026, está prevista a exceção dos novos tributos serem somados no valor total da nota, permitindo as empresas e os sistemas de gestão utilizar esse período para adaptações.

Apesar de adiada para ativação futura a regra de validação sobre o não preenchimento dos campos do IBS e CBS, que rejeitaria a emissão da nota fiscal, esses dados são obrigatórios a partir de 01/01/2026 conforme o art. 348 da Lei Complementar nº 214/2025. Por isso, recomendamos a adequação imediata para garantir a conformidade legal.

Desta forma, as principais rejeições automáticas das notas fiscais no ano de 2026 incluem:

- Rejeição 1026: Alíquota do IBS da UF diferente de 0,1% para documentos emitidos em 2026.
- Rejeição 1037: Alíquota da CBS diferente de 0,9% para documentos emitidos em 2026.

## DANFE

Alterações no DANFE para exibir informações relativas aos novos tributos estão em estudo. E serão publicadas em uma nova versão desta Nota Técnica.

## Pacote de Schemas

A NT cita que em busca de uma padronização entre os diversos documentos fiscais eletrônicos existentes, introduz o arquivo “DFeTiposBasicos_v1.00.xsd” ao conjunto dos arquivos que compõem o schema de todos os Documentos Fiscais Eletrônicos - DF-e, entre eles a NF-e e NFC-e.

Esse pacote de schemas é muito útil para as adaptações necessárias nos softwares, com finalidade de construção e leitura dos arquivos. Podemos encontrá-lo no Portal da Nota Fiscal Eletrônica, no menu "Documentos\Esquemas XML", com o nome:

- ~~Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010a (Novo leiaute da NF-e, NT 2025.002 v.1.01) (ZIP).-~~ Publicado em 15/04/2025 `(versão em desuso)`
- ~~Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010b (Novo leiaute da NF-e, NT 2025.002 v.1.10, NT 2024.003 e NT 2025.001) (ZIP).~~ Publicado em 09/06/2025 `(versão em desuso)`
- ~~Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010b (Novo leiaute da NF-e, NT 2025.002 v.1.20, NT 2024.003 e NT 2025.001) (ZIP).~~ Publicado em 30/07/2025 `(versão em desuso)`
- ~~Esquema XML NF-e/NFC-e - Schema dos eventos da NT 2025.002 v.1.20 - RTC (ZIP).~~ Publicado em 18/08/2025 `(versão em desuso)`
- ~~Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010b v. 1.21 (Novo leiaute da NF-e, NT 2025.002 v.1.20, NT 2024.003 e NT 2025.001) (ZIP).~~ Publicado em 20/08/2025 `(versão em desuso)`
- **Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010b v. 1.30 (Novo leiaute da NF-e, NT 2025.002 v.1.30, NT 2024.003 e NT 2025.001) (ZIP).** Publicado em 07/10/2025
- **Esquema XML NF-e/NFC-e - Schema dos eventos da NT 2025.002 v.1.30 - RTC (ZIP).** Publicado em 07/10/2025 - Atualizado em 30/10/2025

## Novos Eventos

Criação de novos eventos destinados a ajustar a apuração assistida do IBS e da CBS. Permitindo que em certos casos específicos as empresas informem o direito ao crédito fiscal ou realizem o estorno de créditos indevidamente apropriados.

| Código | Evento                                                                                             |           Autor            |
| ------ | :------------------------------------------------------------------------------------------------- | :------------------------: |
| 112110 | Informação de efetivo pagamento integral para liberar crédito presumido do adquirente              |          Emitente          |
| 112120 | Importação em ALC/ZFM não convertida em isenção                                                    |          Emitente          |
| 112130 | Perecimento, perda, roubo ou furto durante o transporte contratado pelo fornecedor                 |          Emitente          |
| 112140 | Fornecimento não realizado com pagamento antecipado                                                |          Emitente          |
| 112150 | Atualização da Data de Previsão de Entrega                                                         |          Emitente          |
| 211110 | Solicitação de Apropriação de crédito presumido                                                    |        Destinatário        |
| 211120 | Destinação de item para consumo pessoal                                                            |   Emitente Destinatário    |
| 211124 | Perecimento, perda, roubo ou furto durante o transporte contratado pelo adquirente                 |        Destinatário        |
| 211128 | Aceite de débito na apuração por emissão de nota de crédito                                        |        Destinatário        |
| 211130 | Imobilização de Item                                                                               |        Destinatário        |
| 211140 | Solicitação de Apropriação de Crédito de Combustível                                               |        Destinatário        |
| 211150 | Solicitação de Apropriação de Crédito para bens e serviços que dependem de atividade do adquirente |        Destinatário        |
| 212110 | Manifestação sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão              |         Sucessora          |
| 212120 | Manifestação sobre Pedido de Transferência de Crédito CBS em Operações de Sucessão                 |         Sucessora          |
| 412120 | Manifestação do Fisco sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão     |           Fisco            |
| 412130 | Manifestação do Fisco sobre Pedido de Transferência de Crédito de CBS em Operações de Sucessão     |           Fisco            |
| 110001 | Cancelamento de Evento (para cancelar algum dos eventos citados acima)                             | Autor do evento a cancelar |

O evento de “Imobilização de Item” por exemplo, deverá ser gerado pelo adquirente de bem, quando este for integrado ao seu ativo imobilizado, a fim de viabilizar o controle do prazo de 180 dias para apreciação dos pedidos de ressarcimento do respectivo crédito, caso apurar saldo a recuperar nos termos do art. 39 e 40, I da LC 214/2025.

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
