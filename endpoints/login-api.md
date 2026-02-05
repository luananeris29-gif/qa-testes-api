# Teste de API – Login

## Endpoint
POST /login

## Descrição
Valida autenticação de usuário.

## Body
{
  "email": "teste@email.com",
  "senha": "123456"
}

## Resultado Esperado
- Status Code: 200
- Retornar token de autenticação
