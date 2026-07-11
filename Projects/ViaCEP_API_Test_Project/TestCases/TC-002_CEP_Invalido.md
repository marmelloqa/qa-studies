# TC-002 - Busca de CEP Inválido

## Objetivo

Validar o comportamento da API para CEP inexistente.

## Endpoint

GET https://viacep.com.br/ws/00000000/json/

## Resultado esperado

- Status 200.
- Campo "erro": true.
