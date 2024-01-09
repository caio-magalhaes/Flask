 Cria um aplicativo Flask que renderiza um template chamado ‘book.html’. O template  recebe informações de um livro, como título, autor e ano de publicação, e exibe na página.

Model:
    Crie uma classe chamada Book que representa um livro, com os atributos title, author e year;
    Crie um objeto book com informações do livro Dom casmurro.

View:
    Crie um template chamado book.html que exibe as informações do livro;
    Usa a sintaxe do Jinja2 para exibir o título, autor e ano de publicação do livro.

Controller:
    Cria uma rota ‘/‘ que renderize o template book.html;
    Passa o objeto book como um argumento para a função render_template.
