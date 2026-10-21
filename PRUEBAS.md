# Casos de prueba
Probados por: isabela martinez peñaloza · Fecha: 20/10/2026

| # | Caso | Cómo se prueba | Resultado esperado | Resultado |
|---|---|---|---|---|
| 1 | La página carga | Abrir index.html con Live Server | Se ve el nombre del proyecto, sin mensajes en rojo | ⬜ |
| 2 | Datos del proyecto | Revisar el encabezado | Nombre, descripción y versión coinciden con datos/equipo.json | ⬜ |
| 3 | Integrantes completos | Contar las tarjetas | Hay una tarjeta por cada integrante del README | ⬜ |
| 4 | Enlaces a GitHub | Clic en cada @usuario | Abre el perfil correcto | ⬜ |
| 5 | JSON válido | Abrir datos/equipo.json en VS Code | VS Code no marca errores en rojo | ⬜ |
| 6 | Vista en celular | F12 › modo dispositivo móvil | Las tarjetas se acomodan en una columna | ⬜ |
| 7 | Página publicada | Abrir la URL de GitHub Pages | Se ve igual que en Live Server | ⬜ |
   Si un caso falla: abrir un Issue con la etiqueta `bug`, explicar qué pasó y asignarlo a quien corresponda.