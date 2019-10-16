# TDC POA 2019 Talk - Delivery

## Topicos

Esta será uma palestra que busca mostrar como é a jornada até a entrega de uma aplicação no seridor.

Do momento quando uma 

- Código fonte
  - Integração continua, não fique longe, você pode se perder.
  - GIT Flow, esse negocio é legal, e tem um monte de gente usando
  - Branches, isso tem um potencial enorme para o caos
  - PRs, um por dia pode ser?
  - Controles de qualidade
    - Ciclos instantaneos (Live)
      - Lint, pose ser seu melhor amigo, daquele sinceros que diz na tua cara que você ta errado.
    - Ciclos minimos (No teu commit)
      - Teu amigo te chamando para um papo serio
    - Ciclos médios (No teu push)
      - É tipo um papo introspectivo onde voce sosinho vai revisar seus problemas
    - Ciclos longos (No teu pipeline)
      - Quando o malvadão do time de QA quer zoar com você
- Build
  - Hora de sofrer com o paradoxo da escolha
  - Code split
    - Dividir para conquistar
  - Server nginx
    - CORS? não obrigado
  - Docker
- Artefato
  - Tem coisas que não mudam mesmo
- Ambientes
  - Server, não, Browser
- Testes
  - End 2 End (Evidencias)

![Evidencias](./evidencias.jpg)