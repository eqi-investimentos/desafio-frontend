# Desafio Desenvolvedor Front-end

Bem vindo ao desafio para Desenvolvedor Front-end.

## Quem somos

Somos um dos maiores escritórios de Assessoria de Investimentos com presença em 11 cidades no Brasil e 11 anos de história no Mercado Financeiro.

Você fará parte da equipe de Engenharia de Software, tendo a oportunidade de construir soluções e ferramentas financeiras que simplifiquem a experiência dos nossos clientes no mercado de investimentos.

Somos uma empresa em crescimento, então aqui o aprendizado é constante.

## Apresentação do problema

Sua tarefa é construir um front-end para um Simulador de Investimentos. A aplicação deverá permitir ao usuário realizar uma simulação de rendimentos de acordo com o tipo de indexação e tipo de rendimento escolhido.
O front-end deve ser construído utilizando JavaScript puro ou React e seguindo os wireframes apresentados abaixo.

## O que será avaliado

Queremos avaliar sua capacidade de desenvolver e documentar um front-end para uma aplicação com back-end pronto. Serão avaliados:

- Código bem escrito e limpo;
- Quais ferramentas foram usadas e porque;
- Seu conhecimento em JS, HTML e CSS;
- Sua capacidade de seguir a especificação fornecida (wireframe);
- Sua capacidade de documentar o que você fez.

### O mínimo esperado

- Desenvolver o front-end de acordo com o wireframe fornecido, sendo que o gráfico não é obrigatório;
- Utilizar a API disponibilizada na documentação;
- README.md contendo informações básicas do projeto e como executá-lo.

### Diferenciais

- Testes no front-end (unitário com jest, e2e com cypress);
- Responsividade;
- Ferramentas adicionais que facilitem o seu trabalho (eslint, prettier, webpack/vite);
- Cuidados especiais com otimização, SEO, entre outros;
- Containerização com Docker;
- Outras sugestões que você tenha.

## Wireframes

### Tela inicial

![Home](https://user-images.githubusercontent.com/39882671/152025499-e79b10a4-7245-4303-af2c-ffd4bf2895f6.png)
Os campos IPCA e CDI devem vir preenchido no carregamento da página. Esses dados serão fornecidos pela API Fake.

### Tela inicial com os dados Preenchidos

![Dados Preenchidos](https://user-images.githubusercontent.com/39882671/152025603-25448432-572f-4aad-b4b1-0fa693b5788e.png)

### Dados inválidos

![Error](https://user-images.githubusercontent.com/39882671/152025628-032e0c0f-b468-44de-942e-3c6c196f38fa.png)
Validar o tipo dos campos e em caso de erro mostrar uma mensagem e colocar o label em vermelho.

### Exibição de dados do retorno da API

![Exibição de retorno dos dados da API](https://user-images.githubusercontent.com/39882671/152025761-f0353d38-9c80-4dee-8b37-e8ce84d1dd66.png)

Ao clicar no botão "Simular" você deverá chamar a API Fake por GET (sim, nós sabemos) e retornar os dados para a tela. Independente do valor que o usuário colocar, o retorno será o mesmo, a única coisa que você deverá se preocupar é com o tipo de indexação e tipo de investimento.

## API Documentação

https://github.com/eqi-investimentos/desafio-fake-api

## Entregando o desafio

- Criar um repositório para o desafio na sua conta do Github (não fazer fork);
- No README do projeto deve ter instruções de como executar e acessar o projeto;
- Envie o link do projeto para o e-mail desafio-tech@euqueroinvestir.com
