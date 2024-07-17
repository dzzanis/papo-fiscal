---
layout: ../layouts/AboutLayout.astro
title: "Sobre nós"
---

Papo fiscal é um blog com os melhores conteúdos e notícias do universo fiscal e tributário. Artigos produzidos pelos especialistas do Papo Fiscal. Leia agora!"

<div>
  <img src="/assets/blog.svg" class="sm:w-1/2 mx-auto" alt="blog writer illustration">
</div>

<h2 align="center">Apoio</h2>

<style>
  .section-apoio{
    width: 100%;
    margin-top: 2rem;
    margin-bottom: 2rem;
    justify-self: center;
    -webkit-font-smoothing: antialiased;
    display: flex; 
    flex-direction: row; 
    gap: 0.6rem;
    justify-content: center;
  }
  .card{
    box-shadow: 0.1rem 0.2rem 0.2rem 0.2rem lightgray;
    border-radius: 1rem;
    box-sizing: border-box;
    transition: transform 0.3s;

    display: flex; 
    flex-direction: column; 
    gap: 0.01rem;  
    justify-content: center;
    align-items: center;
    padding: 1rem;
  }

  .card a{
    //text-decoration: none;
  }
  </style>

<div class="section-apoio">
  
  <div class="card">
    <a href="https://rodrigozanis.adv.br" target="_blank" class="no-underline">
      <div>
        <img src="/assets/logo-rz-consultoria-e-assessoria-juridica.png" class="h-48 w-48 mx-auto" alt="logo advogado Rodrigo Zanis">
        <p class="text-xl font-medium text-black">Advogado Rodrigo Zanis</p>
        <strong class="text-slate-500">Consultoria e Assesoria Jurídica</strong>
      </div>
    </a>
  </div>

  <div class="card">
    <a href="https://dzzanis.github.io/contabilidade-osmarborges" target="_blank" class="no-underline">
      <div>
        <img src="/assets/logo-contabilidade-osmar-borges.jpg" class="h-48 w-48 mx-auto" alt="logo da Contabilidade Osmar Borges">
        <p class="text-xl font-medium text-black">Contabilidade Osmar Borges</p>
        <strong class="text-slate-500">Consultoria e Assesoria Jurídica</strong>
      </div>
    </a>
  </div>

</div>
