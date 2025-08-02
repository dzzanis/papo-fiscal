---
author: Papo Fiscal
pubDatetime: 2025-07-12T07:16:00Z
title: Versão 1.10 da Nota Técnica 2025.002 - Adequações da NF-e à reforma tributária
slug: reforma-tributaria-nf-e-nt-2025-002-v1.10
featured: false
draft: false
tags:
  - Reforma Tributária
  - Nota Técnica
  - DF-e
  - NF-e
  - NFC-e
description: Novas definições apresentadas pela Nota Técnica 2025.002 v.1.10 para adequação da NF-e à reforma tributária. Notas sem IBS e CBS serão rejeitadas a partir de janeiro de 2026, exceto para empresas do Simples Nacional e MEIs com obrigatoriedade a partir de 2027.
---

O Portal da Nota Fiscal Eletrônica divulgou a versão 1.10 da Nota Técnica nº 2025/002, trazendo mais atualizações nas regras de emissão de NF-e e NFC-e em razão da Reforma Tributária.

Entre as principais alterações destaca-se a dispensa das empresas do Simples Nacional e os MEIs de preencher os novos campos de IBS e CBS nas NF-e e NFC-e, nas emissões realizadas ao longo de 2026. A obrigatoriedade para o Simples Nacional passará a valer a partir de janeiro de 2027. Esta alteração compatibiliza as regras de validação a dispensa prevista no artigo 348, inciso III, alínea “c” da Lei Complementar 214/2025.

Outro destaque é a criação do grupo específico de informações que envolvem antecipação de pagamento. Para referenciar os documentos fiscais relacionados às antecipações financeiras ocorridas antes da efetiva entrega de mercadorias ou prestação de serviços. Por exemplo, casos de operações de venda com entrega futura, nas quais o comprador realiza pagamentos e aguarda a disponibilidade dos bens adquiridos.

