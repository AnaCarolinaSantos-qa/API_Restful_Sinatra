# API RESTful com Sinatra

Projeto de curso para uma API de livros com Sinatra e MongoDB.

## Requisitos

- Ruby e Bundler
- MongoDB local em `127.0.0.1:27017`

O arquivo `mongoid.yml` é local e ignorado pelo Git. Copie o exemplo antes de iniciar a aplicação:

```bash
cp mongoid_example.yml mongoid.yml
bundle install
bundle exec ruby app.rb -p 4567
```

Em outro terminal, rode a suíte:

```bash
bundle exec rspec
```

Os testes criam e removem registros no banco configurado; use somente um banco descartável de desenvolvimento/teste.
