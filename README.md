# Chatbot simple con api OpenAI

## Introducción

Tiene implementado Next.js y su AI sdk de OpenAI. Siendo un proyecto bastante simple de realizar.


## Configuración

Es necesario crear el archivo .env para poder configurar la clave de la api Open AI (https://openai.com/blog/openai-api/)
El archivo en cuestión debe contener:

```bash
OPENAI_API_KEY=xxxxxxxxx
```

## Despliegue

Una vez clonado el repositorio y agregado el archivo .env
Ya puede desplegar el producto con el comando:

```bash
npm run dev
```

Y abrir [http://localhost:3000](http://localhost:3000) en tu navegador para empezar a probar!

## Aclaraciones

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) 

¿Como instale la dependencia que hace la magia?:

```bash
npm install ai openai
```