Já foram publicadas diversas notas técnicas apresentando adequações dos leiautes dos DF-es (NF-e, NFC-e, CT-e, CT-e OS, BP-e, NF3-e, NFCom e NFS-e Nacional) à reforma tributária,que entrarão em vigor em [1º de janeiro de 2026](https://papofiscal.blog/posts/reforma-tributaria-cronograma/). Vamos aqui conhecer os novos campos e regras da NF-e apresentado pela Nota Técnica 2025.002.

## Sumário

## RT - Nota Técnica 2024.002

[Clique para baixar a RT - Nota Técnica 2024.002](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=DaB0yzqdbRU=)<br>
<span class="text-sm">Versão 1.10 - Publicada em 6 de dezembro de 2024</span>

Esta foi a primeira nota técnica definida conjuntamente entre os Estados, Municípios e Receita Federal do Brasil, modificando o leiaute da NF-e (modelo 55) e NFC-e (modelo 65). Inserindo os grupos e campos relacionados a tributação do Imposto sobre Bens e Serviços (IBS), Contribuição sobre Bens e Serviços (CBS) e Imposto Seletivo (IS), em atendimento as alterações previstas na EC 132/2023 para implementação da Reforma Tributária.

A versão 1.0 publicada em 01 de agosto de 2024 continha 41 páginas. Já a versão 1.10 de 06 de dezembro, passou a compor 67 páginas. Descrevendo além de novos campos, uma série de regras de validação e novos eventos.

## Nota Técnica 2025.002

[Clique para baixar a Nota Técnica 2025.002 v1.01](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=wuVuolIzJLs=)<br>
<span class="text-sm">Versão 1.01 - Publicada em 15 de abril de 2025</span>

Esta Nota Técnica substituiu a RT NT 2024.002, atualizando as definições dos novos eventos, regras de validação e leiaute da NF-e e NFC-e referente à Reforma Tributária do Consumo.

A versão 1.00 publicada em 28 de março de 2025 continha 48 páginas. Já a versão 1.01 de 14 de abril, passou a compor 50 páginas.

## Nota Técnica 2025.002 v.1.10

[Clique para baixar a Nota Técnica 2025.002 v.1.10](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=B7DBKw%20UPbs=)<br>
<span class="text-sm">Versão 1.10 - Publicada em 9 de junho de 2025</span>

Esta versão acresenta várias atualizações, como novos campos, cria e altera regras de validação, e cria novos eventos para apuração do IBS/CBS, passando a compor 66 páginas.

Mas vamos seguir, apresentando abaixo, uma visão geral e atualizada de todo o escopo das adequações da NF-e e NFC-e.

## Cronograma

Em Produção, no ano de 2025 as informações de tributação relativas ao IBS, CBS e IS serão opcionais e somente serão validadas se forem preenchidas. A partir de janeiro de 2026, as novas regras de validação referentes a tributação do IBS e da CBS serão aplicadas, entrando em efetiva operacionalização.

| Atualizações                                                                                            |   Homologação    | Produção |
| :------------------------------------------------------------------------------------------------------ | :--------------: | :------: |
| Implantação de novo schema com os campos para apuração do IBS, CBS e IS, com preenchimento opcional.    | 07/07 a 28/07/25 | 06/10/25 |
| Aplicação das regras de validação, conforme detalhamento do cronograma abaixo.                          | 07/07 a 11/08/25 | 06/10/25 |
| Implantação dos eventos para utilização na apuração do IBS, CBS e IS.                                   |     04/08/25     | 06/10/25 |
| Início da obrigatoriedade da informação dos novos tributos, conforme detalhamento do cronograma abaixo. |     06/10/25     | 05/01/26 |

Detalhamento do Cronograma:

|            | Homologação                                                                                             | Produção                                                                                                                                                                                    |
| ---------- | :------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Julho/25   | IBS/CBS facultativo. Se preenchidos, as Regras de Validação serão aplicadas.                            | Campos do IBS/CBS ainda não implantados. Caso informados, ocasionará erro de schema.                                                                                                        |
| Outubro/25 | IBS/CBS obrigatórios para NF-e com data de emissão maior ou igual a 06/10/2025 e as RV serão aplicadas. | IBS/CBS facultativo. Se preenchidos, as RV serão aplicadas. <br><br> 💡Sem valor jurídico para os novos tributos.                                                                           |
| Janeiro/26 | Idem Homologação Outubro/25.                                                                            | Campos IBS/CBS obrigatórios para NF-e com data de emissão maior ou igual a 05/01/2026 e as RV serão aplicadas. <br><br> ⚠️Com valor jurídico para os novos tributos a partir de 01/01/2026. |

## Nota de Débito e Crédito

Foram criadas duas novas finalidades de emissão da nota fiscal eletrônica:

- **Nota de débito**: documenta uma situação na qual o emitente registra um aumento no imposto devido (consequentemente, uma redução no imposto devido pelo adquirente, que é o destinatário);
- **Nota de crédito**: documenta uma situação na qual o emitente registra uma redução no imposto devido (consequentemente, um aumento no imposto devido pelo adquirente, que é o destinatário);

A NT cita que a regulamentação do IBS disporá sobre a utilização de notas de crédito e notas de débito para lançamentos de ajuste, com a finalidade de instrumentalizar a preparação da declaração assistida a ser oferecida para os contribuintes, de maneira automatizada, a partir de documentos fiscais eletrônicos, em cumprimento ao que preconiza a LC 214/2025.

Também, explica que as finalidades de "Nota de Ajuste" e "Nota Complementar" que já existem são casos especiais de "Nota de Débito". Já uma "Nota de Entada" emitida para documentar, por exemplo, a devolução de mercadoria que havia sido vendida para consumidor final é um caso especial de "Nota de Crédito".

Cabe destacar que, a menos que ocorra uma alteração na regulamentação do ICMS e do IPI, estas notas de crédito e notas de débito não serão utilizadas para ajustes destes tributos.

## Código de Situação Tributária e Código de Classificação da Tributação

Os itens do documento fiscal devem ser classificados de acordo com o Código de Situação Tributária (CST) e o Código de Classificação Tributária (cClassTrib) do IBS, CBS e IS.

Essa tabela, publicada através do "Informe Técnico 2025.002 RTC", está disponível nos portais nacionais dos DF-es. E a classificação dos itens do documento deve ser realizada conforme as previsões legais da Reforma Tributária, vinculando os CST e cClassTrib com as regras de validação.

## Grupo de Identificação da Nota Fiscal Eletrônica

No `Grupo B. Identificação da Nota Fiscal Eletrônica` houve a inclusão do campo de Código do Município de consumo, fato gerador do IBS / CBS – `cMunFGIBS`, que tem como finalidade informar o município de ocorrência do fato gerador dos tributos, para ser preenchido quando o `indPres = 5 (Operação presencial, fora do estabelecimento)` e a nota fiscal não tiver informações do endereço do destinatário ou local de entrega.

Também consta o campo "Tipo de Nota de Débito" - `tpNFDebito`, com as seguintes opções possíveis:

- 01 = Transferência de créditos para Cooperativas;
- 02 = Anulação de Crédito por Saídas Imunes/Isentas;
- 03 = Débitos de notas fiscais não processadas na apuração;
- 04 = Multa e juros;
- 05 = Transferência de crédito de sucessão;
- 06 = Pagamento antecipado
- 07 = Perda em estoque

A opção `04=Multa e Juros` deverá ser usada nas emissões de notas fiscais para incidência dos tributos IBS e da CBS, quando ocorrer recebimento de juros e multas. O contribuinte que pagar a multa e os juros terá direito ao crédito dos tributos, por isso a necessidade de criação desse campo.

E a inclusão do campo "Tipo de Nota de Crédito" - `tpNFCredito`, com as seguintes opções possíveis:

- 01 = Multa e juros
- 02 = Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25)

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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cMunFGIBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código do Município de consumo, fato gerador do IBS / CBS
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
          <div class="absolute left-1/4 -translate-x-1/4 bottom-full mb-2 min-w-96 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de Nota de Débito: <br>
            01=Transferência de créditos para Cooperativas; <br>
            02=Anulação de Crédito por Saídas Imunes/Isentas; <br>
            03=Débitos de notas fiscais não processadas na apuração; <br>
            04=Multa e juros; <br>
            05=Transferência de crédito de sucessão; <br>
            06=Pagamento antecipado <br>
            07=Perda em estoque 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpNFCredito
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de Nota de Crédito:
            01 = Multa e juros <br>
            02 = Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25) 
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
            Percentual de redução de alíquota em compra governamental. Conforme art. 472/370 da LC 214/24.
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpOperGov
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Tipo de operação com o ente governamental:
            1=Fornecimento <br>
            2=Recebimento do pagamento, conforme fato gerador do IBS/CBS definido no Art. <code>10 §2º</code>da LC 214/25. 
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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Chave de acesso da NF-e de antecipação de pagamento
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

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

