EM PROGRESSO!!

SERVER

npm init -y
npm i express
modules "type":"module", e server para mjs
npm i typescript -D
trocar mjs para ts

-   "scripts": {
    "build": "tsc"
    },
    npx
-   arquivo de configuração executável do typescript
    npx tsc --init

tsconfig

"rootDir": "./src",
"outDir": "./build", (salvar o compilado na pasta build)
"moduleResolution": "node",

biblioteca para typescript
npm i @types/express -D

inicializador tipo nodemon para typescript
npm ts-node-dev -D
"dev": "ts-node-dev --exit-child src/server.ts"

npm i prisma -D
npx prisma init -h
npx prisma init --datasource-provider SQLite
npx prisma migrate
npx prisma migrate dev (name for the new migration "create table games", "create table ads")
npx prisma studio (interface gráfica para navegar pelo banco)
npm i @prisma/client

npm i cors
npm i @types/cors -D

npm install @radix-ui/react-dialog

REACT

npm create vite@latest
web-React-Typescript
npm install
npm i -D tailwindcss autoprefixer
npx tailwindcss init -p
-altera 'content' tailwind.config.cjs
-cria o styles/main com confg do tailwind

npm i phosphor-react

MOBILE

npm install --global expo-cli
expo init mobile
blank (TypeScript) same as blank but with TypeScript configuration
expo start
expo install expo-font @expo-google-fonts/inter
expo install react-native-safe-area-context
expo install expo-linear-gradient
