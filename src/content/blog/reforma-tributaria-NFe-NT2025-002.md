---
author: Papo Fiscal
pubDatetime: 2025-05-03T07:58:00Z
title: Nota Técnica 2025.002 substitui a RT NT 2024.002 nas adequações da NF-e à reforma tributária
slug: reforma-tributaria-nf-e-nt-2025-002
featured: false
draft: false
tags:
  - Reforma Tributária
  - Nota Técnica
  - DF-e
  - NF-e
  - NFC-e
description: Conheça as novas definições apresentadas pela Nota Técnica 2025.002 para adequação do leiaute da NF-e à reforma tributária. Notas sem IBS e CBS serão rejeitadas a partir de janeiro de 2026.
---

Foram publicadas notas técnicas apresentando as adequações dos leiautes dos DF-es (NF-e, NFC-e, CT-e, CT-e OS, BP-e, NF3-e, NFCom e NFS-e Nacional) à reforma tributária.

Vamos aqui conhecer os novos campos da NF-e, apresentado pela Nota Técnica 2025.002.

O Projeto de Lei Complementar (PLP) nº 68/2024, convertido na Lei Complementar nº 214/2025 estabelece regras para a implementação da Reforma Tributária do Consumo (RTC). Com a aprovação desse projeto, os Estados, o Distrito Federal e os Municípios devem promover ajustes nos Documentos Fiscais Eletrônicos e nos sistemas envolvidos, tendo em vista que as alterações entrarão em vigor em [1º de janeiro de 2026](https://papofiscal.blog/posts/reforma-tributaria-cronograma/).

## Sumário

## Cronograma

a) Inserção de campos de controle e criação de eventos para utilização na apuração do IBS, CBS e IS:

- **01/07/2025**: Implantação Homologação
- **01/10/2025**: Implantação Produção

b) Aplicação das Regras de Validação:

- **01/07/2025**: Implantação Homologação
- **01/01/2026**: Implantação Produção

Em Produção, no ano de 2025 as informações de tributação relativas ao IBS, CBS e IS serão opcionais e não serão validadas. A partir de janeiro de 2026, as novas regras de validação referentes a tributação do IBS e da CBS serão aplicadas, entrando em efetiva operacionalização.

## RT - Nota Técnica 2024.002

[Clique para baixar a RT - Nota Técnica 2024.002](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=DaB0yzqdbRU=)<br>
<span class="text-sm">Versão 1.10 - Publicada em 6 de dezembro de 2024</span>

Esta nota técnica, definida conjuntamente entre os Estados, Municípios e Receita Federal do Brasil, modificava o leiaute da NF-e (modelo 55) e NFC-e (modelo 65). Inserindo os grupos e campos relacionados a tributação do Imposto sobre Bens e Serviços (IBS), Contribuição sobre Bens e Serviços (CBS) e Imposto Seletivo (IS), em atendimento as alterações previstas na EC 132/2023 para implementação da Reforma Tributária.

A versão 1.0 publicada em 01 de agosto de 2024 continha 41 páginas. Já a versão 1.10 de 06 de dezembro, passou a compor 67 páginas. Descrevendo além de novos campos, uma série de regras de validação e novos eventos.

## Nota Técnica 2025.002 (NF-e e NFC-e)

[Clique para baixar a Nota Técnica 2024.002](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=wuVuolIzJLs=)<br>
<span class="text-sm">Versão 1.01 - Publicada em 15 de abril de 2025</span>

Esta Nota Técnica substitui, no âmbito da NFe/NFCe, a RT NT 2024.002, atualizando as definições dos novos eventos, regras de validação e leiaute da NF-e e NFC-e referente à Reforma Tributária do Consumo.

A versão 1.00 publicada em 28 de março de 2025 continha 48 páginas. Já a versão 1.01 de 14 de abril, passou a compor 50 páginas.

## Nota de Débito e Crédito

Foram criadas duas novas finalidades de emissão da nota fiscal eletrônica:

- **Nota de débito**: documenta uma situação na qual o emitente registra um aumento no imposto devido (consequentemente, uma redução no imposto devido pelo adquirente, que é o destinatário);
- **Nota de crédito**: documenta uma situação na qual o emitente registra uma redução no imposto devido (consequentemente, um aumento no imposto devido pelo adquirente, que é o destinatário);