- Rejeição: NF-e referenciada de pagamento antecipado informada indevidamente (caso informado para modelo 65 - NFC-e);
- Rejeição: NF-e referenciada de pagamento antecipado inexistente;
- Rejeição: NF-e referenciada de pagamento antecipado deve ser do tipo débito.

## Bem móvel usado

O grupo `Grupo I. Produtos e Serviços da NF-e` passa a ter o campo `indBemMovelUsado` para identificar o fornecimento de bem móvel usado, adquirido de pessoa física que não seja contribuinte ou que seja inscrita como MEI.

## Alteração do ICMS normal e ICMS ST

As informações do ICMS da operação própria e ST passam a ter sua ocorrência opcional, pois será futuramente substituído pelo IBS.

⚠️ Precisamos lembrar de considerar a composição da base de cálculo do ICMS, pois isso não será citado em notas técnicas. Se não houver alteração, temos o IBS, CBS e IS compondo a base de cálculo do ICMS no período de transição. Leia o artigo [Reforma tributária: Impactos na Formação de Preços de Venda](https://papofiscal.blog/posts/reforma-tributaria-formacao-precos-de-venda) e saiba mais.

## Grupo de Informações dos Tributos IBS / CBS e IS

Novo grupo `UB. Informações dos tributos IBS / CBS e Imposto Seletivo`, contendo um série de campos relacionados aos novos tributos que deverão ser informados para cada item do documento, e o `Grupo VB. Total do item da NF-e` com o campo `vItem`.

- Esquema gráfico do leiaute, contemplando os grupos de campos do IBS, CBS e Imposto Seletivo.

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
  <div class="row-start-6 col-start-1 flex flex-col justify-center items-center">
    <div class="w-full max-w-44 min-w-28 p-1 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500 relative">prod
        <span class="absolute -right-1">+</span>
      </span>
    </div>
  </div>
  <div class="row-start-7 row-span-8 col-start-1">
    <div class="w-full flex flex-row gap-0.5 justify-center items-center">
      <span class="grow max-w-44 min-w-24 ml-0 sm:ml-6 text-center text-sm text-gray-500 p-1 border rounded-lg shadow-md relative">imposto</span>
      <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex justify-start items-center">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md relative">...
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupos dos tributos já existentes 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-8 col-start-2 w-full flex justify-start items-center pt-0.5">
    <div class="w-40 flex flex-col gap-4">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">IS
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Novo grupo referente informações do Imposto Seletivo 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-9 col-start-2 w-full flex justify-start items-start pt-0.5">
    <div class="w-full flex flex-row gap-0.5">
      <span class="grow max-w-40 min-w-20 pl-4 text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">IBSCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Novo grupo referente informações do Imposto de Bens e Serviços - IBS e da Contribuição de Bens e Serviços - CBS
          </div>
        </i>
      </span>
      <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    </div>
  </div>
  <div class="row-span-6 row-start-9 col-span-1 col-start-3 w-full gap-1 flex justify-start items-start">
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
      <span class="text-center sm:text-sm text-[0.5rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCredPresIBSZFM
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Informações do crédito presumido de IBS para fornecimentos a partir da ZFM
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

- Campos do Imposto Seletivo

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

- Grupo do IBS e CBS

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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Base de cálculo do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSUF
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para a UF
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSMun
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para o Município
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCBS
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gTribRegular
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da Tributação Regular.
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCredPres
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido do IBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCBSCredPres
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido referente a CBS
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gTribCompraGov
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da composição do valor do IBS e da CBS em compras governamentais 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

- Campos do IBS da UF

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
            Valor do tributo devolvido (desconto na própria Nota Fiscal / Fatura) 
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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva do IBS de competência das UF aplicada a Base de Cálculo, após redução de alíquota e gCompraGov/pRedutor: <br>
             <code>pAliqEfet = pIBSUF x (1 – pRedAliq) x (1 - gCompraGov/pRedutor) </code> 
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
            <code>Se grupo gRed preenchido:<br>
                vIBSUF = gRed/pAliqEfet x vBC <br>
              Senão: 
                vIBSUF = pIBSUF x vBC 
            </code> 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

- Campos do IBS dos Municípios

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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-48 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva do IBS de competência do Município aplicada a Base de Cálculo, após redução de alíquota e gCompraGov/pRedutor: <br><br>
             <code>pAliqEfet = pIBSMun x (1 – pRedAliq) x (1 - gCompraGov/pRedutor) </code> 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/3 bottom-full mb-2 min-w-64 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS de competência do Município.  <br><br>
            <code>Se grupo gRed preenchido:<br>
                vIBSMun = gRed/pAliqEfet x vBC <br>
              Senão: 
                vIBSMun = pIBSMun x vBC 
            </code> 
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

- Campos da CBS

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

- Grupo de informações da Tributação Regular, informando como seria a tributação caso não cumprida a condição resolutória/suspensiva

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

- Campos do Crédito Presumido de IBS

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 px-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] group">gIBSCredPres
        <i class="ph-light ph-info absolute left-1">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido referente ao IBS
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Código de Classificação do Crédito Presumido. Utilizar tabela cCredPres (Anexo IV) 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido em condição suspensiva
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

