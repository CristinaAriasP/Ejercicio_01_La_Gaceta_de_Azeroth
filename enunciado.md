# Ejercicio: Crea La Gaceta de Azeroth

## Descripción
Vamos a crear la página principal de un periódico digital ambientado en el mundo de Warcraft. Deberás construir una web que muestre las últimas noticias de Azeroth, 
siguiendo una guía de estilos específica y utilizando el contenido proporcionado.

## Objetivos de Aprendizaje
- Aplicar HTML semántico
- Estructurar contenido en elementos de bloque e inline
- Implementar estilos CSS siguiendo una guía de diseño
- Practicar la organización de selectores CSS
- Trabajar con imágenes y enlaces

## Recursos Proporcionados
1. Contenido completo del periódico (textos y estructura)
2. Guía de estilos con:
   - Paleta de colores
   - Tipografía y tamaños de texto
   - Sistema de espaciado
   - Especificaciones de diseño

## Requerimientos Técnicos

### Estructura HTML
1. Debe usar los siguientes elementos:
   - `header` para la cabecera
   - `article` para las noticias
   - `section` para agrupar contenido relacionado
   - `aside` para las noticias breves
   - `footer` para el pie de página
   - `div` como contenedor cuando sea necesario

2. Elementos inline requeridos:
   - `a` para enlaces
   - `img` para imágenes
   - `span` para textos específicos
   - `strong` para énfasis

### Requerimientos CSS
1. Organización por especificidad:
   - Primero selectores de elemento
   - Luego clases de componentes
   - Finalmente clases de utilidad

