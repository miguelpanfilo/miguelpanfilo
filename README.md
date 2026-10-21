# Hola, soy Miguel Panfilo 👋

Soy estudiante avanzado de **Licenciatura en Sistemas** en la Universidad ORT Uruguay y Doctor en Medicina (UdelaR). Después de varios años trabajando en salud, encontré en el desarrollo de software una forma de combinar lo que más me gusta: **resolver problemas de forma estructurada y construir soluciones que realmente le sirvan a las personas**.

Tengo experiencia academica con **desarrollo backend con C# y .NET**, cuidando el diseño, la calidad del código y las buenas prácticas: como arquitectura en capas, patrones de diseño, TDD y Clean Code. Busco **integrarme a un equipo de desarrollo donde seguir creciendo profesionalmente**, aprender de personas con más experiencia y aportar mi capacidad de análisis, mi compromiso y una mirada distinta.

Montevideo, Uruguay · Ciudadano de la Unión Europea

## Tecnologías

- **Lenguajes:** C# · Java · JavaScript · TypeScript · Python · SQL
- **Backend:** .NET · ASP.NET Core · Entity Framework Core · API REST · SignalR
- **Frontend:** Angular · Blazor · RxJS · HTML/CSS
- **Datos y DevOps:** SQL Server · Oracle · Docker · Git · GitHub Actions · Azure
- **Diseño:** patrones de diseño (State, Visitor, Strategy, Factory, Facade) · SOLID · arquitectura en capas · reflection / plugins
- **Prácticas:** TDD · Clean Code · Scrum · métricas de diseño (NDepend)

##  Proyectos destacados

### [DarkKitchen](https://github.com/miguelpanfilo/DarkKitchen)
*Proyecto de **Diseño de Aplicaciones 2** · Universidad ORT Uruguay · trabajo en equipo*

Plataforma full-stack de pedidos para una cocina de delivery: API REST en .NET 8 + SPA en Angular 19.
- **Patrones de diseño:** *State* para el ciclo de vida de los pedidos, *Visitor* para los reportes, *Strategy* para los importadores, *Factory* y *Facade*.
- **Plugins con reflection:** importadores CSV / JSON / XML que se cargan como DLLs en tiempo de ejecución, con *shadow copying* para reemplazarlos sin reiniciar y aviso en tiempo real al frontend por **SignalR**.
- **Calidad:** TDD, 750+ tests, ~99 % de cobertura, métricas de diseño con NDepend y CI con GitHub Actions.

`C#` `.NET 8` `Angular 19` `EF Core` `SQL Server` `SignalR` `Docker`

### [NearDupFinder](https://github.com/miguelpanfilo/NearDupFinder)
*Proyecto de **Diseño de Aplicaciones 1** · Universidad ORT Uruguay · trabajo en equipo*

Detector de productos casi duplicados en catálogos.
- Similitud de **Jaccard** con pesos por campo y **stemming en español** (Lucene.Net); agrupación en clusters y fusión de ítems.
- Importación CSV, exportación a Excel, reservas de stock, roles y auditoría.
- **Calidad:** 440+ tests unitarios y CI con GitHub Actions.

`C#` `.NET 8` `Blazor` `EF Core` `SQL Server` `Docker`

## Contacto

[LinkedIn](https://www.linkedin.com/in/miguel-panfilo-214aa2127) · miguepanfilo@outlook.com
