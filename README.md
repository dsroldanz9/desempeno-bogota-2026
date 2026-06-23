# Desempeño de campaña en Bogotá — segunda vuelta presidencial 2026

Un análisis que armé para entender cómo nos fue en Bogotá en la segunda vuelta. Tomé los
resultados por puesto de votación y los llevé a UPZ, localidades y estratos, y medí a cada
zona contra lo que su propio estrato y su respaldo de 2022 predecían, usando a la ciudad
misma como vara. Así separo la estructura del desempeño y se puede ver dónde rindió Bogotá
por encima de lo esperado, dónde está la fuerza, dónde queda la frontera por reconquistar
y qué hacer en el frente y de cara a las locales de 2027.

**Autor:** Daniel Santiago Roldán · [@RoldnSantiago](https://twitter.com/RoldnSantiago)

## 📄 El informe

- **[Desempeno_Bogota_interno.pdf](Desempeno_Bogota_interno.pdf)** — informe completo (10 secciones).
- **[Versión web (index.html)](index.html)** — el mismo informe para leer en el navegador.

## Qué hice

1. Casé 905 puestos de votación entre las dos vueltas de 2026 y 2022; los agregué a 90 UPZ
   y 19 localidades.
2. Usé un modelo de estrato + base de 2022 (explica el 98,6 % del nivel del voto) como
   expectativa interna de cada zona.
3. El desempeño de cada zona es su **residuo**: cuánto retuvo y movilizó por encima o por
   debajo de lo que su estructura predecía, con la vara de Bogotá.
4. Controlé los puestos no residenciales (el puesto censo de Corferias y las cárceles), que
   distorsionan la lectura por estrato.

## Hallazgos

- La caída del voto fue pareja por toda la ciudad (−7,1 pts); es una tarea de marca para
  toda Bogotá.
- La **fuerza** está en el sur popular (estratos 1–2, el 41 % de los votos), donde la
  movilización es el músculo.
- La **frontera** por reconquistar es la clase media (estratos 3–4, el 52 % de los votos),
  con la mayor caída en el estrato medio-alto.
- Las zonas que se separaron del patrón: Santa Fe, Las Nieves y Galerías por retención;
  Ciudad Usme, El Tesoro, Lucero y Río Tunjuelo por movilización.

## Datos (derivados de fuentes públicas de la Registraduría)

- [Desempeno_UPZ_Bogota.csv](Desempeno_UPZ_Bogota.csv) — las 90 UPZ con todos sus indicadores.
- [Desempeno_Localidades_Bogota.csv](Desempeno_Localidades_Bogota.csv) — las 19 localidades.
- [Lectura_Estratos_Bogota.csv](Lectura_Estratos_Bogota.csv) — los estratos 1–6.

Fuentes: Registraduría Nacional (preconteo de primera vuelta, detalle por mesa de segunda
vuelta, archivo MMV 2022); estrato del puesto por catastro de Bogotá.
