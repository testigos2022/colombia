English version below

# Testigos electorales Colombia 2022
Este es un sistema que permite construir un registro instantáneo e inmutable de votos. Se usará en las elecciones de Presidente y Congreso 2022-2026 en Colombia. Los registros son creados con reportes de testigos electorales.

# Contexto
El Consejo de Estado ha indicado que el software que se usa en Colombia para contabilizar los votos de las elecciones es fraudulento. En mayo 2022 hay elecciones de Presidente y Congreso en Colombia. Por lo tanto, se espera que haya un nuevo fraude electoral.

Más información en:
- https://www.lasillavacia.com/historias/silla-nacional/reglas-electorales-clave-para-la-oposicion-no-alcanzaran-a-aplicarse-en-2022/
- https://pares.com.co/2018/04/27/asi-se-roban-las-elecciones-en-colombia/
- https://www.semana.com/elecciones-presidenciales2018/candidatos-elecciones-presidencia-2018/articulo/polemica-por-auditoria-al-software-de-la-registraduria/568155/

# Problema
En Colombia, el conteo de votos se hace en tres etapas:
- Conteo en mesas de votación.
- Consolidado por zonas de votación (sumatoria de mesas).
- Consolidado por municipios (sumatoria de zonas).

Hay pruebas que indican que el conteo registrado en cada una de las etapas de conteo no coincide con los votos registrados en las otras etapas. Para los testigos electorales es imposible identificar estas inconsistencias en el momento en que se hace el conteo porque hay demasiada información que tienen que verificar en pocas horas.

# Solución
Crear un registro de los votos registrados en cada mesa de votación, usando información reportada por los testigos electorales. El reporte de los testigos ubicados en cada mesa de votación será accesible inmediatamente para los testigos zonales. De la misma forma, los reportes creados por los testigos zonales serán accesibles inmediatamente para los testigos municipales. De esta forma, se automatizará parte del trabajo de los testigos electorales y se garantizará que el conteo que se hace en todas las etapas sea consistente.

Además, la aplicación permitirá tomar fotografías de los documentos oficiales que se usan durante el conteo de votos (formularios E-14 y E-24). Estas fotos podrán ser usadas por los testigos zonales y municipales para hacer reclamos durante el día de las elecciones. Así mismo, las fotografías podrán ser usadas después del día de las elecciones para hacer las denuncias respectivas.

# Usuarios

## Testigos electorales
- Digitan en la aplicación los votos obtenidos por cada candidato en su mesa / zona / municipio.
- Toman fotos de los formularios E-14 y/o E-24.
- Reportan inconsistencias en cada etapa del conteo de votos.
- Reportan anomalías en los puestos de votación.

## Ciudadanos
- Reciben reportes de los resultados de las elecciones.
- Obtienen reportes de fraude electoral.

## Agente KYC
- Válida Cédula de Ciudadanía del usuario.

## Organización acreditadora
- Otorga credenciales a testigos electorales.

# Beneficios
- Registro público e inmodificable.
- Costo nulo para los observadores electorales.
- Control y participación ciudadana sobre el proceso electoral.
- Registro digital de formularios E-14 y E-24, los cuales se pueden usar como evidencia para denunciar fraude electoral.
- Software de código abierto, que puede ser auditado por cualquier persona.
- Software gratuito, creado por la sociedad civil.

# ¿Quién puede acreditar testigos electorales?
- Partidos y movimientos políticos con o sin personería jurídica.
- Movimientos sociales.
- Grupos significativos de ciudadanos que inscriban candidatos a cargos o corporaciones públicas o promuevan el voto en blanco.
- Comités independientes de promotores del voto en blanco

Fuente: https://pdf.usaid.gov/pdf_docs/PA00MVGB.pdf

<img src="https://github.com/testigos2022/colombia/blob/main/assets/img/flowchart-es.png" alt="" width="550px">

------------------------------------------------------------------------------------------------------------------------------------------------------------
English version

# Electoral observers Colombia 2022
Testigos 2022 is a system that allows building instantaneously an immutable record of votes. The system is designed for the 2022-2026 Presidential and Congressional elections in Colombia. The votes record is built with reports from electoral observers.

# Context
The Council of the Colombian Estate has indicated that the software used in Colombia to count election votes is fraudulent. In May 2022, elections for President and Congress in Colombia will take place. Therefore, it is expected that there will be a new electoral fraud.

More information at:
- https://www.lasillavacia.com/historias/silla-nacional/reglas-electorales-clave-para-la-oposicion-no-alcanzaran-a-aplicarse-en-2022/
- https://pares.com.co/2018/04/27/asi-se-roban-las-elecciones-en-colombia/
- https://www.semana.com/elecciones-presidenciales2018/candidatos-elecciones-presidencia-2018/articulo/polemica-por-auditoria-al-software-de-la-registraduria/568155/

# Problem
In Colombia, vote counting consists of three phases:
- Counting at voting tables.
- Aggregated by voting zones (sum of voting tables).
- Aggregated by municipalities (sum of voting zones).

Most often, the vote-count results at each phase do not match with the other phases. For the electoral observers it is impossible to identify these inconsistencies during the vote-counting process because there is too much information that they have to verify in a few hours (thousands of paper forms).

# Solution
Build an immutable record of the votes registered at each voting table, using information reported by the election observers. The reports of the observers located at each voting table will be immediately accessible to the zonal observers. Likewise, the reports created by the zonal witnesses will be immediately accessible to the municipal observers. Thus, part of the work of the election observers will be automatized, contributing to guarantee that the results are consistent across all the stages of the vote-counting process.

Additionally, the system allows taking photographs of the official documents used during the vote-count (E-14 and E-24 forms). These photos can be used by observers to make official complaints during election day. Likewise, the photographs may be used after election day to make lawsuits.

# Users

## Electoral observers
- Enter in the application the votes obtained by each candidate in their table / zone / municipality.
- Take photos of the E-14 and/or E-24 forms.
- Report inconsistencies at each stage of the vote-counting process.
- Report anomalies at the voting stations.

## Citizens
- Receive reports of election results.
- Obtain reports of electoral fraud.

## KYC Agent
- Validate the user's citizenship card.

## Accrediting Organization
- Provides credentials to electoral observers.

## Benefits
- Public and unchangeable registry.
- Null cost for the electoral observers.
- Citizen control and participation in the electoral process.
- Digital registry of E-14 and E-24 forms that can be used as evidence to denounce electoral fraud.
- Open-source software that anyone can audit.
- Free software, created by civil society.

# Who can issue credentials of electoral observers?
- Political parties and movements with or without legal status.
- Social movements.
- Significant groups of citizens that register candidates for public offices or corporations or promote the blank vote.
- Independent committees of blank vote promoters.

Source: https://pdf.usaid.gov/pdf_docs/PA00MVGB.pdf

<img src="https://github.com/testigos2022/colombia/blob/main/assets/img/flowchart-en.png" alt="" width="550px">

