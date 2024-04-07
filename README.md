# Blog da Kenzie: Guia de Implementação

Este projeto envolve a criação de uma estrutura de blog utilizando HTML, seguindo o design e a estrutura do blog da Kenzie Academy Brasil. O objetivo é compilar artigos com links para endereços externos, permitindo que os usuários acessem conteúdos completos ao clicar nos posts. Além disso, o site inclui uma seção de Newsletter para coleta de emails dos usuários interessados em receber notícias.

## Estrutura do Projeto

O projeto é estruturado em torno de tags semânticas do HTML para organizar o conteúdo e facilitar a navegação. A estrutura principal inclui:

- **Cabeçalho (`<header>`):** Contém o título principal do blog.
- **Navegação (`<nav>`):** Fornece links para seções específicas do blog.
- **Conteúdo Principal (`<main>`):** Apresenta os artigos (`<article>`) com resumos e links para os artigos completos externos.
- **Formulário de Newsletter (`<form>`):** Solicita o email do usuário para subscrição de novidades.

### Posts

Cada post é encapsulado dentro de uma tag `<article>`, com um identificador único para facilitar a navegação. Os artigos contêm:

- Títulos (`<h2>` e `<h3>`): Para os títulos dos artigos e subtítulos.
- Parágrafos (`<p>`): Descrevem o conteúdo do artigo e incluem um link (`<a>`) para o artigo completo externo.
- Citação (`<cite>`): Indica o autor do artigo.

### Newsletter

A seção de Newsletter segue os artigos, convidando os usuários a se inscreverem para receber notícias. Inclui:

- Um formulário (`<form>`) com:
  - Etiqueta (`<label>`) para o campo de email.
  - Campo de entrada (`<input type="email">`) para o usuário inserir seu email, com atributos adequados para validação.
  - Botão de envio (`<button type="submit">`).

## Metatags

O `<head>` do documento HTML inclui metatags para:

- Especificação de charset (`<meta charset="UTF-8">`).
- Compatibilidade com o IE (`<meta http-equiv="X-UA-Compatible" content="IE=edge">`).
- Viewport para responsividade (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`).

## Tags Semânticas

A utilização de tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<form>`) organiza o conteúdo de forma lógica e acessível, melhorando a SEO e a experiência do usuário.
