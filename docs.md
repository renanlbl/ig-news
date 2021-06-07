criação de rotas automáticas, onde é preciso apenas adicionar na pasta /pages

salvar imagem, favicon... em public, onde em seus components você podera ter acesso direto a
pasta public, por exemplo /images/logo.svg, /favicon... etc

favicon deve ser adicionado no /document.tsx



Client-side -> Não precisa de indexação,
Server-side -> SEO, mais dinâmico da sessão do usuário em tempo real, que muda muito 
Static Side Generation -> SEO, mais rapido, se repete

Post blog =>
1º Coutendo = SSG
2º Comentário = SSR ou Client Side -> Client Side seria melhor pq nesse contexto não é algo que não talvez não precise está indexado,
e também não precisa ser mostrado logo quando carrega a tela, e também gera menos custo pro servidor.
