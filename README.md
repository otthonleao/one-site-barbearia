# Site Barbearia
Projeto prático com layouts de uma página estática para desenvolver utilizando HTML e CSS. Esse site conta com três páginas básicas: Home, Serviços e Contatos. Além da construção básica, conta exemplos para inserção de mapas e vídeos do YouTube.

Nesse curso da **Oracle Next Education** em parceria com a Alura engloba temas como:
- HTML5
- CSS3
- Media Query para reponsividade de tela
- Git e GitHub

Certificado: [Formação Iniciante em Programação T5 - ONE](https://cursos.alura.com.br/degree/certificate/82c4cee2-89f8-4345-9fe2-c2c555562f6b)

## Oracle Next Education - ONE
O [ONE](https://www.oracle.com/br/education/oracle-next-education/) é um programa de educação e empregabilidade com objetivo social de capacitar pessoas em tecnologia e conectá-las com o mercado de trabalho por meio de empresas parceiras.

O curso é 100% online e totalmente gratuito, feito para quem não teve acesso à educação de qualidade e deseja transformar a sua realidade social.

O programa abre as inscrições 3 vezes ao ano. Cada turma cumpre uma jornada de 6 meses, divididos em 4 trilhas disponibilizadas na plataforma – ao todo são mais de 560 horas de conteúdo.

## Links Úteis
- [Unicode Table](https://old.unicode-table.com/pt/) : Código unicode para utilizar no HTML (utilizado a forma 'entidade').
- [Mayer Web](https://meyerweb.com/eric/tools/css/reset/) : Reset CSS para "zerar" as configurações de estilos padrão dos navegadores.

## Destaques HTML
- `<fieldset>` é utilizada para marcar um grupo de campos em qualquer formulário sendo muito comum em formulários de cartão de crédito por exemplo. `<legend>` marca o título do grupo do `<fieldset>` ao invés de utilizar a tag `<p>`.

* A criar uma tabela HTML
`<table>`, que representa a tabela
`<tr>`, que representa a linha da tabela
`<td>`, representa a célula da tabela
`<tr><td colspan="5"></td></tr>`, mescla 5 células da linha
`<thead>`, representa o cabeçalho da tabela
`<tbody>`, representa o corpo da tabela
`<th>`, representa a célula do cabeçalho da tabela
`<tfoot>`, que representa o rodapé da tabela

- `<section>`é utilizado para um bloco onde o conteúdo tenha o mesmo significado, o mesmo sentido, ou seja, um bloco semântico.

## Destaques CSS
- `width: calc(33%-10px)` : exemplo de como usar medidas proporcionais para deixar um elemento de 100% de largura com o equivalente a 1/3 do elemento pai, menos 10px.

- `main > p {}`: seletor `>`, para acessar os filhos de determinado elemento.
- `img + p {}`: seletor `+`, para acessar o primeiro irmão de determinado elemento.
- `img ~ p {}`: seletor `~`, para acessar todos os irmãos de determinado elemento.
- `main p:not(#missao) {}`: seletor `not`, para acessar os elementos, exceto algum. Por exemplo, para acessar todos os `p` dentro de `main`, exceto o `p` que tem `id missao`.