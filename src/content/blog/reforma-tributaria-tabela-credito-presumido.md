---
author: Papo Fiscal
pubDatetime: 2025-07-18T07:11:00Z
title: Tabela de Crédito Presumido do IBS e CBS
slug: reforma-tributaria-tabela-de-credito-presumido-do-ibs-e-cbs
featured: false
draft: false
tags:
  - Reforma Tributária
  - DF-e
  - NF-e
description: Conheça de tabela de Classificação de Crédito Presumido do IBS e da CBS apresentada pelo Informe Técnico RT 2025.002
---

Foi publicada a “Tabela de Classificação de Crédito Presumido do IBS e da CBS” no portal da nota fiscal eletrônica. Com o objetivo de padronizar, identificar e operacionalizar os créditos presumidos autorizados pela Lei Complementar nº 214/2025.

[Clique para baixar a Tabela de Código de Crédito Presumido](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=u2qX9qyLEGY=)<br>
<span class="text-xs">Publicada em 04/07/2025</span>

Sua previsão foi criada através do [Informe Técnico RT 2025.002](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=5gah0mS%20g5I=), que apresenta também outras tabelas, a “Tabela de Código de Classificação Tributária (cClassTrib)" e a “Tabela de Indicadores do CST”, ambos relacionados ao IBS e a CBS. E recentemente, em junho/2025, nas versões 1.10 e 1.11 sofre alterações incluindo também a tabela de `“Classificação do Crédito Presumido (cCredPres)”`.

A tabela define códigos aplicáveis às hipóteses legais de crédito presumido do IBS e da CBS, conforme previstas na Lei Complementar nº 214, de 2025. Cada código refere-se a uma situação específica autorizada pela legislação.

A tabela está disponível no Portal Nacional de DF-e em formato online e interativo:

**Tabela de Crédito Presumido (cCredPres):**

- [https://dfe-portal.svrs.rs.gov.br/DFE/TabelaCreditoPresumido](https://dfe-portal.svrs.rs.gov.br/DFE/TabelaCreditoPresumido)

No portal você encontra também as **Tabelas CST e Classificação Tributária (cClassTrib):**

- [https://dfe-portal.svrs.rs.gov.br/DFE/TabelaClassificacaoTributaria](https://dfe-portal.svrs.rs.gov.br/DFE/TabelaClassificacaoTributaria)

Cabe destacar que a tabela de Classificação do Crédito Presumido será fundamental para o preenchimento correto dos campos obrigatórios nos documentos fiscais eletrônicos e o cumprimento das regras de validação estabelecidas na documentação técnica de cada DFe. Sendo essencial para escrituração fiscal, parametrização dos ERP e o cumprimento das obrigações acessórias do novo sistema tributário.

Na tabela encontramos, junto aos códigos `cCredPress`, os indicadores que estabelecem se o crédito presumido será apropriado via nota fiscal ou evento de manifestação, se abrange o IBS e/ou a CBS, o tipo de alíquota que deve ser utilizada para cálculo (fixa, divulgada anualmente, efetiva, efetiva com redução) e qual cClassTrib (Código de Classificação Tributária) deve ser referenciado.

Por fim, veja abaixo os grupos e campos relacionados, previstos na [Nota Técnica 2025.002](https://papofiscal.blog/posts/reforma-tributaria-nf-e-nt-2025-002-v1.10/) da NF-e:

- Grupo do IBS e CBS do Item

<div class="grid grid-cols-[minmax(0px,_0.8fr)_minmax(0px,_1fr)] grid-rows-1 p-4 gap-2 ring-2 rounded ring-[#8b5cf6]">
  <div class="row-span-1 row-start-1 col-span-1 col-start-1 w-full flex flex-row gap-1 justify-end items-center">
    <div class="min-w-28 flex flex-col gap-2 justify-center p-2 ring-1 ring-gray-500/50 rounded-lg shadow-md">
      <span class="text-center text-sm text-gray-500 relative">gIBSCBS
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
      <span class="text-center text-sm text-gray-500 p-1 ring-1 ring-gray-500/50 rounded-xl shadow-md relative">vBC
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
              Base de cálculo do IBS e CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-gray-500 p-1 ring-1 ring-gray-500/50 rounded-xl shadow-md relative">gIBSUF
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 min-w-20 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para a UF
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-gray-500 p-1 ring-1 ring-gray-500/50 rounded-xl shadow-md relative">gIBSMun
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo do IBS para o Município
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-gray-500 p-1 ring-1 ring-gray-500/50 rounded-xl shadow-md relative">gCBS
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações da CBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-gray-500 p-1 ring-1 ring-gray-500/50 rounded-xl shadow-md relative">gTribRegular
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de informações da Tributação Regular.
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-red-500 p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gIBSCredPres
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido do IBS
          </div>
        </i>
      </span>
      <span class="text-center text-sm text-red-500 p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">gCBSCredPres
        <span class="absolute right-1">+</span>
        <i class="ph-light ph-info absolute left-1 group">
          <div class="absolute left-1/2 -translate-x-1/2 bottom-full mb-2 hidden group-hover:block bg-gray-800 text-white text-sm rounded px-2 py-1 shadow-lg">
            Grupo de Informações do Crédito Presumido referente a CBS
          </div>
        </i>
      </span>
      <span class="text-center sm:text-sm text-xs text-gray-500 p-1 ring-1 ring-gray-500/50 rounded-xl shadow-md relative">gTribCompraGov
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
      <span class="text-center text-sm text-red-500 p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cCredPres
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
      <span class="text-center text-sm text-red-500 p-1 ring-1 ring-[#8b5cf6] rounded-xl shadow-md relative">cCredPres
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
