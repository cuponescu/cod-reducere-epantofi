# Cod Reducere ePantofi

O colecție de coduri de reducere ePantofi. Le folosim pentru testarea cuvintelor cheie cod reducere ePantofi, voucher ePantofi, cupon ePantofi, și cod promotional ePantofi de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-epantofi` prin NPM:

```bash
npm install cod-reducere-epantofi
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-epantofi')

console.log(codes)

// [
//   {
//     site: 'https://www.epantofi.ro',
//     cod_reducere: 'PANTOFI10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toată încălțămintea'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-epantofi a fost creat de echipa de la Cuponescu pentru a ajuta cu testarea.

https://www.cuponescu.ro