- Campos do Crédito Presumido da CBS

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] group">gCBSCredPres
        <i class="ph-light ph-info absolute left-1">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido referente ao CBS
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Código de Classificação do Crédito Presumido. Utilizar tabela cCredPres (Anexo IV) 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido em condição suspensiva
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

- Campos do IBS e da CBS em Compras Governamentais

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
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Alíquota do IBS de competência do Estado 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor que seria devido a UF, sem aplicação do <code>Art. 473. da LC 214/2025 </code>
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota do IBS de competência do Município 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor que seria devido ao município, sem aplicação do <code>Art. 473. da LC 214/2025 </code>
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota da CBS 
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor que seria devido de CBS, sem aplicação do <code>Art. 473. da LC 214/2025 </code>
          </div>
        </i>
      </span>
    </div>
  </div>
</div>

- Campos do IBS e CBS Monofásico

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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">-x-
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Monofasia dos Combustíveis 
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">-x-
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Uso em operações com combustíveis derivados de petróleo (Gasolina A ou Óleo Diesel A) para retenção do imposto sobre o biocombustível a ser misturado. Art 173 PLP 68/24. 
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">-x-
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-10 -translate-x-1/2 bottom-full mb-2 min-w-36 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Tributação monofásica própria sobre combustíveis cobrada anteriormente.
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">-x-
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

