# Ciro
atividades de POS

## Descrição de serviços

- ESCOLA: poderá realizar cadastros de alunos, professores e turmas. Por conseguinte, deve interagir com a Biblioteca para indicar quais usuários são alunos ou professores, de maneira que eles possam pegar uma quantidade maior de livros emprestados.

- BIBLIOTECA: deve realizar empréstimos de livros a usuários. Para isto, são necessários cadastros de livros e usuários. A Biblioteca é um serviço independente da Escola, de maneira que qualquer pessoa pode pedir livros emprestados. No entanto, professores e alunos podem pegar uma quantidade maior de livros emprestados. Assim, a Biblioteca deve pedir informações sobre os usuários à Escola para saber se são professores, alunos ou usuários comuns.

- AUTENTICAÇÃO: Este é o único serviço responsável por armazenar: login, senha, chaves de acesso... E fazer autenticação dos usuários (log in, log out). Será usado pela Escola e pela Biblioteca para autenticar seus usuários.

## Como foi desenvolvida a ferramenta?

Instalei um framework laravel utilizando o link https://laravel.com/".

## Como utilizar a ferramentar?

precisamos criar uma porta para acessar a ferramenta. Para criarmos a porta digitaremos no cmd: 
> php artisan serve --port 8081.
