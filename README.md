## migrate the database
`cargo sqlx prepare -- --lib`

`DATABASE_URL=YOUR-DIGITAL-OCEAN-DB-CONNECTION-STRING sqlx migrate run`

## build docker image

`docker build --tag zero2prod --file Dockerfile .`