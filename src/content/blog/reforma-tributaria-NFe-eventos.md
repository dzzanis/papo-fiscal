---
author: Papo Fiscal
pubDatetime: 2026-10-01T08:01:00Z
title: Como os novos eventos da NF-e impactam a apuração assistida da reforma tributária
slug: reforma-tributaria-nf-e-eventos
featured: false
draft: false
tags:
  - Reforma Tributária
  - Nota Técnica
  - DF-e
  - NF-e
  - Eventos NF-e
description: Visão prática dos novos eventos da NF-e na Reforma Tributária e como eles se relacionam com a Apuração Assistida do IBS e da CBS.
---

A Nota Técnica 2025.002 da NF-e criou uma série de eventos para a reforma tributária. Estes eventos da NF-e registram **fatos, condições ou manifestações relacionados à operação** após a emissão do documento.

Na Reforma Tributária do Consumo, eles ganham uma função adicional: **complementar as informações utilizadas pela Apuração Assistida da RTC**, influenciando a determinação de débitos, créditos e outros efeitos tributários.

> A NF-e registra a operação, os eventos registram o que acontece com ela, e a Apuração Assistida utiliza essas informações para determinar os efeitos do IBS e da CBS.

## Sumário

## 1️⃣ Os eventos criados pela Reforma Tributária

Podemos agrupar de eventos conforme a seguir para situações relacionadas à Reforma Tributária.

<div style="border-left:5px solid #1976d2; padding:12px 16px; margin:16px 0;">

### 🏭 Eventos do emitente

|   Código   | Evento                                                                                |
| :--------: | ------------------------------------------------------------------------------------- |
| **112110** | Informação de efetivo pagamento integral para liberar crédito presumido do adquirente |
| **112120** | Importação em ALC/ZFM não convertida em isenção                                       |
| **112130** | Perecimento, perda, roubo ou furto durante o transporte contratado pelo fornecedor    |
| **112140** | Fornecimento não realizado com pagamento antecipado                                   |
| **112150** | Atualização da data de previsão de entrega                                            |
| **211110** | Solicitação de apropriação de crédito presumido                                       |

</div>

<div style="border-left:5px solid #2e9d57; padding:12px 16px; margin:16px 0;">

### 👤 Eventos do destinatário

|   Código   | Evento                                                                                             |
| :--------: | -------------------------------------------------------------------------------------------------- |
| **211110** | Solicitação de apropriação de crédito Presumido                                                    |
| **211124** | Perecimento, perda, roubo ou furto durante o transporte contratado pelo adquirente                 |
| **211128** | Aceite de débito na apuração por emissão de nota de crédito                                        |
| **211130** | Imobilização de item                                                                               |
| **211140** | Solicitação de apropriação de crédito de combustível                                               |
| **211150** | Solicitação de apropriação de crédito para bens e serviços que dependem de atividade do adquirente |

</div>

<div style="border-left:5px solid #7048c6; padding:12px 16px; margin:16px 0;">

### 🔄 Eventos de sucessão

|   Código   | Evento                                                                                |
| :--------: | ------------------------------------------------------------------------------------- |
| **212110** | Manifestação sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão |
| **212120** | Manifestação sobre Pedido de Transferência de Crédito de CBS em Operações de Sucessão |

</div>

<div style="border-left:5px solid #ed6c02; padding:12px 16px; margin:16px 0;">

### 🏛️ Eventos do Fisco

|   Código   | Evento                                                                                         |
| :--------: | ---------------------------------------------------------------------------------------------- |
| **412120** | Manifestação do Fisco sobre Pedido de Transferência de Crédito de IBS em Operações de Sucessão |
| **412130** | Manifestação do Fisco sobre Pedido de Transferência de Crédito de CBS em Operações de Sucessão |

</div>

<div style="border-left:5px solid #d32f2f; padding:12px 16px; margin:16px 0;">

### ❌ Cancelamento de evento

