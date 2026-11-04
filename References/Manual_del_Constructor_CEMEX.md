# Referencia Técnica: Manual del Constructor CEMEX

- **Archivo Original:** [Manual_del_Constructor_CEMEX.pdf](file:///g:/My%20Drive/MDCP/References/Manual_del_Constructor_CEMEX.pdf)
- **Autor / Entidad:** CEMEX (Área de Servicios Técnicos y Asesoría al Constructor).
- **Extensión:** 102 páginas técnicas repletas de tablas numéricas, fórmulas de ingeniería, proporciones y diagramas de diseño.
- **Enfoque Principal:** Prontuario y manual de bolsillo para maestros de obra, ingenieros residentes y constructores, con datos precisos de dosificación de concreto, pesos de materiales, cálculo estructural simplificado, instalaciones eléctricas e hidráulicas.

---

## 1. Propósito y Estructura del Manual CEMEX

El *Manual del Constructor CEMEX* es una obra de referencia técnica de campo ("vademécum de obra"). A diferencia de las cartillas sociales ilustradas, su fortaleza es la **precisión cuantitativa**: contiene tablas exactas de rendimiento de materiales, consumo de cemento por metro cúbico, propiedades físicas, químicas y mecánicas del concreto, y fórmulas para instalaciones de servicios.

```mermaid
graph LR
    A[Cap. I: Unidades y Geometría] --> B[Cap. II: Pesos y Densidades de Materiales]
    B --> C[Cap. III-V: Cemento y Mezclas de Concreto]
    C --> D[Cap. VI: Diseño de Elementos Estructurales]
    D --> E[Cap. VII-VIII: Electricidad e Instalaciones Hidráulicas]
```

---

## 2. Desglose Temático Detallado

### 2.1. Sistema Internacional de Unidades y Geometría Práctica (Capítulo I, pp. 5 - 10)
*   **Tablas de Conversión:** Factores exactos entre el Sistema Internacional (SI) y el Sistema Inglés (pulgadas, pies, yardas, libras, galones, psi a MPa, $\text{kg/cm}^2$, bar).
*   **Geometría y Trigonometría de Obra:**
    *   Fórmulas de área y volumen de cuerpos: prismas, cilindros, pirámides, conos, esferas, casquetes y segmentos circulares.
    *   Resolución de triángulos rectángulos y oblicuángulos (Ley de senos y cosenos, fórmula de Herón para áreas de terrenos irregulares conociendo sus tres lados).

### 2.2. Densidades y Pesos Volumétricos de Materiales (Capítulo II, pp. 11 - 14)
Tablas indispensables para el cálculo de cargas muertas y cubicación de fletes y transporte:

| Material | Densidad / Peso Volumétrico Suelto ($\text{kg/m}^3$) | Peso Compactado ($\text{kg/m}^3$) |
| :--- | :---: | :---: |
| **Arena de río seca** | $1,400 - 1,500$ | $1,600 - 1,750$ |
| **Arena saturada / húmeda** | $1,600 - 1,800$ | $1,900 - 2,050$ |
| **Grava / Triturado común** | $1,450 - 1,550$ | $1,650 - 1,750$ |
| **Cemento Portland a granel / sacos** | $1,500$ (en saco $50\text{ kg} \approx 33\text{ L}$) | — |
| **Concreto simple (sin acero)** | $2,200 - 2,300$ | — |
| **Concreto reforzado (con acero)** | $2,400$ | — |
| **Mortero de cemento y arena** | $1,900 - 2,100$ | — |
| **Ladrillo macizo de arcilla** | $1,600 - 1,800$ | — |
| **Ladrillo hueco / Bloque perforado** | $900 - 1,200$ | — |
| **Bloque de concreto hueco** | $1,300 - 1,500$ | — |
| **Madera estructural seca** | $500 - 900$ (según especie) | — |

*   **Coeficientes de fricción suelo-concreto:** Factores de rozamiento para el cálculo de zapatas y muros de contención contra deslizamiento (suelo cohesivo, arena compacta, grava).

### 2.3. Cemento y Mezclas de Concreto (Capítulos III, IV y V, pp. 15 - 37)
*   **Química del Cemento Portland:** Función de los silicatos tricálcico ($C_3S$: resistencia inicial) y dicálcico ($C_2S$: resistencia a largo plazo), aluminato tricálcico ($C_3A$: fraguado y calor de hidratación) y ferroaluminato tetracálcico ($C_4AF$).
*   **Dosificaciones típicas de concreto recomendadas para obras pequeñas (por sacos de 50 kg):**

| Resistencia $f'_c$ a 28 días | Usos Típicos en Obra | Cemento (sacos 50 kg) | Arena (cajones $30\times30\times30$ cm) | Grava (cajones $30\times30\times30$ cm) | Agua aprox. (Litros) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| **100 kg/cm² (10 MPa)** | Solados, plantillas, limpieza | $1.0$ | $3.5$ | $5.5$ | $32$ |
| **150 kg/cm² (15 MPa)** | Andenes, pisos peatonales | $1.0$ | $2.5$ | $4.0$ | $28$ |
| **200 kg/cm² (20 MPa)** | Zapatas, vigas de cimentación | $1.0$ | $2.0$ | $3.0$ | $25$ |
| **250 kg/cm² (25 MPa)** | Columnas, losas de entrepiso | $1.0$ | $1.5$ | $2.5$ | $22$ |
| **300 kg/cm² (30 MPa)** | Estructuras especiales | $1.0$ | $1.0$ | $2.0$ | $20$ |

*   **Patologías y problemas comunes del concreto:**
    *   *Agrietamiento plástico:* Ocurre por evaporación rápida del agua en clima cálido o ventoso. Solución: regado con agua nebulizada o aplicación de membrana de curado inmediatamente después del afinado.
    *   *Eflorescencia (salitre):* Sales solubles que migran a la superficie. Solución: usar agregados limpios lavados y reducir la permeabilidad con baja relación agua/cemento.
    *   *Bajas resistencias:* Causadas casi siempre por exceso de agua en la revoltura ("aguada"), curado deficiente o arena sucia con limos.
    *   *Falso fraguado:* Pérdida prematura de plasticidad sin liberación notable de calor; puede re-mezclarse enérgicamente sin añadir más agua.
*   **Concreto en clima cálido:** Medidas para evitar fraguado acelerado (sombrear agregados, usar agua fría o con hielo, colar temprano en la mañana o al atardecer).
*   **Control de calidad y ensaye de cilindros:** Procedimiento normalizado para la prueba de revenimiento (cono de Abrams: asentamiento típico de 7.5 a 10 cm para elementos comunes) y toma de probetas cilíndricas ($15\times30$ cm o $10\times20$ cm) falladas a los 7, 14 y 28 días.

### 2.4. Diseño de Estructuras (Capítulo VI, pp. 38 - 77)
*   **Acciones de diseño:** Combinaciones de cargas permanentes (muertas) y variables (vivas) según los códigos de diseño.
*   **Cálculo de flexión en vigas:** Diagramas de momento flector ($M$) y cortante ($V$), cálculo de cuantías de acero longitudinal ($A_s = M / (\phi f_y j d)$) y cálculo de estribos por cortante.
*   **Columnas:** Efectos de esbeltez, confinamiento de estribos y diagramas de interacción carga axial - momento flector.
*   **Zapatas:** Esfuerzo de contacto admisible del suelo ($q_{adm}$), punzonamiento o cortante bidireccional, y verificación de peralte mínimo para anclaje de varillas.

### 2.5. Instalaciones Eléctricas (Capítulo VII, pp. 78 - 90)
*   **Unidades y Ley de Ohm:** $V = I \cdot R$; Potencia activa $P = V \cdot I \cdot \cos \phi$.
*   **Tabla de Calibres de Conductores de Cobre (AWG):**
    *   *AWG #14:* Capacidad 15 A (circuitos de iluminación).
    *   *AWG #12:* Capacidad 20 A (circuitos de tomacorrientes de uso general).
    *   *AWG #10:* Capacidad 30 A (estufas eléctricas, calentadores de paso, aires acondicionados).
    *   *AWG #8:* Capacidad 40-50 A (alimentadores principales de tableros).
*   **Ocupación de tubería Conduit:** Tablas de diámetro mínimo de ducto (1/2", 3/4", 1") según el número de cables para no sobrepasar el 40% del área interna del tubo.

### 2.6. Instalaciones Hidráulicas y Sanitarias (Capítulo VIII, pp. 91 - 102)
*   **Pérdidas de carga por fricción:** Tablas basadas en la fórmula de Hazen-Williams ($C=100$ para hierro fundido, $C=140-150$ para PVC).
*   **Longitudes equivalentes de accesorios:** Equivalencia en metros lineales de tubería recta para codos de 90°, codos de 45°, tes de paso directo, tes de desvío y válvulas de compuerta o globo.
*   **Cálculo de gastos por Unidades Hunter:** Demanda máxima simultánea para agua fría y caliente en residencias.

---

## 3. Relevancia Directa para el *Manual del Constructor Popular Colombiano*

El manual de CEMEX es la fuente técnica ideal para alimentar:
1. **Módulo 5 (Cantidades y Presupuestos - El Bolsillo):** Las tablas de dosificación por volumen (cajón de $30\times30\times30$ cm o balde de 20 L) y los rendimientos por $m^3$ de concreto y mortero.
2. **Módulo 4 (Las Venas de la Casa):** Dimensionamiento de calibres de cables eléctricos (AWG) y pérdidas en tuberías de agua potable de PVC.
3. **Módulo 2 (Concretos):** Reglas preventivas para vaciado de concreto en clima caluroso (aplicable a Buenaventura, Costa Caribe y valles interandinos).
