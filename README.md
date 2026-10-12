# Laboratorio de sensores remotos

Laboratorio interactivo del curso **Geomática** · Ingeniería Agronómica · Universidad EAFIT · 2026‑2.

**Abrir el laboratorio:** https://luriverap.github.io/laboratorio-sensores/

Funciona en cualquier navegador y no hay que instalar ni descargar nada. La imagen satelital viene incluida en la página.

## Qué se practica

Son seis misiones en secuencia: cuatro con una imagen Sentinel‑2 real y dos con un vuelo de drone ilustrativo.

| # | Misión | Qué se hace |
|---|---|---|
| 1 | Reproducir | Armar composiciones de color (R‑G‑B) a partir de las bandas, con un medidor de parecido |
| 2 | Identificar | Reconocer coberturas por su firma espectral: bosque, pasto, suelo, agua, nube |
| 3 | Resolución | Degradar la imagen de 10 a 60 m y ver cuándo deja de distinguirse un objeto |
| 4 | Firma | Comparar el rojo (B4) con el infrarrojo cercano (B8), que es la base del NDVI |
| 5 | Vuelo | Simular el traslape entre fotos de un vuelo fotogramétrico |
| 6 | Elevación | Recorrer un perfil con ortomosaico, nube de puntos, MDS y MDT, y medir alturas |

## Cómo se usa

- **Composición:** elija en los selectores R, G y B qué banda va en cada canal.
- **Ir al punto:** los botones A–F amplían la imagen y la centran en cada punto.
- **Moverse:** con la imagen ampliada a 2× o 3×, arrástrela con el mouse.
- **Firma espectral:** un clic sobre la imagen la muestra; con «Fijar para comparar» se ven dos firmas a la vez.
- **Resolución:** cambie entre 10, 20, 30 y 60 m para ver el efecto del tamaño de píxel.

## Datos

- **Imagen:** Sentinel‑2B, nivel L2A (reflectancia de superficie), 6 de diciembre de 2025, tesela T18PUQ. Es un recorte de 6 × 6 km al norte de Montería (Córdoba), con las bandas B2, B3, B4, B8 y B11; la B11 está remuestreada de 20 a 10 m.
- **Atribución:** contiene datos modificados de Copernicus Sentinel (2025).
- **Drone:** el vuelo y el perfil de elevación son ilustrativos. No corresponden a un levantamiento real.

## Autoría

Luna Rivera Patiño, docente de Geomática, Universidad EAFIT.
