# Project Go (Api em Golang) :rocket:

Está é uma API em Golang, que foi desenvolvida para realizar operações CRUD (criação, leitura, atualização e exclusão) em um banco de dados MySQL

# Requisitos :books:

- Golang 1.18 ou superior
- MySQL

# Instalação :hammer:

1. Clone este repositório para seu computador
2. Execute o comando:
```
    go mod download
```
3. Configure as variaveis de ambiente no arquivo ***.env*** 


# Uso  :bulb:

1. Execute o comando:
```
    go run main.go
```

A API estára disponível em ***http://  localhost:5000***


# Rotas :dart:

| Método  | Rotas |    Descrição |
| ------- | ----- | -------------
| GET     | /usuarios | Lista todos os usuarios  |
| GET     | /usuarios/{usuarioId}  | Retorna um u usuário pelo ID |
| POST    | /usuarios  | Cria um novo usuário  |
| PUT     | /usuarios/{usuarioId}  | Atualiza um usuário pelo ID  |
| DELETE  | /usuarios/{usuarioId}  | Exclui um usuário pelo ID |


# Contribuição :anchor:

Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Fork este repositório
2. Crie uma branch com suas alterações ( ***git checkout -b my-new-feature***)
3. Faça suas alterações e salve (***git commit -m "Add some feature"***)
4. Envie suas alterações para sua branch (***git push origin my-new-feature***)
5. Crie um Pull Request
