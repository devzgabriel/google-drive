# Google Drive Clone - Semana JS Expert 5.0

## Preview

![](./resources/demo.gif)

## Checklist Features

- Web API

  - [] Deve listar arquivos baixados
  - [] Deve receber stream de arquivos e salvar em disco
  - [] Deve notificar sobre progresso de armazenamento de arquivos em disco
  - [] Deve permitir upload de arquivos em formato image, video ou audio
  - [] Deve atingir 100% de cobertura de código em testes

- Web App
  - [] Deve listar arquivos baixados
  - [] Deve permitir fazer upload de arquivos de qualquer tamanho
  - [] Deve ter função de upload via botão
  - [] Deve exibir progresso de upload
  - [] Deve ter função de upload via drag and drop

## Desafios pós projeto

1. _Backend_: Salvar o arquivo na AWS ou qualquer serviço de storage
   - Nosso projeto hoje armazena arquivos em disco. o desafio é você via Stream, fazer upload para algum serviço na nuvem
   - Como plus, manter 100% de code coverage, ou seja, crie testes para sua nova feature
2. _Frontend_: Adicionar testes no frontend e alcançar 100% de code coverage
   - Você aprendeu como fazer testes no backend. Usar o mesmo processo para criar testes unitários no frontend com Jest
   - Caso tenha duvidas, acesse o [exemplo](https://github.com/ErickWendel/tdd-frontend-example) e deixe uma estrela!
3. _Infraestrutura_: Publicar aplicação com seu SSL customizado em máquina virtual
   - Você aprendeu a gerar SSL local, o desafio é você criar um certificado (pode ser com o _Let's Encrypt_) e adicionar na sua aplicação

## Créditos ao Layout <3

- O Layout foi adaptado a partir do projeto do brasileiro [Leonardo Santo](https://github.com/leoespsanto) disponibilizado no [codepen](https://codepen.io/leoespsanto/pen/KZMMKG).

## FAQ

- Certificado SSL inválido?

  - Esse erro acontece porque gerei um certificado atrelado ao usuário da minha máquina.
  - Você pode clicar em prosseguir no browser e usar o certificado invalido que o projeto vai continuar funcionando, mas se quiser gerar o seu próprio, escrevi o passo a passo em [certificates](./aulas/01/grive-api/certificates/README.md)

- Rodei `npm test` mas nada acontece, o que fazer?
  - Verifique a versão do seu Node.js. Estamos usando na versão 16.8. Entre no [site do node.js](https://nodejs.org) e baixe a versão mais recente.