- Campos de Transferências de Crédito

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

- Campos de crédito presumido de IBS para fornecimentos a partir da Zona Franca de Manaus

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="w-40 sm:w-44 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] group">gCredPresIBSZFM
        <i class="ph-light ph-info absolute left-1">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do crédito presumido de IBS para fornecimentos a partir da ZFM
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
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpCredPresIBSZFM
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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-72 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do crédito presumido calculado sobre o saldo devedor apurado. <br>
            <ul class="flex flex-col text-start">
              <li><code>É obrigatório para nota de crédito com tpNFCredito = 02 - Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25)</code></li>
              <li><code>Vedado para documentos que não sejam nota de crédito com tpNFCredito = 02 - Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1º, LC 214/25)</code></li>
            </ul>
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

`vNFTot`: Valor total da NF-e com IBS / CBS / IS

## Regras de Validação

Diversas regras de validação serão aplicadas. Destacam-se e rejeição caso não informados dados do grupo dos tributos IBS e CBS e a regra de validação do valor total da NF-e/NFC-e, que vai considerar os valores de IS, IBS, CBS, IBS monofásico e CBS monofásica como parte integrante do total do documento.

Contudo, para no ano de 2026, que será tratado como um período de testes, está prevista a exceção em que os valores destacados dos novos tributos não sejam ainda somados no valor total da nota. Permitindo que as empresas e os sistemas de gestão, nesta exigência específica, tenham esse período para adaptação.

## DANFE

Alterações no DANFE para exibir informações relativas aos novos tributos estão em estudo. E serão publicadas em uma nova versão desta Nota Técnica.

## Pacote de Schemas

A NT cita que em busca de uma padronização entre os diversos documentos fiscais eletrônicos existentes, introduz o arquivo “DFeTiposBasicos_v1.00.xsd” ao conjunto dos arquivos que compõem o schema de todos os Documentos Fiscais Eletrônicos - DF-e, entre eles a NF-e e NFC-e.

Esse pacote de schemas é muito útil para as adaptações necessárias nos softwares, com finalidade de construção e leitura dos arquivos. Podemos encontrá-lo no Portal da Nota Fiscal Eletrônica, no menu "Documentos\Esquemas XML", com o nome:

- Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010a (Novo leiaute da NF-e, NT 2025.002 v.1.01) (ZIP). Publicado em 15/04/2025 `(versão em desuso)`
- Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010b (Novo leiaute da NF-e, NT 2025.002 v.1.10, NT 2024.003 e NT 2025.001) (ZIP). Publicado em 09/06/2025

## Novos Eventos

Criação de novos eventos destinados a ajustar a apuração assistida do IBS e da CBS. Permitindo que em certos casos específicos as empresas informem o direito ao crédito fiscal ou realizem o estorno de créditos indevidamente apropriados.

| Código | Evento                                                                                             |           Autor            |
| ------ | :------------------------------------------------------------------------------------------------- | :------------------------: |
| 112110 | Informação de efetivo pagamento integral para liberar crédito presumido do adquirente              |          Emitente          |
| 112120 | Importação em ALC/ZFM não convertida em isenção                                                    |          Emitente          |
| 112130 | Perecimento, perda, roubo ou furto durante o transporte contratado pelo fornecedor                 |          Emitente          |
| 112140 | Não ocorrência de fornecimento com pagamento antecipado                                            |          Emitente          |
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

O evento de “Imobilização de Item” por exemplo, deverá ser gerado pelo adquirente de bem, quando este for integrado ao seu ativo imobilizado, a fim de viabilizar o controle do prazo de 180 dias para apreciação dos pedidos de ressarcimento do respectivo crédito, nos termos do art. 39 e 40, I da LC 214/2025.

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