|   Código   | Evento                 |
| :--------: | ---------------------- |
| **110001** | Cancelamento de Evento |

</div>

> **Atenção às versões:** o evento **211120 — Destinação de item para consumo pessoal** não é considerado neste artigo, pois foi removido na versão 1.40 da Nota Técnica 2025.002. Conforme revogação do §6º do art. 57 da LC 214/2025 pela LC 227/2026. Da mesma forma, eventos que existiam em versões anteriores da NT não devem ser tratados como eventos vigentes sem verificar a versão atual.

---

## 2️⃣ Onde os eventos entram na Apuração Assistida?

A grande questão não é apenas **qual evento existe**, mas **qual efeito a informação desse evento produz na Apuração Assistida**.

O modelo pode ser visualizado assim:

<style>
  .rtc-flow {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.75rem;
  }

  .rtc-flow-card {
    width: 100%;
    max-width: 280px;
  }

  .rtc-flow-arrow {
    transform: rotate(90deg);
  }

  @media (min-width: 640px) {
    .rtc-flow {
      flex-direction: row;
      align-items: stretch;
      justify-content: center;
      gap: 0.4rem;
    }

    .rtc-flow-card {
      max-width: none;
      min-width: 0;
      flex: 1 1 0%;
    }

    .rtc-flow-arrow {
      transform: rotate(0deg);
    }
  }
</style>

<div class="rtc-flow my-8">
  <!-- NF-e -->
  <div class="rtc-flow-card flex min-h-[175px] flex-col items-center justify-center rounded-xl border border-blue-400 bg-slate-900 px-3 py-5 text-center shadow-sm">

  <div class="mb-3 text-4xl">
      📄
    </div>

  <div class="text-base font-bold text-white">
      NF-e autorizada
    </div>

  <div class="mt-3 w-full border-t border-blue-400/70 pt-3 text-sm leading-relaxed text-slate-300">
      Operação original
    </div>

  </div>

  <!-- Seta -->
  <div class="rtc-flow-arrow flex shrink-0 items-center justify-center text-2xl font-light text-slate-300">
    ➕
  </div>

  <!-- Evento RTC -->
  <div class="rtc-flow-card flex min-h-[175px] flex-col items-center justify-center rounded-xl border border-amber-400 bg-slate-900 px-3 py-5 text-center shadow-sm">

  <div class="mb-3 text-4xl">
      🧩
    </div>

  <div class="text-base font-bold text-white">
      Evento RTC
    </div>

  <div class="mt-3 w-full border-t border-amber-400/70 pt-3 text-sm leading-relaxed text-slate-300">
      Fato, condição ou manifestação
    </div>

  </div>

  <!-- Seta -->
  <div class="rtc-flow-arrow flex shrink-0 items-center justify-center text-2xl font-light text-slate-300">
    →
  </div>

  <!-- Apuração Assistida -->
  <div class="rtc-flow-card flex min-h-[175px] flex-col items-center justify-center rounded-xl border border-purple-400 bg-slate-900 px-3 py-5 text-center shadow-sm">

  <div class="mb-3 text-4xl">
      📊
    </div>

  <div class="text-base font-bold text-white">
      Apuração Assistida
    </div>

  <div class="mt-3 w-full border-t border-purple-400/70 pt-3 text-sm leading-relaxed text-slate-300">
      Processamento e cruzamento
    </div>

  </div>

  <!-- Seta -->
  <div class="rtc-flow-arrow flex shrink-0 items-center justify-center text-2xl font-light text-slate-300">
    →
  </div>

  <!-- IBS / CBS -->
  <div class="rtc-flow-card flex min-h-[175px] flex-col items-center justify-center rounded-xl border border-green-400 bg-slate-900 px-3 py-5 text-center shadow-sm">

  <div class="mb-3 text-4xl">
      💰
    </div>

  <div class="text-base font-bold text-white">
      IBS / CBS
    </div>

  <div class="mt-3 w-full border-t border-green-400/70 pt-3 text-sm leading-relaxed text-slate-300">
      Débitos, créditos e ajustes
    </div>

  </div>
