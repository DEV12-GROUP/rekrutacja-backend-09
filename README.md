

# Zadanie rekrutacyjne: URL Shortener

Twoim zadaniem jest dokończenie implementacji mikroserwisu do skracania linków.

## Wymagania uruchomienia
- Node.js 20
- pnpm/npm 
- Docker + docker-compose

## Kroki do uruchomienia
1. `docker compose up -d`
2. `pnpm i && pnpm db:migrate && pnpm dev`

## Testy
`pnpm test`

## Przykłady użycia po implementacji
- `POST /links` z body: `{ "url": "...", "slug?": "..." }`
- `GET /abc123` -> przekierowanie 302
- `GET /links?limit=10&offset=0`

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

