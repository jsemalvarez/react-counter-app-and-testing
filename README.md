# CounterApp with testing

## Instalaciones
Recuerden que si desean ejecutar esta aplicación, deben de reconstruir los módulos de node así:

```
npm install
```

Y luego pueden correrlo así

```
npm start
```



En la primera aplicacion con React, creamos un `Functional Component` llamado `PrimeraApp` y aplicamos:

## Props y su desestructuracion 
```
    const PrimeraApp = ({ saludo, subtitulo }) => {
```

## PropTypes

```
PrimeraApp.propTypes = {
    saludo: PropTypes.string.isRequired
}
```

## DefaultProps

```
PrimeraApp.defaultProps = {
    subtitulo: 'Soy un subtitulo'
}
```

El segundo componente que creamos es `CounterApp`, he hicimos una introduccion general a los Hooks:

## useState

```
    const [ counter, setCounter ] = useState( value );
```
Para cambiar el valor de counter, se usa 
```
    setCounter( counter + 1);
```
Y si bien podemos pensar que hacer
```
    setCounter( counter++ );
```
es lo mismo, con `counter++` estamos haciendo `counter = counter + 1`, y en React estamos obligados a mutar el estado de las variables con las funciones destinadas, que en este caso seria `setCounter`

# Introduccion a las pruebas

- AAA
    - Arrange - Arreglar
    - Act - Actuar 
    - Assert - Afirmar
- Jest
- Expect
- toBe
- Enzyme
- Simular eventos 
