---
author: Papo Fiscal
pubDatetime: 2025-03-01T07:58:00Z
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

Essas tabelas estarão disponíveis nos portais nacionais para classificação dos itens, devendo ser preenchida conforme as previsões legais da Reforma Tributária, vinculando os CST e cClassTrib com as regras de validação.

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

- `tpCompraGov` - Tipo de compra governamental. Que poderá ser:
  - 1 = União
  - 2 = Estados
  - 3 = Distrito Federal
  - 4 = Municípios
- `pRedutor` - Percentual de redução de alíquota em compra governamental.
- `tipoNotaCredito` - Indicador do tipo de nota de crédito que está sendo utilizada. Os tipos a ainda serão definidos.

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

## Pacote de Schemas

A NT cita que em busca de uma padronização entre os diversos documentos fiscais eletrônicos existentes, introduz o arquivo “DFeTiposBasicos_v1.00.xsd” ao conjunto dos arquivos que compõem o schema de todos os Documentos Fiscais Eletrônicos - DF-e, entre eles a NF-e e NFC-e.

Contudo, até o momento não foi publicado oficialmente o novo pacote de schemas contemplando as alterações da Nota Técnica. Esse pacote de schemas é muito útil para as adaptações necessárias nos softwares, com finalidade de construção e leitura dos arquivos.

Mas, podemos encontrar uma versão beta no Portal dos Documentos Fiscais Eletrônicos SVRS, conforme o link:

[https://dfe-portal.svrs.rs.gov.br/Schemas/PRBPETA/DFeTiposBasicos_v1.00.xsd](https://dfe-portal.svrs.rs.gov.br/Schemas/PRBPETA/DFeTiposBasicos_v1.00.xsd).

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
