# Primera activitat de GIT
## Explicació del codi del fitxer script.js

En aquest docuemnt s'explica el codi de cadascun dels exercicis 

## Exercici 1
Explicació 
### Codi
```javascript
document.addEventListener("DOMContentLoaded", () => {
    let header1 = document.querySelector("h1");
    header1.style.color = "blue";
});

```

## Exercici 2
Explicació 
### Codi
```javascript
let paragraf = document.getElementById("paragraf-hola")
paragraf.textContent="Hola Mon "
```

## Exercici 
Explicació
### Codi
```javascript
let imatge = document.getElementById("imatge-canviant")
imatge.setAttribute("src","https://ethic.es/wp-content/uploads/2023/03/imagen-640x384.jpg")
```

## Exercici 4
Explicació
### Codi
```javascript
let boton=document.getElementById("boto-alerta")

boton.addEventListener("click", ()=>{
    let fons=document.getElementById("caixa-estil")
    fons.style.backgroundColor="green"
})
```

## Exercici 5
Explicació
### Codi
```javascript
let botoActiu=document.getElementById("boto-toggle")
botoActiu.addEventListener("click",()=>{
    let texactiu=document.getElementById("text-classe")
    texactiu.classList.toggle("actiu")
})
```

## Exercici 6
Explicació
### Codi
```javascript
boton.addEventListener("click",()=>{
    alert("alerta")
})
```

## Exercici 7
Explicació
### Codi
```javascript
let llista=document.getElementById("llista-compra")
nouItem=document.createElement("li")
nouItem.textContent="Agua"
llista.appendChild(nouItem)
```

## Exercici 8
Explicació
### Codi
```javascript
let tocarEliminar = document.getElementById("element-eliminar");
tocarEliminar.addEventListener("click", () => {
    tocarEliminar.remove();
});8
```

---
