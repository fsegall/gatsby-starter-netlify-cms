---
templateKey: "about-page"
path: /about
title: As boas práticas do JAMstack
---

### O Projeto todo Servido em um CDN (Content Delivery Network)

Por conta dos projetos não dependerem de código server-side, ele pode ser distribuído em vez de viver em um único servidor. Servir de um CDN possibilita velocidade e performance imbatível.

### Ferramentas Modernas de Build

Usar as web-standards de amanhã hoje. Isso hoje significa Babel, PostCSS, Webpack e amigos.

### Builds Automatizados

Como o markup (HTML) é prerrenderizado o conteúdo precisa sofrer um build a cada atualização.
Você pode fazer isso com webhooks ou contar com os serviços prontos das plataformas de publicação.

### Deploys Atômicos

Uma estatégia de atualização tudo ou nada para os arquivos em cada deploy visando garantir e fazer controle de versão de um estado consistente da aplicação em todos os builds.

### Invalidação de Cache Instantânea

Os CDN's se encarregam de fazer o purge do cache para exibir as versões mais recentes do site.

### Tudo mora no Git

No projeto JAMstack, todos devem ser capazes de fazer um git clone, instalar as dependencias e rodar o projeto localmente com comandos simples(como npm install e npm start). O ambiente não deve necessitar de instalações complexas e levantar servidores de banco de dados. Isso reduz as barreiras para contribuição, além de simplificar os fluxos de trabalho nos ambientes de staging (homologação) e teste.
