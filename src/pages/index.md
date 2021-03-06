---
templateKey: index-page
title: A mágica do JAMstack aqui na capital
image: /img/brasilia-master-plan_home-jumbotron.jpg
heading: Como tudo funciona?
subheading: O nome JAM é baseado em 3 pilares - JavaScript no cliente, APIs e Markup 'pré-buildado'.
mainpitch:
  title: Por que o JAMstack?
  description: >
    Para fazer web apps e sites globalmente distribuídos e resilientes a tráfico pesado.
    Fazendo deploy contínuo com o work-flow git que já está acostumado. Tudo isso tirando proveito de poder usar um design modular e consumir serviços via API.

description: >-
  O código fonte do site é hospedado em um repositório git que armazena o conteúdo e o código juntos em arquivos editáveis. Sempre que uma mudança é feita, um novo processo de build é inicializado que pré-renderiza o site ao criar páginas HTML baseadas em templates, conteúdo e dados. Por fim, todos os recursos são publicados globalmente em um CDN, perto dos usuários finais.
intro:
  blurbs:
    - image: /img/GitHub-logo.png
      text: >
        Você cria um repositório remoto no Github (Bitbucket, Gitlab ...) para o seu controle de versão normalmente.
    - image: /img/Gatsby-logo.png
      text: >
        Usa um gerador de sites estáticos para criar o seu projeto do zero ou com um starter. O Gatsby (que usamos neste site) e o Nextjs são duas opções muito utilizadas pela comunidade do Reactjs. Porém existem vários outros baseados em ecossistemas fora do JavaScript também.
    - image: /img/full-logo-light-Netlify.png
      text: >
        O Netlify, ou outras plataformas de hospedagem (como o Vercel, dentre dezenas de outras), se encarrega de fazer o build da aplicação, servir os seus assets em um CDN globalmente distribuído e fazer a integração contínua dos seu repositório no GitHub para deploys contínuos sempre que comitar o seu código na branch configurada.
---
