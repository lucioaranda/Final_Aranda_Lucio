# Final_Aranda_Lucio

Examen Final 

Esta aplicación web muestra:

- Nombre
- DNI
- Un mensaje

---

## Ejecutar localmente

Abrir el archivo `index.html` en un navegador web.

---

## Ejecutar con Docker

1. Construir la imagen:

```powershell
docker build -t final-aranda-lucio .

2. Correr contenedor
docker run -d -p 8080:80 final-aranda-lucio

3.Abrir en navegador
http://localhost:8080