</div>

A Cartilha Orientativa — Volume 1 é especialmente importante aqui porque detalha **como determinadas informações dos documentos fiscais e eventos são utilizadas pelos Sistemas Operacionais do Comitê Gestor do IBS**.

---

## 3️⃣ O que um evento pode fazer na Apuração Assistida?

Nem todo evento tem a mesma finalidade.

De forma simplificada, podemos agrupá-los em quatro efeitos:

<div class="overflow-x-auto sm:text-sm text-xs">
  <table>
  <tr>
  <td align="center" width="25%">

➕<br>CRÉDITO

Informação que permite ou complementa a apropriação de crédito.

  </td>

  <td align="center" width="25%">

➖<br>DÉBITO

Informação que gera ou ajusta um débito.

  </td>

  <td align="center" width="25%">

🔄<br>AJUSTE

Modificação de uma informação anteriormente considerada.

  </td>

  <td align="center" width="25%">

🔐<br>CONDIÇÃO

Informação necessária para que determinado tratamento tributário seja reconhecido.

  </td>
  </tr>
  </table>
</div>

> **Importante:** evento não é sinônimo de crédito tributário. O evento fornece uma informação que será processada juntamente com os demais dados disponíveis para a Apuração Assistida.

---

## 4️⃣ Os eventos do emitente

### 💳 112110 — Efetivo pagamento integral

O evento registra o **efetivo pagamento integral da operação** para liberar crédito presumido do adquirente, nas hipóteses previstas.

<div align="center">

**NF-e**  
↓  
💰 **Pagamento integral**  
↓  
⚡ **112110**  
↓  
📊 **Apuração Assistida**  
↓  
➕ **Tratamento do crédito presumido**

</div>

### 🔎 Por que esse evento é interessante?

Porque o fato relevante para o tratamento tributário pode acontecer **depois da emissão da NF-e** e nascer no módulo financeiro do ERP.

**Financeiro → Evento fiscal → Apuração Assistida**

---

### 🌎 112120 — Importação em ALC/ZFM não convertida em isenção

O evento está relacionado à importação realizada em **Área de Livre Comércio ou Zona Franca de Manaus** quando a suspensão não se converte em isenção nas condições previstas.

<div align="center">

🌎 **Importação ALC/ZFM**  
↓  
⏸️ **Suspensão**  
↓  
❌ **Não conversão em isenção**  
↓  
⚡ **112120**  
↓  
➖ **Débito na Apuração Assistida**

</div>

A Cartilha detalha que esse evento permite registrar o valor correspondente ao IBS suspenso que não se converteu em isenção.

---

### 🚚 112130 — Perda, roubo ou furto no transporte contratado pelo fornecedor

O evento trata do **perecimento, perda, roubo ou furto da mercadoria durante transporte contratado pelo fornecedor**.

<div align="center">

🏭 **Fornecedor**  
↓  
📄 **NF-e**  
↓  
🚚 **Transporte contratado pelo fornecedor**  
↓  
⚠️ **Perecimento / perda / roubo / furto**  
↓  
⚡ **112130**  
↓  
📊 **Reflexo na Apuração Assistida**

</div>

Um ponto relevante destacado pela Cartilha é que, nessa situação, o evento pode produzir efeito sobre o débito anteriormente considerado para a operação.

---

### 💰 112140 — Fornecimento não realizado com pagamento antecipado

O evento trata da situação em que houve **pagamento antecipado**, mas o fornecimento não se concretizou.

<div align="center">

💰 **Pagamento antecipado**  
↓  
❌ **Fornecimento não realizado**  
↓  
⚡ **112140**  
↓  
🔄 **Ajuste na Apuração Assistida**

</div>

A utilização do evento está relacionada à situação em que se caracteriza que não haverá mais o fornecimento correspondente àquele pagamento antecipado.