A NT cita que a regulamentação do IBS disporá sobre a utilização de notas de crédito e notas de débito para lançamentos de ajuste, com a finalidade de instrumentalizar a preparação da declaração assistida a ser oferecida para os contribuintes, de maneira automatizada, a partir de documentos fiscais eletrônicos, em cumprimento ao que preconiza a LC 214/2025.

Também, explica que as finalidades de "Nota de Ajuste" e "Nota Complementar" que já existem são casos especiais de "Nota de Débito". Já uma "Nota de Entada" emitida para documentar, por exemplo, a devolução de mercadoria que havia sido vendida para consumidor final é um caso especial de "Nota de Crédito".

Cabe destacar que, a menos que ocorra uma alteração na regulamentação do ICMS e do IPI, estas notas de crédito e notas de débito não serão utilizadas para ajustes destes tributos.

## Código de Situação Tributária e Código de Classificação da Tributação

Os itens do documento fiscal devem ser classificados de acordo com o Código de Situação Tributária (CST) e o Código de Classificação Tributária (cClassTrib) do IBS, CBS e IS.

Essa tabela, publicada através do [Informe Técnico RT 2024.001](https://papofiscal.blog/posts/reforma-tributaria-tabela-classificacao-tributaria-do-ibs-e-da-cbs), está disponível nos portais nacionais dos DF-es. E a classificação dos itens do documento deve ser realizada conforme as previsões legais da Reforma Tributária, vinculando os CST e cClassTrib com as regras de validação.

## Grupo de Identificação da Nota Fiscal Eletrônica

No ´Grupo B. Identificação da Nota Fiscal Eletrônica´ houve a inclusão do campo de Código do Município de consumo, fato gerador do IBS / CBS – `cMunFGIBS`, que tem como finalidade informar o município de ocorrência do fato gerador dos tributos, para ser preenchido quando o `indPres = 5 (Operação presencial, fora do estabelecimento)` e a nota fiscal não tiver informações do endereço do destinatário ou local de entrega.

Também consta o campo "Tipo de Nota de Débito" - `tpNFDebito`, com as seguintes opções possíveis:

- 01 = Transferência de créditos para Cooperativas;
- 02 = Anulação de Crédito por Saídas Imunes/Isentas;
- 03 = Débitos de notas fiscais não processadas na apuração;
- 04 = Multa e juros;
- 05 = Transferência de crédito de sucessão;

A opção `04=Multa e Juros` deverá ser usada nas emissões de notas fiscais para incidência dos tributos IBS e da CBS, quando ocorrer recebimento de juros e multas. O contribuinte que pagar a multa e os juros terá direito ao crédito dos tributos, por isso a necessidade de criação desse campo.

E a inclusão do campo "Tipo de Nota de Crédito" - `tpNFCredito`. Mas os tipos ainda serão definidos futuramente.

<div class="grid grid-cols-[minmax(0px,_0.94fr)_minmax(0px,_1fr)_minmax(0px,_1fr)] grid-rows-8 p-1 gap-2 ring-1 rounded ring-[#8b5cf6]">
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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-52 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de Nota de Débito:
            01=Transferência de créditos para Cooperativas; 
            02=Anulação de Crédito por Saídas Imunes/Isentas; 
            03=Débitos de notas fiscais não processadas na apuração; 
            04=Multa e juros; 
            05=Transferência de crédito de sucessão; 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpNFCredito
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-44 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Tipo de Nota de Crédito: a definir. 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-2 row-start-7 col-start-2 flex justify-start items-center">
    <div class="flex flex-row gap-0.5">
      <span class="sm:min-w-44 text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCompraGov
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
  <div class="row-span-2 row-start-7 col-start-3 gap-1 flex justify-start items-center">
    <div class="sm:min-w-36 flex flex-col gap-2">
      <span class="text-center sm:text-sm text-xs text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">tpCompraGov
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedutor
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual de redução de alíquota em compra governamental. Conforme art. 472/370 da LC 214/24.
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

## Alteração do ICMS normal e ICMS ST

As informações do ICMS da operação própria e ST passam a ter sua ocorrência opcional, pois será futuramente substituído pelo IBS.

⚠️ Precisamos lembrar de considerar a composição da base de cálculo do ICMS, pois isso não será citado em notas técnicas. Se não houver alteração, temos o IBS, CBS e IS compondo a base de cálculo do ICMS no período de transição. Leia o artigo [Reforma tributária: Impactos na Formação de Preços de Venda](https://papofiscal.blog/posts/reforma-tributaria-formacao-precos-de-venda) e saiba mais.

## Grupo de Informações dos Tributos IBS / CBS e IS

Novo grupo ´Grupo VB. Total do item da NF-e´ com o campo´vItem´ e o ´Grupo UB. Informações dos tributos IBS / CBS e Imposto Seletivo´ contendo um série de grupos e campos relacionados aos novos tributos que deverão ser informados para cada item do documento.

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
  <div class="row-start-7 col-start-1">
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
  <div class="row-start-8 col-start-2 w-full flex justify-start items-center">
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
  <div class="row-start-9 col-start-2 w-full flex justify-start items-start">
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
  <div class="row-span-4 row-start-9 col-span-1 col-start-3 w-full gap-1 flex justify-start items-start">
    <div class="w-full max-w-40 min-w-20 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">CST
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Código de Situação Tributária do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cClassTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Código de Classificação Tributária do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBS
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo de Informações do IBS e da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-[0.8rem] text-[#8b5cf6] p-1 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBSMono
        <span class="absolute right-0.5">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-32 hidden group-hover:block bg-gray-800 text-white text-sm text-start rounded px-2 py-1 shadow-lg">
            Grupo de Informações do IBS e CBS em operações com imposto monofásico
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-13 col-start-1 flex flex-col justify-center items-center">
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
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
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
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva do IBS de competência das UF aplicada a Base de Cálculo 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSUF
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS de competência da UF 
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
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
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
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva do IBS de competência do Município aplicada a Base de Cálculo 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-start-7 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMun
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS de competência do Município 
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
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
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
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-2 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-0.5 pl-3 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
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

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_1fr)] grid-rows-1 p-4 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-28 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center text-xs text-[#8b5cf6] group">gTribRegular
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfetRegIBSUF
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-4 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfetRegIBSMun
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfetRegCBS
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

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center p-2 pl-4 ring-1 ring-[#8b5cf6] rounded-lg shadow-md relative">
      <span class="text-center text-sm text-[#8b5cf6] group">gIBSCredPres
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
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
      <span class="text-center text-sm text-[#8b5cf6] group">gCBSCredPres
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido em condição suspensiva
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
  <div class="row-span-1 row-start-2 col-span-1 col-start-1 w-full flex flex-col gap-1 justify-end items-start sm:items-end">
    <div class="w-40 sm:w-44 flex flex-col gap-2">
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemIBSREten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem do IBS sujeito a retenção 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vIBSMonoReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-40 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do IBS monofásico sujeito a retenção, a ser somado ao valor de IBS a ser recolhido. 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">adRemCBSReten
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota ad rem da CBS sujeito a retenção 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCBSMonoReten
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTotIBSMonoItem
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Total de IBS Monofásico.
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 pl-5 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTotCBSMonoItem
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Total da CBS Monofásica.
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

  - `vCresPres` Valor total do crédito presumido
  - `vCredPresCondSus` Valor total do crédito presumido em condição suspensiva
  - `vDif` Valor total do diferimento
  - `vDevTrib` Valor total de devolução de tributos
  - `vCBS` Valor total da CBS

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

- Esquema XML NF-e/NFC-e - Pacote de Liberação nº 010a (Novo leiaute da NF-e, NT 2025.002 v.1.01) (ZIP). Publicado em 15/04/2025

## Novos Eventos

Criação de novos eventos destinados a ajustar a apuração assistida do IBS e da CBS. Permitindo que em certos casos específicos as empresas informem o direito ao crédito fiscal ou realizem o estorno de créditos indevidamente apropriados.

| Código | Evento                                                                                             |           Autor            |
| ------ | :------------------------------------------------------------------------------------------------- | :------------------------: |
| 112110 | Informação de efetivo pagamento integral para liberar crédito presumido do adquirente              |          Emitente          |
| 211110 | Solicitação de Apropriação de crédito presumido                                                    |        Destinatário        |
| 211120 | Destinação de item para consumo pessoal                                                            |   Emitente Destinatário    |
| 211124 | Perecimento, perda, roubo ou furto                                                                 |        Destinatário        |
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
