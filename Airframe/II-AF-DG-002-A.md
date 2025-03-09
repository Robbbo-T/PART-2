# II-AF-DG-002-A: Structural Design Guide

**Part II: Air Vehicle Systems** \ `Airframe`

---

## 1. Propósito

Este documento desarrolla las **metodologías de diseño estructural** para el Airframe de la aeronave GAIA AIR, complementando la visión general presentada en [II-AF-OV-001-A](II-AF-OV-001-A.md). Incluye lineamientos para el cálculo de refuerzos, selección de materiales y compatibilidad con otros subsistemas.

---

## 2. Alcance

- Directrices y normas de diseño aplicables al fuselaje y componentes principales.
- Factores de seguridad (FoS), márgenes de diseño y métodos de validación.
- Interfaz con subsistemas (Avionics, Propulsión, Control).
- No profundiza en planes de mantenimiento ni en estudios de cargas detallados (ver [II-AF-MA-004-A](II-AF-MA-004-A.md) y [II-AF-AN-003-A](II-AF-AN-003-A.md)).

---

## 3. Lineamientos Generales de Diseño

1. **Normas y Estándares**  
   - Referencia principal a FAR/CS-25 u otras regulaciones aplicables.
   - Adopción de estándares ISO en materiales y procesos de fabricación.

2. **Geometría y Configuración**  
   - Consideraciones de aerodinámica (aeroperfiles, alas, empennage) que afectan la estructura.
   - Zonas de alta complejidad: uniones ala-fuselaje, montajes de motor, compartimentos presurizados.

3. **Selección de Materiales**  
   - Criterios para optar por aleaciones (Al, Ti) o composites (fibra de carbono, vidrio).
   - Factores de densidad, resistencia a la fatiga, costo y disponibilidad.
   - Compatibilidad con Part VII (Materials & Manufacturing).

4. **Factores de Seguridad y Redundancias**  
   - Definición de FoS (Factor of Safety) en función de la criticidad del componente.
   - Redundancia estructural en caso de fallo de un elemento (fail-safe, damage tolerant).

---

## 4. Cálculo de Refuerzos

1. **Zonas Críticas**  
   - Identificación de áreas sometidas a mayores esfuerzos (por ejemplo, unión ala-fuselaje, largueros, frames).
   - Métodos para evaluar fatiga en regiones sometidas a ciclos de carga repetitivos.

2. **Métodos de Análisis**  
   - **Elementos Finitos (FEA)** para simulación detallada.
   - Modelos analíticos simplificados para verificación rápida.
   - Corridas de validación en prototipos físicos o ensayos destructivos (si aplica).

3. **Refuerzos Integrados**  
   - Uso de vigas, largueros, montantes, nervios para mejorar la rigidez.
   - Revestimiento (skin) con espesores variables según distribución de cargas.

---

## 5. Compatibilidad de Subsistemas

1. **Interfaces Mecánicas**  
   - Diseñar puntos de anclaje para alas, montantes de propulsión, tren de aterrizaje.
   - Zonas de acceso para mantenimiento (hatches, paneles removibles).

2. **Avionics y Cableado**  
   - Canalizaciones y rutas protegidas para cables, evitando interferencias o daños mecánicos.
   - Análisis de peso y balance por la distribución de equipos electrónicos.

3. **Sistemas de Control**  
   - Integración de actuadores, servo-mecanismos y sus refuerzos en las superficies de control.
   - Requerimientos de espacio y cargas dinámicas.

---

## 6. Verificación y Validación

1. **Ensayos de Laboratorio**  
   - Prototipos a escala o secciones del fuselaje para ensayos de tracción, compresión, flexión.
   - Tests destructivos controlados para observar modos de fallo.

2. **Simulaciones Computacionales**  
   - Modelos FEA para cada fase de vuelo (despegue, crucero, maniobras, aterrizaje).
   - Validar que las tensiones máximas estén dentro de márgenes seguros.

3. **Inspecciones Post-Vuelo**  
   - Registros de deformaciones, fisuras, cualquier indicio de sobrecarga.
   - Actualizar el modelo de diseño si se detectan desviaciones significativas.

---

## 7. Documentos Relacionados

- [II-AF-OV-001-A](II-AF-OV-001-A.md): **Airframe Overview**  
  Describe la estructura general y el contexto del fuselaje.

- [II-AF-AN-003-A](II-AF-AN-003-A.md): **Load & Stress Analysis**  
  Presenta resultados cuantitativos de cargas y fatiga.

- [II-AF-MA-004-A](II-AF-MA-004-A.md): **Maintenance Guidelines**  
  Cobertura de los intervalos de inspección y reparación.

- [PartVII/Materials/](../../PartVII/): Referencia a propiedades de los materiales, procesos de manufactura.

---

## 8. Notas Finales

Este documento ayuda a mantener la **coherencia y calidad** en el diseño estructural del Airframe. Apoya la toma de decisiones informadas a lo largo del ciclo de vida de la aeronave, asegurando que la estructura cumpla con los requisitos de seguridad y rendimiento.

**Estado del Documento**: Draft (A). A la espera de validación por el equipo de Estructuras.