---

### 📅 112150 — Atualização da Data de Previsão de Entrega

A previsão de entrega também pode ter impacto no tratamento da operação.

<div align="center">

📄 **NF-e**  
↓  
📅 **Previsão de entrega**  
↓  
🔄 **Data alterada / informada**  
↓  
⚡ **112150**  
↓  
📊 **Atualização na Apuração Assistida**

</div>

A alteração pode ser especialmente relevante quando modifica o período em que a operação deve ser considerada.

---

## 5️⃣ Os eventos do adquirente

Aqui está uma das principais novidades conceituais da RTC:

> 👤 **o adquirente também participa da formação das informações utilizadas na apuração por meio de eventos.**

---

### 🎯 211110 — Apropriação de Crédito Presumido

O adquirente pode solicitar a apropriação de crédito presumido mediante o evento específico.

<div align="center">

📄 **NF-e recebida**  
↓  
🔎 **Análise da operação**  
↓  
🎯 **Hipótese de crédito presumido**  
↓  
⚡ **211110**  
↓  
📊 **Apuração Assistida**

</div>

É importante separar:

**direito ao crédito ≠ solicitação ≠ processamento da apuração.**

---

### 📝 211128 — Aceite de débito por emissão de nota de crédito

Esse evento cria uma relação direta entre as apurações dos participantes da operação.

<div align="center">

👤 **Adquirente**  
↓  
🔎 **Possível crédito do adquirente**  
↓  
📝 **Nota de crédito**  
↓  
🏭 **Fornecedor**  
↓  
✅ **211128 — Aceite**  
↓  
📊 **Apuração Assistida**

</div>

A lógica é importante porque o tratamento de uma informação em uma empresa pode depender de uma manifestação realizada pela outra parte.

---

### 🏗️ 211130 — Imobilização de item

Quando o adquirente destina determinado bem ao **ativo imobilizado**, essa informação passa a ter representação por meio de evento.

<div align="center">

📄 **NF-e recebida**  
↓  
📦 **Bem adquirido**  
↓  
🏗️ **Destinação ao ativo imobilizado**  
↓  
⚡ **211130**  
↓  
📊 **Informação utilizada na Apuração Assistida**

</div>

Aqui fica evidente a necessidade de integração entre:

**Compras + Estoque + Ativo Imobilizado + Fiscal.**

---

### ⛽ 211140 — Crédito de combustível

O evento permite ao adquirente solicitar a apropriação de crédito nas hipóteses previstas para combustível.

<div align="center">

⛽ **Aquisição de combustível**  
↓  
🔎 **Análise da utilização**  
↓  
✅ **Condição para crédito**  
↓  
⚡ **211140**  
↓  
➕ **Tratamento do crédito**

</div>

A Cartilha apresenta situações em que o tratamento depende da finalidade dada ao combustível, distinguindo, por exemplo, aquisição para revenda daquela destinada ao consumo na atividade.

---

### ⚙️ 211150 — Crédito dependente de atividade do adquirente

Esse evento é particularmente interessante porque o direito ao crédito pode depender de uma condição relacionada à **atividade desenvolvida pelo próprio adquirente**.

<div align="center">

📄 **NF-e recebida**  
↓  
⚙️ **Bem ou serviço**  
↓  
🔎 **Condição relacionada à atividade**  
↓  
✅ **Hipótese de apropriação**  
↓  
⚡ **211150**  
↓  
📊 **Apuração Assistida**

</div>

Ou seja:

> **A informação necessária para a apuração pode estar no processo operacional do adquirente — e não somente na NF-e emitida pelo fornecedor.**

---

## 6️⃣ Sucessão: transferência de créditos

Os eventos **212110** e **212120** possuem uma dinâmica diferente porque envolvem a transferência de créditos em operações de sucessão.

<div align="center">

