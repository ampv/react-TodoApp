## ¿Qué veremos en esta sección?

    1.Redux
    2.Store
    3.Middlewares
    4.Dispatch
    5.Actions
    6.State
    7.Acciones asíncronas
    8.RTK Query
    9.Redux Toolkit
    10.Slices

## ¿Qué es Redux?

| - Es un contenedor predecible del estado de la aplicación.
| - Es una forma de controlar donde se encuentra la información de la aplicación y poder controlarla en todo momento.
| - Redux es totalmente diferente a lo que es, por ejemplo: React Redux, Redux Toolkit, etc.
| - Redux es el patron que se basa en crear nuevos estados basados en reducer.
|  
| ¿Qué es el Store? -- Concepto nuevo
| - Es la fuente única de la verdad, es decir. Ahí es donde está la información que los componentes van a consumir.
| - Es similar al reducer.
| - Todo proceso es sincrono, pero en caso de necesitar un proceso asincrono como podría serlo un login, se requiere de un middleware.

## ReduxToolkit

    1. https://redux-toolkit.js.org/
    2. https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en
    3. npm install @reduxjs/toolkit react-redux

## API

    1. https://pokeapi.co/

## AXIOS

    1. npm add axios

## RTK QUERY

    1. evitar hacer posteos y traer información duplicada si ya se encuentra en el cache de la información.
    2. hace parte del redux-toolkit