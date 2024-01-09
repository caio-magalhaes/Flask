 Cria um aplicativo web, usando Flask e Jinja2, que exibe uma lista de filmes. Acompanhe o passo a passo:

1 - Crie uma rota ‘/‘ que renderize um template chamado index.html. 2 - O template index.html deve exibir o título “Lista de Filmes” no topo da página. 3 - Defina uma lista de filmes no arquivo do aplicativo e passe essa lista para o template. 4 - No template, use uma estrutura de repetição do Jinja2 para exibir cada filme da lista em uma lista HTML. 5 - Cada filme deve ser exibido como um item de lista, contendo o título do filme e o ano de lançamento. 6 - Estilize a lista de filmes usando CSS para torná-la visualmente agradável.

Considere as seguintes dicas:

    Use a função render_template do Flask para renderizar o template index.html.
    Passe a lista de filmes para o template como um argumento na função render_template.
    No template, use a sintaxe do Jinja2 para iterar sobre a lista de filmes e exibi-los.
    Use arquivos CSS separados para estilizar a lista de filmes, se desejar.