🏢 **Sucessão**  
↓  
💳 **Pedido de transferência de crédito**  
↓  
👤 **Manifestação da sucessora**  
↓  
⚡ **212110 — IBS**  
⚡ **212120 — CBS**  
↓  
🏛️ **Manifestação do Fisco**  
↓  
⚡ **412120 — IBS**  
⚡ **412130 — CBS**  
↓  
📊 **Reflexo na Apuração Assistida**

</div>

Nesse caso, temos um verdadeiro fluxo de comunicação:

**Sucessora → Evento → Fisco → Manifestação → Apuração**

---

## 7️⃣ 110001 — Cancelamento de Evento

Os eventos possuem seu próprio ciclo de vida.

Quando um evento precisa ser desfeito, utiliza-se o **110001 — Cancelamento de Evento**.

<div align="center">

⚡ **Evento RTC autorizado**  
↓  
⚠️ **Necessidade de desfazimento**  
↓  
❌ **110001**  
↓  
🔄 **Atualização da situação do evento**

</div>

> ⚠️ **Não confundir:** cancelar um evento **não significa cancelar a NF-e**. São objetos fiscais distintos.

---

## 8️⃣ O fluxo completo

Todos esses eventos podem ser resumidos em uma única cadeia:

<div class="overflow-x-auto sm:text-sm text-xs">
<table>
<tr>
<td align="center">

1️⃣<br>📅<br>**Fato**

Pagamento, entrega, imobilização, crédito etc.

</td>

<td align="center">→</td>

<td align="center">

2️⃣<br>🔎<br>**Regra**

A situação exige um evento?

</td>

<td align="center">→</td>

<td align="center">

3️⃣<br>⚡<br>**Evento**

Emitente, adquirente ou Fisco

</td>

<td align="center">→</td>

<td align="center">

4️⃣<br>☁️<br>**Autorização**

Evento registrado

</td>

<td align="center">→</td>

<td align="center">

5️⃣<br>📊<br>**Apuração**

Informação incorporada

</td>
</tr>
</table>
</div>

---

## 9️⃣ Por que esses eventos são tão importantes?

<div class="border rounded-lg p-2">

🛡️ Segurança

Informações estruturadas e rastreáveis reduzem o risco de tratamentos fiscais incorretos.

</div>

<div class="border rounded-lg p-2 mt-2">

🎯 Precisão

A Apuração Assistida passa a trabalhar com informações complementares sobre o ciclo da operação.

</div>

<div class="border rounded-lg p-2 mt-2">

🔗 Integração

Financeiro, logística, compras, ativo imobilizado e fiscal passam a participar de uma mesma cadeia de informação tributária.

</div>

<div class="border rounded-lg p-2 mt-2">

🔍 Rastreabilidade

Cada evento fica relacionado à operação e pode ser acompanhado em seu próprio ciclo de vida.

</div>

---

## 💡 Em resumo

**A NF-e deixa de ser apenas o registro da operação.**

Com a Reforma Tributária, eventos passam a registrar fatos e manifestações que podem ocorrer **depois da emissão do documento** e que são relevantes para a **Apuração Assistida do IBS e da CBS**.

> O desafio não é apenas implementar novos XMLs. É identificar os fatos do negócio que precisam ser transformados em eventos fiscais e garantir que essas informações cheguem corretamente à Apuração Assistida.

---

### 📚 Referências

- **NT 2025.002-RTC — NF-e/NFC-e – Reforma Tributária do Consumo**
- **Cartilha Orientativa – Volume 1 — Orientações sobre os efeitos dos documentos fiscais eletrônicos na Apuração Assistida gerada pelos Sistemas Operacionais do Comitê Gestor do IBS**

_Este artigo considera a relação de eventos da NT 2025.002 em sua versão 1.51 e utiliza a Cartilha Orientativa – Volume 1 como referência para explicar os efeitos dos documentos fiscais e eventos na Apuração Assistida. Como a Cartilha foi publicada com base em versão anterior da NT, alterações posteriores devem ser sempre confrontadas com a documentação técnica vigente._

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
