# Dentro ou Fora

Bem-vindo ao "Dentro ou Fora"! Este é um projeto de jogo onde os usuários podem criar e participar de jogos com pessoas, onde cada pessoa deve escolher se ela fica dentro ou fora. Este README fornecerá uma visão geral do projeto e como você pode começar a utilizá-lo.

## Funcionalidades

- Criar um jogo: Os usuários podem criar um novo jogo, definindo os participantes e as opções "dentro" e "fora".
- Encerrar jogo: Os criadores dos jogos podem encerrar um jogo criado por eles a qualquer momento.
- Votar em novos jogos: Os usuários podem participar de jogos criados por outros usuários, votando se as pessoas listadas devem ficar dentro ou fora.
- Compartilhar votações: Os resultados das votações podem ser compartilhados nas redes sociais ou com outros usuários.
- Cadastro de usuários: Os usuários podem se cadastrar para criar jogos e participar das votações.

## Tecnologias Utilizadas
Este projeto foi desenvolvido utilizando o framework Laravel para o backend e o framework Bootstrap para a construção do frontend.

## Como Iniciar

Clone o Repositório: Clone este repositório para o seu ambiente local utilizando o seguinte comando:

```bash
git clone https://github.com/seu-usuario/dentro-ou-fora.git
```

Instale as Dependências: Navegue até o diretório clonado e instale as dependências do projeto utilizando o Composer:
```bash
cd dentro-ou-fora
composer install
```
Configure o Banco de Dados: Renomeie o arquivo .env.example para .env e configure suas credenciais de banco de dados.

Execute as Migrações: Execute as migrações do banco de dados para criar as tabelas necessárias:
```bash
php artisan migrate
```

Inicie o Servidor de Desenvolvimento: Inicie o servidor de desenvolvimento do Laravel:
```bash
php artisan serve
```

Acesse o Aplicativo: Abra o navegador e acesse http://localhost:8000 para começar a usar o aplicativo "Dentro ou Fora".

## Contribuindo

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
