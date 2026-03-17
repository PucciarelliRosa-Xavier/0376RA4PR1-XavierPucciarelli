# Primera activitat de GIT
## Explicació del codi del fitxer script.js

En aquest docuemnt s'explica el codi de cadascun dels exercicis 

## Exercici 1
En el següent codi s'utilitza serveix per a que es canvï el color d'un h1 quan la pàgina carreguio fent servir querySelector 
### Codi
```javascript
document.addEventListener("DOMContentLoaded", () => {
    let header1 = document.querySelector("h1");
    header1.style.color = "blue";
});

```

## Exercici 2
El següent codi serveix per a que un paràgrad mostri el text "Hola mon" modificant el seu contingut fent servir textContent.
### Codi
```javascript
let paragraf = document.getElementById("paragraf-hola")
paragraf.textContent="Hola Mon "
```

## Exercici 3
Amb el següent codi es canvia el paràmetre 'src' d'una imatge amb setAttribute.
### Codi
```javascript
let imatge = document.getElementById("imatge-canviant")
imatge.setAttribute("src","https://ethic.es/wp-content/uploads/2023/03/imagen-640x384.jpg")
```

## Exercici 4
Aquest codi serveix per canviar el color de fons d'un element quan es faci clic.
### Codi
```javascript
let boton=document.getElementById("boto-alerta")

boton.addEventListener("click", ()=>{
    let fons=document.getElementById("caixa-estil")
    fons.style.backgroundColor="green"
})
```

## Exercici 5
Amb aquest codi es fa que un botó que per afegir o treure la classe "actiu" amb classList.toggle
### Codi
```javascript
let botoActiu=document.getElementById("boto-toggle")
botoActiu.addEventListener("click",()=>{
    let texactiu=document.getElementById("text-classe")
    texactiu.classList.toggle("actiu")
})
```

## Exercici 6
En el següent codi hi ha un addEventListener per a que en fer click a un botó es mostri una alerta
### Codi
```javascript
boton.addEventListener("click",()=>{
    alert("alerta")
})
```

## Exercici 7
Amb el següent codi es crea un nou <li> amb createElement i s'afegeix a una <ul> amb appendChild.

### Codi
```javascript
let llista=document.getElementById("llista-compra")
nouItem=document.createElement("li")
nouItem.textContent="Agua"
llista.appendChild(nouItem)
```

## Exercici 8
El segÑuent codi fa que que un element desaparegui en fer-li clic gràcies al mètode remove.
### Codi
```javascript
let tocarEliminar = document.getElementById("element-eliminar");
tocarEliminar.addEventListener("click", () => {
    tocarEliminar.remove();
});8
```

---