2. No usar:
   - Selectores de ID (#)
   - Media queries
   - Pseudo-selectores
   - Propiedades de CSS que no hayamos visto en clase


## Proceso de Trabajo

1. **Fase de Planificación**
   - Revisar el contenido proporcionado
   - Revisar la guía de estilos
   - Identificar elementos HTML necesarios

2. **Fase de HTML**
   - Crear estructura base
   - Implementar todos los elementos
   - Añadir clases necesarias
   - Comentar el código

3. **Fase de CSS**
   - Implementar estilos base (selectores)
   - Aplicar estilos de layout o interfaz
   - Añadir clases de utilidad
   - Comentar el código

4. **Fase de Revisión**
   - Comprobar que todo funciona
   - Validar HTML y CSS
   - Verificar que se siguen las guías de estilo

## Entregables
1. Archivo HTML
2. Archivo CSS

### HTML
- [x] Uso correcto de elementos semánticos
- [x] Estructura clara y lógica
- [x] Código comentado
- [x] Indentación correcta

### CSS
- [x] Sigue la guía de estilos
- [x] Organización correcta de selectores
- [x] Código comentado
- [x] Indentación correcta

### General
- [x] Similitud con el diseño propuesto
- [x] Limpieza del código
- [x] Cumplimiento de todos los requisitos
- [x] Entrega de todos los elementos solicitados


## Notas
- No se permite usar frameworks o librerías externas
- El código debe estar perfectamente indentado
- Cada sección debe estar comentada
- Se valorará la limpieza del código


STYLEGUIDE

# Guía de Estilos - La Gaceta de Azeroth

## Paleta de Colores

### Colores Principales

-   **Dorado Principal:** #C0A060 (para títulos y acentos)
-   **Azul Oscuro:** #1A2C4E (color base para textos)
-   **Crema:** #F5E6D3 (fondo principal)

### Colores Secundarios

-   **Rojo Horda:** #8C1616
-   **Azul Alianza:** #1A3C8C
-   **Gris Neutro:** #707070 (textos secundarios)

## Tipografía

### Fuentes

1. **Títulos:**

    - Familia: Georgia, Garamond, serif

2. **Cuerpo:**
    - Familia: Arial, Verdana, sans-serif

### Tamaños de Fuente

-   **h1 (Título Principal):** 2.5rem (40px)
-   **h2 (Títulos de Sección):** 2rem (32px)
-   **h3 (Títulos de Noticia):** 1.75rem (28px)
-   **h4 (Subtítulos):** 1.5rem (24px)
-   **h5 (Títulos Pequeños):** 1.25rem (20px)
-   **Cuerpo de texto:** 1rem (16px)
-   **Texto pequeño:** 0.875rem (14px)

## Espaciado

### Márgenes

-   **Contenedor Principal:** max-width: 1200px, margin: 0 auto
-   **Entre Secciones:** margin-bottom: 3rem (48px)
-   **Entre Artículos:** margin-bottom: 2rem (32px)
-   **Entre Párrafos:** margin-bottom: 1rem (16px)

### Padding

-   **Contenedor Principal:** padding: 0 20px
-   **Cabecera:** padding: 2rem 0
-   **Secciones:** padding: 1.5rem
-   **Cards de Noticias:** padding: 1.25rem

## Elementos Específicos

### Cabecera

-   Fondo degradado: linear-gradient(45deg, #1A2C4E, #2A3C5E)
-   Texto en dorado (#C0A060)
-   Sombra de texto: text-shadow: 2px 2px 4px rgba(0,0,0,0.5)

### Enlaces

-   **Color Normal:** #1A3C8C
-   **Hover:** #C0A060
-   **Transición:** 0.3s ease-in-out
-   **Subrayado:** none (aparece en hover)

### Imágenes

-   **Border-radius:** 4px
-   **Sombra:** box-shadow: 0 4px 8px rgba(0,0,0,0.1)
-   **Hover:** transform: scale(1.02)
-   **Transición:** 0.3s ease-in-out

### Cards de Noticias

-   **Fondo:** #FFFFFF
-   **Borde:** 1px solid rgba(192,160,96,0.2)
-   **Border-radius:** 8px
-   **Sombra:** box-shadow: 0 2px 4px rgba(0,0,0,0.05)

# El Heraldo de Azeroth
*Tu Fuente Diaria de Verdad a través de los Reinos*

## Últimas Noticias (Historia Principal)
### Sylvanas Windrunner Desaparece Tras el Juicio en Oribos
**Por:** Chromie, Guardián del Tiempo
**Fecha:** 27 de Noviembre, 2024

La ex-Jefa de Guerra de la Horda ha desaparecido misteriosamente tras su polémico juicio en Oribos. Los testigos informan haberla visto por última vez en compañía de Tyrande Whisperwind, aunque la líder de los Elfos de la Noche niega cualquier participación en su desaparición.

"La situación es más compleja de lo que parece", declaró Thrall, ex-Jefe de Guerra, quien sirvió como testigo durante el juicio. "El equilibrio entre la justicia y la redención es delicado, especialmente considerando los eventos recientes en las Shadowlands."

Los Kyrian han iniciado una búsqueda exhaustiva en todos los reinos de las Shadowlands, mientras que los agentes del SI:7 investigan posibles avistamientos en Azeroth.

## Guerra y Política

### El Consejo de Stormwind Debate sobre la Embajada Forsaken
La propuesta de establecer una misión diplomática Forsaken en la ciudad ha provocado acalorados debates entre el liderazgo de la Alianza. El Alto Rey Anduin Wrynn apoya la iniciativa como un paso hacia la paz duradera.

### Thunder Bluff Organiza Cumbre de Paz Histórica
Representantes de todas las órdenes druídicas se reunieron en Thunder Bluff para el primer Consejo Cenarion Unido, abordando preocupaciones ambientales tanto en Azeroth como en las Shadowlands.

## Comercio y Economía

### El Cartel Goblin Abre Ruta Comercial Oribos-Orgrimmar
El Cartel Bilgewater ha establecido una ruta comercial revolucionaria que conecta la capital de la Horda con las Shadowlands. Los precios de los materiales exóticos han caído un 40%.

### La Reforma de la Casa de Subastas Causa Caos en el Mercado
Los cambios recientes en las políticas de la casa de subastas entre facciones han llevado a fluctuaciones sin precedentes en el mercado. Los comerciantes goblin informan de beneficios récord mientras los mercados tradicionales basados en facciones luchan por adaptarse.

## Arqueología y Exploración

### Ruinas Titánicas Descubiertas Bajo Tanaris
La Liga de Exploradores ha desenterrado un complejo de ruinas que sugiere una presencia Titánica previamente desconocida. Brann Bronzebeard lidera la expedición.

### Evidencia de Imperio Troll Perdido Encontrada en Zandalar
Los hallazgos arqueológicos en Zandalar apuntan a una antigua civilización troll que podría ser anterior al propio Imperio Zandalari. La Reina Talanji ha concedido acceso limitado de investigación a los eruditos de la Alianza.

## Noticias Breves

### Política y Diplomacia
- Aumentan las tensiones en el Consejo de Dalaran por la propuesta de admitir magos no-muertos
- La delegación de Elfos de la Noche busca residencia permanente en Orgrimmar
- El proyecto de recuperación de Gnomeregan entra en la fase 3

### Economía
- Los precios del Azerita alcanzan máximos históricos
- El gremio de Joyería anuncia nuevo programa de aprendizaje
- Depósitos de plata tormentosa descubiertos en el puerto de Boralus

### Militar
- La Guardia de Stormwind comienza a reclutar exploradores Vulpera
- Silvermoon fortalece las defensas mágicas
- Ironforge revela nuevo prototipo de máquina de asedio

### Sociedad y Cultura
- Los maestros cerveceros Pandaren autorizados para abrir tabernas en Stormwind
- El festival cultural de los Tauren de Altamontaña atrae multitudes récord
- Anunciados nuevos tours temporales del Azeroth pre-Cataclismo

### Medio Ambiente
- Anomalías mágicas causan nevada en Durotar
- Los druidas informan de patrones inusuales de migración animal en Feralas
- El Círculo Cenarion monitorea crecimiento inesperado de plantas en Desolace

### Deportes y Entretenimiento
- Equipo goblin gana el Campeonato de Bola Cohete por primera vez
- La Feria de la Luna Negra añade nueva atracción: "Baila con los Dragones"
- Torneo de Hearthstone en Gadgetzan termina en caos tras acusaciones de trampa

### Académico
- Nueva ala de estudios de magia abre en Dalaran
- Los monjes del Templo de Jade ofrecen entrenamiento a todas las facciones
- Avance en técnicas de Inscripción promete glifos más duraderos