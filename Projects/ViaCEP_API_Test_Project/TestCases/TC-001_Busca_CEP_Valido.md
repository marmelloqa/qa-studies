# TC-001 - Busca de CEP Válido

## Objetivo

Validar que a API ViaCEP retorna corretamente os dados para um CEP existente.

## Pré-condição

API disponível.

## Endpoint

GET https://viacep.com.br/ws/01001000/json/

## Passos

1. Enviar requisição GET.
2. Informar CEP válido.
3. Executar.

## Resultado esperado

- Status 200.
- CEP retornado corretamente.
- Cidade São Paulo.
- UF SP.
