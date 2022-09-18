<div>

# Bootcamp Ignite NLW RocketSeat

## Full-stack application.
<br>
Front-end web and Mobile with back-end database.

<br>

# Preview
<div align="center">
<a href="https://youtu.be/LWsyGEgw4Lw">DEMO</a>
</div>
<br/>

![Captura de Tela 2022-09-18 às 15 36 37](https://user-images.githubusercontent.com/101880897/190923088-4f623981-6a69-44a8-b6d9-ddf2dc4b412c.png)

![Captura de Tela 2022-09-18 às 15 53 16](https://user-images.githubusercontent.com/101880897/190924089-b1e423f5-6ce6-419c-ad0c-e4469fbf39df.png)

![Captura de Tela 2022-09-18 às 16 01 02](https://user-images.githubusercontent.com/101880897/190924092-98367b8c-dd87-4019-ae52-f99d259814c2.png)


<br>
<br>

# Techs

## Front-end
- REACT
- Tailwindcss
- Typescript

Libs

- npm install
- npm create vite@latest
- web-React-Typescript
- npm i -D tailwindcss autoprefixer
- npx tailwindcss init -p
    - altera 'content' tailwind.config.cjs
    - cria o styles/main com confg do tailwind
npm i phosphor-react
npm install @radix-ui/react-checkbox
npm install @radix-ui/react-toggle-group
npm i axios

## Front-end Mobile

Libs

- npm install --global expo-cli
- expo init mobile
- blank (TypeScript) same as blank but with TypeScript configuration
- expo start
- expo install expo-font @expo-google-fonts/inter
- expo install react-native-safe-area-context
- expo install expo-linear-gradient

- ifconfig (endereço Ip)

- npm install @react-navigation/native
- expo install react-native-screens
- npm install @react-navigation/native-stack
- npm install --save phosphor-react-native
- expo install react-native-svg
- expo install expo-clipboard
- expo install expo-notifications
- expo install expo-modules-core

## Server

Libs

- npm init -y
- npm i express
- modules "type":"module", e server para mjs
- npm i typescript -D
    - trocar mjs para ts
    - "scripts": {
    "build": "tsc"
    },
    npx
        - Arquivo de configuração executável do typescript
    npx tsc --init

- tsconfig
    - "rootDir": "./src",
    - "outDir": "./build", (salvar o compilado na pasta build)
    - "moduleResolution": "node",

- biblioteca para typescript
    - npm i @types/express -D
    - inicializador tipo nodemon para typescript
    - npm ts-node-dev -D
    - "dev": "ts-node-dev --exit-child src/server.ts"

- npm i prisma -D
- npx prisma init -h
- npx prisma init --datasource-provider SQLite
- npx prisma migrate
- npx prisma migrate dev (name for the new migration "create table games", "create table ads")
- npx prisma studio (interface gráfica para navegar pelo banco)
- npm i @prisma/client
- npm i cors
- npm i @types/cors -D
- npm install @radix-ui/react-dialog


