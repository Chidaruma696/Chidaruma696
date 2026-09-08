[🇬🇧 English](README.en.md)

<div align="center">
  <br/>

# Chidaruma

**錬金 · Alquimista del código.**

<br/>

*Desarrollo de software independiente y a medida · Android · Linux · Latinoamérica*

<br/>

[![Kotlin](https://img.shields.io/badge/kotlin-7f52ff?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/compose-4285f4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/compose)
[![Rust](https://img.shields.io/badge/rust-b7410e?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![TypeScript](https://img.shields.io/badge/typescript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Python](https://img.shields.io/badge/python-3776ab?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PHP](https://img.shields.io/badge/php-777bb4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![SQLite](https://img.shields.io/badge/sqlite-003b57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Arch Linux](https://img.shields.io/badge/arch%20linux-1793d1?style=for-the-badge&logo=archlinux&logoColor=white)](https://archlinux.org/)
[![XFCE](https://img.shields.io/badge/xfce-2284f2?style=for-the-badge&logo=xfce&logoColor=white)](https://xfce.org/)

</div>

---

Desarrollo software desde Latinoamérica en dos frentes: sistemas a medida para negocios que necesitan resolver su operación diaria, y proyectos de código abierto que nacen cuando la herramienta que quiero todavía no existe. Todo lo que publico aquí comparte los mismos principios: código que se puede leer, documentación que se puede seguir y aplicaciones que no incluyen anuncios, rastreadores ni dependencias innecesarias.

<br/>

## ⚗️ Áreas de trabajo

| 🧭 Proyectos propios | 🧾 Desarrollo a medida |
| --- | --- |
| Aplicaciones Android de código abierto para Latinoamérica: anime y manga con las fuentes compiladas dentro del APK, sin extensiones externas ni tiendas intermedias | Sistemas de gestión empresarial: puntos de venta, inventarios y ERP, con reglas de negocio verificadas y bitácoras inmutables |
| Herramientas para el navegador que funcionan sin servidor: generación de documentos, integración con hardware mediante Web Serial | Sitios corporativos y portfolios en Next.js, con soporte multilingüe y despliegue estático |
| Bibliotecas pequeñas y bien probadas para JavaScript y Python, publicables como paquetes | Automatización de procesos con Python, PHP y n8n: integración entre servicios, procesamiento de datos y tareas internas |
| Temas y entornos de escritorio para Linux, con instaladores multidistribución | Documentación técnica orientada a que el proyecto pueda mantenerse sin depender de su autor |

<br/>

## 📦 Proyectos publicados

| | Proyecto | Descripción | Tecnología |
| --- | --- | --- | --- |
| 📺 | [**Watanuki**](https://github.com/Chidaruma696/Watanuki) | Visor de anime para Latinoamérica: 59 fuentes en español compiladas dentro del APK, reproductor libVLC, descargas en paralelo y diez paletas inspiradas en Touhou | Kotlin · Compose · libVLC |
| 📖 | [**Yuko**](https://github.com/Chidaruma696/Yuko) | Lector de manga, la maestra de Watanuki: parsers de Kotatsu compilados, capítulos completados entre fuentes y lector de derecha a izquierda ajustado al alto | Kotlin · Compose |
| 📄 | [**Fumito**](https://github.com/Chidaruma696/Fumito) | Generador de currículum a partir de repositorios de GitHub: página estática sin servidor ni inteligencia artificial, tres plantillas, exportación a PDF y Markdown · [demostración](https://chidaruma696.github.io/Fumito/) | JavaScript · GitHub Pages |
| 🏪 | [**ToyPOS**](https://github.com/Chidaruma696/ToyPOS) | Núcleo de un punto de venta multisucursal: dominio puro, SQLite local-first, permisos con alcance, bitácora inmutable y aritmética entera de extremo a extremo | Rust · sqlx · OpenSpec |
| 🧟 | [**Win2k Undead**](https://github.com/Chidaruma696/Win2k_undead) | El escritorio de Windows 2000 recreado para XFCE 4.18 y 4.20, con instalador nativo para Arch, Debian, Ubuntu, Fedora, Void y openSUSE | Bash · GTK · xfconf |
| ⚖️ | [**Kana**](https://github.com/Chidaruma696/Kana) | Básculas Torrey desde el navegador con Web Serial: sondeo, parser con banderas de estabilidad, estabilizador probado en mostrador, reconexión automática y simulador | JavaScript · npm |
| 🏷️ | [**Tohru**](https://github.com/Chidaruma696/Tohru) | Códigos de barras de báscula para Python: EAN-13, identidad por paquete, peso embebido y tolerancia a lectores que recortan dígitos | Python · pip |
| 🌐 | [**azazel-dev**](https://github.com/Chidaruma696/azazel-dev) | Sitio portfolio en cuatro idiomas con animaciones, la presencia pública del estudio | Next.js 15 · Tailwind v4 |

<br/>

## 🛠️ Forma de trabajo

- **Arquitectura antes que velocidad.** Cada aplicación parte de un dominio claro y separado de la interfaz; las reglas de negocio se prueban solas, sin base de datos ni pantalla de por medio.
- **Local-first.** Los sistemas que construyo funcionan sin conexión y sincronizan cuando pueden. Un corte de internet no debe detener una caja ni un almacén.
- **Dependencias mínimas y auditables.** Prefiero compilar una fuente dentro del proyecto a instalar un paquete que no controlo. Lo que se incluye, se conoce.
- **Documentación como parte del producto.** Un README debe permitir instalar, entender y mantener el proyecto de corrido. Si hace falta preguntar al autor, la documentación está incompleta.
- **Identidad visual coherente.** Un sistema de diseño propio, inspirado en la página de manga, con paletas de Touhou en modo claro y oscuro, compartido por todas las aplicaciones.
- **Licencias claras.** Todo lo publicado lleva licencia abierta (Apache 2.0 o MIT) y créditos explícitos a los proyectos de los que depende.

<br/>

## 🎌 Principios

- **Latinoamérica primero.** Las aplicaciones de anime y manga existen porque la oferta legal en la región llega tarde o no llega. El día que llegue, dejarán de ser necesarias, y será una buena noticia.
- **Android abierto.** Todo lo que publico depende de que cada persona pueda instalar en su propio teléfono lo que decida. Apoyo la iniciativa [Keep Android Open](https://keepandroidopen.org/es/).
- **Sin ruido.** Ningún proyecto incluye anuncios, rastreo ni paquetes que alteren el sistema. Se instala limpio y se desinstala limpio.
- **Anime, manga, Touhou y Linux.** Son el origen de la mayoría de estos proyectos y de su estética.

<br/>

## ✉️ Contacto

Consultas profesionales y propuestas de trabajo: **jp@azazel.dev**

<br/>

<div align="center">

錬金 · れんきん

</div>
