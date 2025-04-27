---
author: Papo Fiscal
pubDatetime: 2025-03-01T07:58:00Z
modDatetime: 2025-03-26T06:57:00Z
title: Adequação da NF-e à reforma tributária
slug: reforma-tributaria-nf-e
featured: false
draft: false
tags:
  - Reforma Tributária
  - Nota Técnica
  - DF-e
  - NF-e
description: Conheça os novos campos da NF-e apresentado pela Nota Técnica 2024.002 para adequação do leiaute à reforma tributária.
---

Foram publicadas as notas técnicas apresentando as adequações dos leiautes dos DF-es (NF-e, NFC-e, CT-e, CT-e OS, BP-e, NF3-e, NFCom e NFS-e Nacional) à reforma tributária.

Vamos aqui conhecer os novos campos da NF-e, apresentado pela Nota Técnica 2024.002.

O Projeto de Lei Complementar (PLP) nº 68/2024, convertido na Lei Complementar nº 214/2025 estabelece regras para a implementação da Reforma Tributária do Consumo (RTC). Com a aprovação desse projeto, os Estados, o Distrito Federal e os Municípios devem promover ajustes nos Documentos Fiscais Eletrônicos e nos sistemas envolvidos, tendo em vista que as alterações entrarão em vigor em 1º de janeiro de 2026.

A fim de garantir a operacionalização tempestiva das novas regras, além de permitir que as administrações tributárias e os contribuintes se preparem para as mudanças, antecipou-se a publicação dessas notas técnicas.

## Sumário

## Cronograma

- Implantação Homologação: **01/09/2025**
- Implantação Produção: **31/10/2025**

Tendo por objetivo entrar em efetiva operacionalização a partir 01/01/2026.

Vale ressaltar que as discussões sobre a Reforma Tributária ainda estão em curso, o que pode resultar em ajustes tanto na legislação quanto nas notas técnicas publicadas.

## RT - Nota Técnica 2024.002 (NF-e e NFC-e)

[RT - Nota Técnica 2024.002](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=DaB0yzqdbRU=)<br>
<span class="text-sm">Versão 1.10 - Publicada em 6 de dezembro de 2024</span>

Esta nota técnica, definida conjuntamente entre os Estados, Municípios e Receita Federal do Brasil, modifica o leiaute da NF-e (modelo 55) e NFC-e (modelo 65). Inserindo os grupos e campos relacionados a tributação do Imposto sobre Bens e Serviços (IBS), Contribuição sobre Bens e Serviços (CBS) e Imposto Seletivo (IS), em atendimento as alterações previstas na EC 132/2023 para implementação da Reforma Tributária.

A versão 1.0 publicada em 01 de agosto de 2024 continha 41 páginas. Já a versão 1.10 de 06 de dezembro, passou a compor 67 páginas. Ela descreve além dos novos campos, uma série de regras de validação e novos eventos. Ainda indica que serão publicadas tabelas complementares e indicadores de obrigatoriedade de preenchimento dos novos grupos de informações.

## Nota de Débito e Crédito

Em destaque, cria duas finalidades de emissão da nota fiscal eletrônica:

- **Nota de débito**: documenta uma situação na qual o emitente registra um aumento no imposto devido (consequentemente, uma redução no imposto devido pelo adquirente, que é o destinatário);
- **Nota de crédito**: documenta uma situação na qual o emitente registra uma redução no imposto devido (consequentemente, um aumento no imposto devido pelo adquirente, que é o destinatário);

A NT cita que a regulamentação do IBS disporá sobre a utilização de notas de crédito e notas de débito para lançamentos de ajuste, com a finalidade de instrumentalizar a preparação da declaração assistida a ser oferecida para os contribuintes, de maneira automatizada, a partir de documentos fiscais eletrônicos, em cumprimento ao que preconiza o PLP 68/2024.

Também, explica que as finalidades de "Nota de Ajuste" e "Nota Complementar" que já existem são casos especiais de "Nota de Débito". Já uma "Nota de Entada" emitida para documentar, por exemplo, a devolução de mercadoria que havia sido vendida para consumidor final é um caso especial de "Nota de Crédito".

