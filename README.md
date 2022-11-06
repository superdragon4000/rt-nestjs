## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
## db

```bash
# to create migration
$ npx prisma migrate dev --create-only

# to run migration
$ npx prisma db push
```