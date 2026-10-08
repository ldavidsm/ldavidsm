<div align="center">


<a href="https://luissenramirabal.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3200&pause=900&color=FFD43B&center=true&vCenter=true&width=640&lines=Backends+que+aguantan+en+producci%C3%B3n+%F0%9F%90%8D;Python+%C2%B7+FastAPI+%C2%B7+PostgreSQL+%C2%B7+Power+BI;API-first+%C2%B7+Clean+Architecture+%C2%B7+async;De+consultas+lentas+a+milisegundos+%E2%9A%A1" alt="Typing SVG" />
</a>

<p>
  <a href="https://luissenramirabal.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/luis-david-senra-mirabal-483837296/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:lsenramirabal@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://komarev.com/ghpvc/?username=ldavidsm&label=Visitas&color=3776AB&style=flat-square" alt="Visitas al perfil" />
<img src="https://img.shields.io/github/followers/ldavidsm?label=Seguidores&style=flat-square&color=009688" alt="Seguidores" />

</div>

---

## 🐍 Sobre mí

Soy **ingeniero en Ciencias Informáticas** y construyo **backends y pipelines de datos que aguantan en producción**. Vengo de dos años administrando y optimizando las bases de datos del ecosistema **DecidimOS**, y ahora desarrollo APIs REST y automatizaciones con IA.

```python
from dataclasses import dataclass, field


@dataclass(frozen=True)
class Developer:
    name: str = "Luis David Senra Mirabal"
    role: str = "Backend Python & Data"
    base: str = "Madrid, España"

    backend: tuple[str, ...] = ("Python", "FastAPI", "SQLAlchemy", "Pydantic")
    data: tuple[str, ...] = ("PostgreSQL", "MySQL", "Power BI", "Grafana")
    practices: tuple[str, ...] = ("API-first", "Clean Architecture", "async", "SQL tuning")

    motto: str = "Si la consulta tarda más que un café, no está terminada."
```

- ⚡ **Lo que mejor se me da:** diseñar la API primero, exprimir consultas SQL lentas hasta dejarlas en milisegundos y convertir datos crudos en algo con lo que se pueda decidir
<!-- 🏛️ **Acabo de publicar** [**FastAPI Clean Architecture**](https://github.com/ldavidsm/fastapi-clean-architecture): plantilla con entidades, casos de uso, puertos y presentadores, con la regla de dependencias comprobada en CI-->
- 💬 **Pregúntame sobre** FastAPI, optimización de PostgreSQL, modelado de datos o dashboards.

## 🧰 Stack

<table>
  <tr>
    <td align="center" width="140"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,fastapi&perline=10" alt="Python, FastAPI" /></td>
  </tr>
  <tr>
    <td align="center"><b>Datos</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=postgres,mysql,grafana&perline=10" alt="PostgreSQL, MySQL, Grafana" /><br />
      <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nextjs,react,ts&perline=10" alt="Next.js, React, TypeScript" /></td>
  </tr>
  <tr>
    <td align="center"><b>DevOps &amp; automatización</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=docker,git,github&perline=10" alt="Docker, Git, GitHub" /><br />
      <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
    </td>
  </tr>
</table>

## 🚀 Proyectos destacados

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/ldavidsm/pytest-querycount">pytest-querycount</a></h3>
      <a href="https://pypi.org/project/pytest-querycount/"><img src="https://img.shields.io/pypi/v/pytest-querycount?style=flat-square&color=3776AB&label=PyPI" alt="PyPI" /></a>
      <a href="https://pypi.org/project/pytest-querycount/"><img src="https://img.shields.io/pypi/dm/pytest-querycount?style=flat-square&color=009688&label=descargas" alt="Descargas" /></a>
      <br /><br />
      Plugin publicado en PyPI que convierte un problema de rendimiento en un test rojo: hace fallar un test que lanza más consultas SQL de las debidas, detecta el patrón N+1 agrupando las consultas por forma, y encuentra índices ausentes en PostgreSQL aunque la tabla de pruebas tenga ocho filas.
      <br /><br />
      <code>pytest</code> <code>SQLAlchemy 2.x</code> <code>PostgreSQL</code> <code>asyncio</code>
    </td>
    <!--<td width="50%" valign="top">
      <h3>🏛️ <a href="https://github.com/ldavidsm/fastapi-clean-architecture">FastAPI Clean Architecture</a></h3>
      Plantilla lista para arrancar APIs con capas bien separadas: entidades, casos de uso, puertos, presentadores, controladores y repositorio async con SQLAlchemy. <code>import-linter</code> rompe el CI si alguien se salta la regla de dependencias.
      <br /><br />
      <code>FastAPI</code> <code>SQLAlchemy 2.0</code> <code>Alembic</code> <code>pytest</code>
    </td>-->
    <td width="50%" valign="top">
      <h3>🩺 <a href="https://github.com/ldavidsm/proyectoMedico">proyectoMedico</a></h3>
      Plataforma donde los médicos encuentran y se inscriben en programas de formación clínica internacional.
      <br /><br />
      <code>Python</code> <code>FastAPI</code> <code>Next.js</code>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🗄️ <a href="https://github.com/ldavidsm/sistemagestionpy">sistemagestionpy</a></h3>
      Sistema de gestión con la capa de datos sobre PostgreSQL.
      <br /><br />
      <code>Python</code> <code>PostgreSQL</code>
    </td>
    <td valign="top">
      <h3>💬 <a href="https://github.com/ldavidsm/pythonchat">pythonchat</a></h3>
      Chat en tiempo real sobre sockets, sin frameworks de por medio.
      <br /><br />
      <code>Python</code> <code>Sockets</code> <code>HTML</code>
    </td>
  </tr>
  <tr>
    <td valign="top" colspan="2">
      <h3>🌐 <a href="https://github.com/ldavidsm/portfolio">portfolio</a></h3>
      Portfolio personal desplegado en Vercel.
      <br /><br />
      <code>TypeScript</code> <code>React</code> <code>Vercel</code>
    </td>
  </tr>
</table>

## 📊 En números

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ldavidsm/ldavidsm/main/profile-summary-card-output/github_dark/0-profile-details.svg" />
  <img src="https://raw.githubusercontent.com/ldavidsm/ldavidsm/main/profile-summary-card-output/github/0-profile-details.svg" alt="Resumen del perfil" width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ldavidsm/ldavidsm/main/profile-summary-card-output/github_dark/3-stats.svg" />
  <img src="https://raw.githubusercontent.com/ldavidsm/ldavidsm/main/profile-summary-card-output/github/3-stats.svg" alt="Estrellas, commits, PRs e issues" width="49%" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ldavidsm/ldavidsm/main/profile-summary-card-output/github_dark/4-productive-time.svg" />
  <img src="https://raw.githubusercontent.com/ldavidsm/ldavidsm/main/profile-summary-card-output/github/4-productive-time.svg" alt="Commits por hora del día" width="49%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ldavidsm/ldavidsm/output/python-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/ldavidsm/ldavidsm/output/python-snake.svg" alt="Una pitón comiéndose mis contribuciones" width="100%" />
</picture>

<sub>Sí, la serpiente es una pitón. Obviamente. 🐍</sub>

</div>

## 💬 ¿Hablamos?

Abierto a oportunidades en **backend Python y datos**. Y si solo quieres hablar de FastAPI, índices en PostgreSQL o por qué tu dashboard tarda 40 segundos en cargar, también.

<div align="center">

<a href="https://luissenramirabal.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/luis-david-senra-mirabal-483837296/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:lsenramirabal@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>