Cabe destacar que, a menos que ocorra uma alteração na regulamentação do ICMS e do IPI, estas notas de crédito e notas de débito não serão utilizadas para ajustes destes tributos.

## Código de Situação Tributária e Código de Classificação da Tributação

Os itens do documento fiscal devem ser classificados de acordo com o Código de Situação Tributária (CST) e o Código de Classificação Tributária (cClassTrib) do IBS, CBS e IS.

Essa tabela, publicada através do [Informe Técnico RT 2024.001](https://papofiscal.blog/posts/reforma-tributaria-tabela-classificacao-tributaria-do-ibs-e-da-cbs), está disponível nos portais nacionais dos DF-es. E a classificação dos itens do documento deve ser realizada conforme as previsões legais da Reforma Tributária, vinculando os CST e cClassTrib com as regras de validação.

## Grupo de Identificação da Nota Fiscal Eletrônica

No ´Grupo B. Identificação da Nota Fiscal Eletrônica´ houve a inclusão do campo de Código do Município de consumo, fato gerador do IBS / CBS – `cMunFGIBS`, que tem como finalidade informar o município de ocorrência do fato gerador dos tributos, para ser preenchido quando o `indPres = 5 (Operação presencial, fora do estabelecimento)` e a nota fiscal não tiver informações do endereço do destinatário ou local de entrega.

O outro novo campo é o Indicador de Multa e Juros – `indMultaJuros`, que vai ser usado nas emissões de notas fiscais para incidência dos tributos IBS e da CBS, quando ocorrer recebimento de juros e multas. O contribuinte que pagar a multa e os juros terá direito ao crédito dos tributos, por isso a necessidade de criação desse campo.

<div class="grid grid-cols-3 grid-rows-4 p-6 gap-4 ring-2 rounded ring-[#8b5cf6] overflow-hidden">
  <div class="row-span-3 row-start-1 w-full flex gap-5 flex-col justify-center items-center">
    <i class="ph-bold ph-arrow-elbow-up-right text-4xl text-green-700"></i>
    <div class="w-fit p-2 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500">Grupo B.</span>
      <span class="text-center text-sm text-gray-500">Identificação da NF-e</span>
    </div>
    <i class="ph-bold ph-arrow-elbow-down-right text-4xl text-green-700"></i>
  </div>
  <div class="row-span-1 row-start-1 w-full flex gap-2 justify-center items-center">
    <div class="w-48 flex flex-col gap-2">
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md">cMunFGIBS</span>
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md">indMultaJuros</span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-2 w-full flex justify-center items-center">
    <div class="w-48 flex flex-col gap-2">
      <span class="text-center text-sm text-slate-100 bg-indigo-400 p-1 border rounded-xl shadow-md">gCompraGov</span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-3 gap-1 flex justify-start items-center">
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    <div class="flex flex-col gap-2">
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md">tpCompraGov</span>
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md">pRedutor</span>
    </div>
  </div>
  <div class="row-span-1 row-start-4 col-start-2 flex sm:justify-center justify-start items-center">
    <span class="w-48 text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md">tipoNotaCredito</span>
  </div>
</div>

E foi criado o subgrupo de Compra Governamental – `gCompraGov`. Junto a esse subgrupo, temos os seguintes campos:

- `tpCompraGov`: Tipo de compra governamental. Que poderá ser:
  - 1 = União
  - 2 = Estados
  - 3 = Distrito Federal
  - 4 = Municípios
- `pRedutor`: Percentual de redução de alíquota em compra governamental.
- `tipoNotaCredito`: Indicador do tipo de nota de crédito que está sendo utilizada. Os tipos a ainda serão definidos.

## Alteração do ICMS normal e ICMS ST:

As informações do ICMS da operação própria e ST passam a ter sua ocorrência opcional, pois será futuramente substituído pelo IBS.

⚠️ Precisamos lembrar de considerar a composição da base de cálculo do ICMS, pois isso não será citado em notas técnicas. Se não houver alteração, temos o IBS, CBS e IS compondo a base de cálculo do ICMS no período de transição. Leia o artigo [Reforma tributária: Impactos na Formação de Preços de Venda](https://papofiscal.blog/posts/reforma-tributaria-formacao-precos-de-venda) e saiba mais.

## Grupo de Informações dos Tributos IBS / CBS e IS

Novo ´Grupo UB. Informações dos tributos IBS / CBS e Imposto Seletivo´ contendo um série de grupos e campos relacionados aos novos tributos que deverão ser informados para cada item do documento.

- Esquema gráfico do leiaute, contemplando os grupos de campos do IBS, CBS e Imposto Seletivo.

<div class="grid grid-cols-3 grid-rows-3 pl-2 pr-8 sm:px-12 pb-8 gap-1 ring-2 rounded ring-[#8b5cf6] overflow-hidden">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex gap-5 flex-col justify-center items-center">
    <div class="w-full p-2 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500">infNFe</span>
    </div>
    <i class="ph-bold ph-arrow-down text-4xl text-green-700"></i>
  </div>
  <div class="row-span-2 row-start-2 col-span-1 col-start-1 w-full flex gap-5 flex-col justify-start items-center">
    <div class="w-fit p-2 flex flex-col border rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500">Grupo H.</span>
      <span class="text-center text-xs text-gray-500">Detalhamento Produtos e Serviços</span>
    </div>
    <i class="ph-bold ph-arrow-elbow-down-right text-4xl text-green-700"></i>
  </div>
  <div class="row-span-1 row-start-2 col-start-2 w-full flex gap-2 justify-center items-end">
    <div class="w-48 flex flex-col gap-2">
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md relative">prod
        <span class="absolute right-1">+</span>
      </span>
      <span class="text-center text-sm text-gray-500 p-1 border rounded-xl shadow-md relative">imposto
      <span class="absolute right-1">+</span>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-2 w-full mt-1 flex justify-center items-start">
    <div class="w-48 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">IBSCBSSel</span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-span-1 col-start-3 w-full mt-1 gap-1 flex justify-start items-start">
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
    <div class="flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">seletivo
        <span class="absolute right-1">+</span>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">CST</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">cClassTrib</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md px-0.5 sm:px-4">indPerecimento</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBS
        <span class="absolute right-1">+</span>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCBSMono
        <span class="absolute right-1">+</span>
      </span>
    </div>
  </div>
</div>

- Campos do Imposto Seletivo

<div class="grid grid-cols-3 grid-rows-3 pl-2 pr-2 pb-4 sm:px-12 gap-1 ring-2 rounded ring-[#8b5cf6] overflow-hidden">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-center items-end">
    <div class="w-full flex justify-center p-2 ring-1 ring-[#8b5cf6] rounded-lg shadow-md">
      <span class="text-center text-sm text-[#8b5cf6]">seletivo</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-end">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">CST</span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">cClassTrib</span>
    </div>
  </div>
  <div class="row-span-1 row-start-2 col-start-2 w-full mt-1 gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">gImpSel</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-2 row-start-2 col-span-1 col-start-3 w-full gap-1 flex justify-start items-start">
    <div class="flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vBCImpSel</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pImpSel</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md px-0.5 sm:px-4">pImpSelEspec</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">uTrib</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">qTrib</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vImpSel</span>
    </div>
  </div>
</div>

- Grupo do IBS e CBS

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCredPres
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido do IBS
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
    </div>
  </div>
</div>

- Campos do IBS da UF

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_0.74fr)_minmax(0px,_1fr)] 
            grid-rows-[minmax(0px,_1fr)_minmax(0px,_0.6fr)_minmax(0px,_0.4fr)_minmax(0px,_0.6fr)_minmax(0px,_2fr)_minmax(0px,_0.4fr)]
            p-2 gap-4 ring-2 rounded ring-[#8b5cf6] overflow-hidden">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 sm:pl-14 justify-end items-end">
    <div class="w-full flex justify-center p-2 ring-1 ring-[#8b5cf6] rounded-lg shadow-md">
      <span class="text-center text-sm text-[#8b5cf6]">gIBSUF</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-end">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pIBSUF</span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vTribOP</span>
    </div>
  </div>
  <div class="row-span-1 row-start-2 col-start-2 w-full gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gDif</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-2 col-start-3 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pDif</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vDif</span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-2 w-full gap-1 pt-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gDevTrib</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-3 col-start-3 w-full pt-2 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vDevTrib</span>
    </div>
  </div>
  <div class="row-span-1 row-start-4 col-start-2 w-full gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gRed</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-4 col-start-3 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pAliqEfet</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pRedAliq</span>
    </div>
  </div>
  <div class="row-span-1 row-start-5 col-start-2 w-full gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gDeson</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-5 col-start-3 w-full pt-2 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">CST</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md px-0.5 sm:px-4">cClassTrib</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vBC</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pAliq</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vDeson</span>
    </div>
  </div>
  <div class="row-span-1 row-start-6 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vIBSUF</span>
    </div>
  </div>
</div>

- Campos do IBS dos Municípios

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_0.74fr)_minmax(0px,_1fr)] 
            grid-rows-[minmax(0px,_1fr)_minmax(0px,_0.6fr)_minmax(0px,_0.4fr)_minmax(0px,_0.6fr)_minmax(0px,_2fr)_minmax(0px,_0.4fr)]
            p-2 gap-4 ring-2 rounded ring-[#8b5cf6] overflow-hidden">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 sm:pl-14 justify-end items-end">
    <div class="w-full flex justify-center p-2 ring-1 ring-[#8b5cf6] rounded-lg shadow-md">
      <span class="text-center text-sm text-[#8b5cf6]">gIBSMun</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-1 col-start-2 w-full flex gap-2 justify-start items-end">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pIBSMun</span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vTribOP</span>
    </div>
  </div>
  <div class="row-span-1 row-start-2 col-start-2 w-full gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gDif</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-2 col-start-3 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pDif</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vDif</span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-2 w-full gap-1 pt-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gDevTrib</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-3 col-start-3 w-full pt-2 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vDevTrib</span>
    </div>
  </div>
  <div class="row-span-1 row-start-4 col-start-2 w-full gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gRed</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-4 col-start-3 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pAliqEfet</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pRedAliq</span>
    </div>
  </div>
  <div class="row-span-1 row-start-5 col-start-2 w-full gap-1 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0">gDeson</span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-5 col-start-3 w-full pt-2 flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">CST</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md px-0.5 sm:px-4">cClassTrib</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vBC</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">pAliq</span>
      <span class="text-center text-sm text-[#8b5cf6] ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vDeson</span>
    </div>
  </div>
  <div class="row-span-1 row-start-6 col-start-2 w-full flex gap-2 justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md">vIBSMun</span>
    </div>
  </div>
</div>

- Campos do Crédito Presumido de IBS

<div class="grid grid-cols-[minmax(0px,_0.9fr)_minmax(0px,_1fr)] grid-rows-1 pl-2 pr-2 p-4 sm:px-12 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-32 flex flex-col gap-2 justify-center py-2 ring-1 ring-[#8b5cf6] rounded-lg shadow-md">
      <span class="text-center text-sm text-[#8b5cf6] relative">gIBSCredPres
        <i class="ph-light ph-info absolute left-0 group">
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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Código de Classificação do Crédito Presumido
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

- Campos da CBS

<div class="grid grid-cols-[minmax(0px,_1fr)_minmax(0px,_1fr)]
            grid-rows-[minmax(0px,_0.5fr)_minmax(0px,_0.4fr)_minmax(0px,_0.8fr)_minmax(0px,_0.4fr)_minmax(0px,_0.3fr)_minmax(0px,_0.4fr)_minmax(0px,_1fr)_minmax(0px,_0.2fr)]
            p-2 gap-3 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-col gap-1 justify-center items-start sm:items-end">
    <div class="w-36 sm:w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-8 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da CBS
          </div>
        </i>
      </span>
    </div>
    <div class="w-36 sm:w-44 flex flex-col items-center">
      <i class="ph-bold ph-arrow-down text-4xl text-green-700"></i>
    </div>
  </div>
  <div class="row-span-1 row-start-2 col-span-1 col-start-1 w-full flex flex-col gap-1 justify-center items-start sm:items-end">
    <div class="w-36 sm:w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pCBS
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vTribOP
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor bruto do tributo na operação
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-3 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-56 sm:w-36 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCBSCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido referente a CBS 
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
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cCredPres
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código de Classificação do Crédito Presumido 
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
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Crédito Presumido 
          </div>
        </i>
      </span>
      <span class="text-center text-[0.8rem] sm:text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vCredPresCondSus
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do crédito presumido em condição suspensiva. 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-4 col-start-1 w-full gap-1 flex justify-end items-start">
  <div class="w-56 sm:w-36 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gDif
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
  <div class="row-span-1 row-start-4 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual do diferimento 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDif
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do Diferimento 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-5 col-start-1 w-full gap-1 pt-1 flex justify-end items-center">
    <div class="w-56 sm:w-36 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gDevTrib
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
  <div class="row-span-1 row-start-5 col-start-2 w-full pt-2 flex justify-start items-center">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDevTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor do tributo devolvido 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-6 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-56 sm:w-36 flex flex-col gap-2 grow-0">
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
  <div class="row-span-1 row-start-6 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pRedAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Percentual da redução de alíquota 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliqEfet
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Alíquota Efetiva da CBS que será aplicada a Base de Cálculo  
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-7 col-start-1 w-full gap-1 flex justify-end items-start">
    <div class="w-56 sm:w-36 flex flex-col gap-2 grow-0">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md grow-0 relative">gDeson
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da Desoneração 
          </div>
        </i>
      </span>
    </div>
    <svg 
      xmlns="http://www.w3.org/2000/svg" 
      width="32" height="32" fill="#000000" viewBox="0 0 256 256"> <path d="M43.18,128a29.78,29.78,0,0,1,8,10.26c4.8,9.9,4.8,22,4.8,33.74,0,24.31,1,36,24,36a8,8,0,0,1,0,16c-17.48,0-29.32-6.14-35.2-18.26-4.8-9.9-4.8-22-4.8-33.74,0-24.31-1-36-24-36a8,8,0,0,1,0-16c23,0,24-11.69,24-36,0-11.72,0-23.84,4.8-33.74C50.68,38.14,62.52,32,80,32a8,8,0,0,1,0,16C57,48,56,59.69,56,84c0,11.72,0,23.84-4"></path></svg>
  </div>
  <div class="row-span-1 row-start-7 col-start-2 w-full flex justify-start items-start">
    <div class="w-44 flex flex-col gap-2">
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">CST
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código de Situação Tributária do IBS e CBS 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md px-0.5 sm:px-4 relative">cClassTrib
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Código de Classificação Tributária do IBS e CBS 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vBC
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da BC 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">pAliq
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor da alíquota 
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-[#8b5cf6] p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">vDeson
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Valor desonerado 
          </div>
        </i>
      </span>
    </div>
  </div>
  <div class="row-span-1 row-start-8 col-start-1 w-full flex gap-2 justify-end items-start">
    <div class="w-36 sm:w-44 flex flex-col gap-2">
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

- Campos do IBS Monofásico

## Referenciamento de item de outra NF-e

O `Grupo VB. Referenciamento de item de outro Documento Fiscal Eletrônico - DF-e` para as informações:

- `DFeReferenciado` - Grupo para Documento Fiscal Eletrônico Referenciado
  - `chaveAcesso` - Chave de acesso do DF-e referenciado
  - `nItem` - Número do item do documento referenciado.

## Grupo de Total da NF-e

Novo `Grupo W03. Total da NF-e - IBS / CBS / IS` contendo campos totalizadores.

`IBSCBSSelTot`: Totais da NF-e com IBS, CBS e IS. Deve ser informado com o somatório do campo correspondente dos itens.

`gSel`: **Grupo total do imposto seletivo**

- `vBCSel`: Total da base de cálculo do imposto seletivo
- `vImpSel`: Total do imposto seletivo

`vBCIBSCBS`: Valor total da BC do IBS e da CBS

`gIBS`: **Grupo total do IBS**

- `vCresPres` - Valor total do crédito presumido
- `vCredPresCondSus` - Valor total do crédito presumido em condição suspensiva

  `gIBSUFTot`: Grupo total do IBS do Estado

  - `vDif`: Valor total do diferimento
  - `vDevTrib`: Valor total de devolução de tributos
  - `vDeson`: Valor total de desoneração
  - `vIBSUF`: Valor total do IBS da UF

  `gIBSMunTot`: Grupo total do IBS do Município

  - `vDif`: Valor total do diferimento
  - `vDevTrib`: Valor total de devolução de tributos
  - `vDeson`: Valor total de desoneração
  - `vIBSUF`: Valor total do IBS da UF

`gCBS`: **Grupo total da CBS**

- `vCresPres` - Valor total do crédito presumido
- `vCredPresCondSus` - Valor total do crédito presumido em condição suspensiva
- `vDif`: Valor total do diferimento
- `vDevTrib`: Valor total de devolução de tributos
- `vDeson`: Valor total de desoneração
- `vCBS`: Valor total da CBS

`gMono`:**Grupo total da Monofasia**

- `vTotIBSMono`: Total do IBS monofásico
- `vTotCBSMono`: Total da CBS monofásica
- `vTotNF`: Valor total da NF-e com IBS / CBS / IS

## Visão Completa dos Novos Campos do Leiaute

Veja no board abaixo, criado no aplicativo Miro, a representação gráfica completa dos novos grupos e campos que serão criados no XML da NFe e NFCe.

<iframe 
  class="w-full h-[432px] sm:h-dvh"
  src="https://miro.com/app/embed/uXjVIcgeOj4=/?pres=1&frameId=3458764618243140017&embedId=334260372356" 
  frameborder="0" 
  scrolling="no" 
  allow="fullscreen; clipboard-read; clipboard-write" 
  allowfullscreen
  >
</iframe>

## Novas Regras de validação

- B12a-20 - Rejeição: Município do fato gerador do IBS deve ser informado apenas em operação presencial fora do estabelecimento.
- B25-100 - Rejeição: NF-e de cŕedito referencia documento fiscal diferente de NF-e modelo 55.
- B25b-50 - Rejeição: NFC-e de entrega a domicílio e não informado endereço do destinatário.
- B25b-60 - Rejeição: Operação presencial fora do estabelecimento deve informar o município do fato gerador do IBS
- B34-10 - Rejeição: Tipo de nota de crédito deve ser informado apenas para nota com finalidade de nota de crédito.
- B30-20 - Rejeição: NF-e com indicador de multa e juros exige referenciamento do item da NF-e original.
- B32-10 - Rejeição: Nota de compra governamental e alíquota dos outros entes diferente de zero.
- 3BA02-70 - Rejeição: Nota de crédito de multa/juros deve ter NF-e de débito de multa/juros referenciada.

## Pacote de Schemas

A NT cita que em busca de uma padronização entre os diversos documentos fiscais eletrônicos existentes, introduz o arquivo “DFeTiposBasicos_v1.00.xsd” ao conjunto dos arquivos que compõem o schema de todos os Documentos Fiscais Eletrônicos - DF-e, entre eles a NF-e e NFC-e.

Contudo, até o momento não foi publicado oficialmente o novo pacote de schemas contemplando as alterações da Nota Técnica. Esse pacote de schemas é muito útil para as adaptações necessárias nos softwares, com finalidade de construção e leitura dos arquivos.

Mas, podemos encontrar uma versão beta no Portal dos Documentos Fiscais Eletrônicos SVRS, conforme o link:

[https://dfe-portal.svrs.rs.gov.br/Schemas/PRBPETA/DFeTiposBasicos_v1.00.xsd](https://dfe-portal.svrs.rs.gov.br/Schemas/PRBPETA/DFeTiposBasicos_v1.00.xsd).

## Novos Eventos

- Informação de efetivo pagamento integral para liberar crédito presumido do adquirente:

Permite que o emitente da NFe informe o efetivo pagamento integral a fim de liberar crédito presumido do adquirente.

- Solicitação de Apropriação de crédito presumido:

Evento a ser gerado pelo adquirente em relação às notas fiscais de aquisição de emissão de terceiros e que lhe gerem o direito à apropriação de crédito presumido.

- Destinação de item para consumo pessoal:

Permite ao adquirente informar quando uma aquisição for destinada para o consumo de pessoa física, hipótese em que não haverá direito à apropriação de crédito.

- Imobilização de Item:

Evento a ser gerado pelo adquirente de bem, quando este for integrado ao seu ativo imobilizado, a fim de viabilizar a adequada identificação, pelos sistemas da administração tributária, de prazo-limite para apreciação de eventuais pedidos de ressarcimento do respectivo crédito, nos termos do art. 59, I do PLP 68/2024.

- Solicitação de Apropriação de Crédito de Combustível:

Evento a ser gerado pelo adquirente de combustível listado no art. 167 do PLP 68/2024 e que pertença à cadeia produtiva desses combustíveis, para solicitar a apropriação de crédito referente à parcela que for consumida em sua atividade comercial.

- Solicitação de Apropriação de Crédito de fornecimento de bem móvel usado:

Evento a ser gerado pelo fisco sempre que for emitida nota fiscal de venda de bem móvel usado por contribuinte do regime regular de apuração, que referencie nota fiscal de aquisição em que tenha havido solicitação de apropriação de crédito presumido sob condição resolutória.

- Solicitação de Apropriação de Crédito para bens e serviços que dependem de atividade do adquirente:

Evento a ser gerado pelo adquirente para apropriação de crédito de bens e serviços que dependam da sua atividade.

- Manifestação sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão:

Evento a ser gerado pela sucessora em relação às notas fiscais de transferência de crédito de outra sucessora da mesma empresa sucedida para informar aceite da transferência de crédito de IBS.

- Manifestação sobre Pedido de Transferência de Crédito CBS em Operações de Sucessão:

Evento a ser gerado pela sucessora em relação às notas fiscais de transferência de crédito de outra sucessora da mesma empresa sucedida para informar aceite da transferência de crédito de CBS.

- Manifestação do Fisco sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão:

Evento a ser gerado pelo fisco em relação às notas fiscais de transferência de crédito para informar aceite ou não aceite da transferência de crédito de IBS.

- Manifestação do Fisco sobre Pedido de Transferência de Crédito de CBS em Operações de Sucessão:

Evento a ser gerado pelo fisco em relação às notas fiscais de transferência de crédito para informar aceite ou não aceite da transferência de crédito de CBS.

- Evento de cancelamento de evento do emitente:

Permite que o emitente da NF-e efetue o cancelamento de eventos que tenha efetuado, especificamente para cancelamentos referente o novo evento "Informação de efetivo pagamento integral para liberar crédito presumido do adquirente ".

- Evento de cancelamento de evento do destinatário:

Permite que o destinatário da NFe efetue o cancelamento destes novos eventos de NFe que tenha efetuado.

- Evento de cancelamento de evento da sucessora:

Permite que a sucessora efetue o cancelamento de seus eventos de NFe.

## DANFE

Alterações no DANFE para exibir informações relativas aos novos tributos estão em estudo. E serão publicadas em uma nova versão desta Nota Técnica.

---

Gostou deste conteúdo? Compartilhe com seus colegas e amigos que também podem se beneficiar destas informações.

Até a próxima! 👋

---

Precisando de apoio jurídico?

Entre já em contato com o nosso parceiro o advogado Rodrigo Zanis!

Serviços personalizados e de excelência na área da advocacia, de forma inovadora, eficaz e ágil.

<div class="text-center gap-0 shadow-[0.1rem_0.2rem_0.2rem_0.2rem_lightgray] rounded-2xl box-border transition ease-in-out delay-150 hover:scale-105 hover:-translate-y-1 p-3">
  <a href="https://rodrigozanis.adv.br" target="_blank" class="no-underline">
    <div>
      <img src="/assets/logo-rz-consultoria-e-assessoria-juridica.png" class="h-48 w-48 mx-auto" alt="logo advogado Rodrigo Zanis">
      <p class="text-xl font-medium text-black">Advogado Rodrigo Zanis</p>
      <strong class="text-slate-500">Consultoria e Assesoria Jurídica</strong>
    </div>
  </a>
</div>

---
