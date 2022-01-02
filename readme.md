# KURIA - API

API from my future project 'KURIA', a software to manager different properties (houses, offices, locals, parkings...).

This API is a fork of 'https://github.com/LuisPerisVidal/typescript-express-skeleton'. That it's my pesonal skeleton when I work with express/typescript.

## Prepare application

Create a .env file

```
# REQUIRED
PORT=3000
# OPTIONALS
DB_HOST=localhost
DB_USER=root
DB_PASS=123456
DB_DATABASE=kuria
SALT=kuriafilosofea
```

## Running the app

```
# install dependencies
npm install

# run in dev mode
npm run dev

# generate production build
npm run build

# run generated content in dist folder
npm run start
```

## Testing

### Jest with supertest

```
npm run test
```

## Rest Client (Visual Studio)

```
Open folder /testrestclient
```
