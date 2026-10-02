[🇬🇧 English](README.md)

<div align="center">
  <br/>

# Chidaruma

**錬金 · Alquimista del código.**

<br/>

*Desarrollo de software independiente y a medida · Linux · Latinoamérica*

<br/>

[![Kotlin](https://img.shields.io/badge/kotlin-7f52ff?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Rust](https://img.shields.io/badge/rust-b7410e?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![TypeScript](https://img.shields.io/badge/typescript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Python](https://img.shields.io/badge/python-3776ab?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PHP](https://img.shields.io/badge/php-777bb4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![SQLite](https://img.shields.io/badge/sqlite-003b57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Arch Linux](https://img.shields.io/badge/arch%20linux-1793d1?style=for-the-badge&logo=archlinux&logoColor=white)](https://archlinux.org/)

</div>

---

Desarrollo software desde Latinoamérica en dos frentes: sistemas a medida para negocios que necesitan resolver su operación diaria, y proyectos de código abierto que nacen cuando la herramienta que quiero todavía no existe. Todo lo que publico aquí comparte los mismos principios: código que se puede leer, documentación que se puede seguir y aplicaciones que no incluyen anuncios, rastreadores ni dependencias innecesarias.

<br/>

## ⚗️ Áreas de trabajo

| 🧭 Proyectos propios | 🧾 Desarrollo a medida |
| --- | --- |
| Herramientas para Arch Linux y GNOME: un instalador que termina de una pasada, una tienda de software en la terminal, los colores del fondo en todo el escritorio | Sistemas de gestión empresarial: puntos de venta, inventarios y ERP, con reglas de negocio verificadas y bitácoras inmutables |
| Herramientas para el navegador que funcionan sin servidor: grabación de pantalla exportada sin instalar ni subir nada | Sitios corporativos y portfolios en Next.js, con soporte multilingüe y despliegue estático |
|  | Automatización de procesos con Python, PHP y n8n: integración entre servicios, procesamiento de datos y tareas internas |
|  | Documentación técnica orientada a que el proyecto pueda mantenerse sin depender de su autor |

<br/>

## 📦 Proyectos publicados

| | Proyecto | Descripción | Tecnología |
| --- | --- | --- | --- |
| ⛩️ | [**Reimu**](https://github.com/Chidaruma696/Reimu) | Instalador de Arch Linux en Bash: hace las preguntas correctas (sistema de archivos, swap, cifrado, bootloader, escritorio) y termina el trabajo en una sola pasada: LUKS2, snapshots btrfs, systemd-boot o GRUB, drivers, AUR, paquetes de software, configuraciones repetibles | Bash · ISO de Arch |
| 🌿 | [**Sanae**](https://github.com/Chidaruma696/Sanae) | Tienda de software para Arch Linux que vive en la terminal: estantes de AppStream con nombres humanos y popularidad, repositorios y AUR en una sola búsqueda, actualizaciones con las noticias de Arch, cola con vista previa, y recetas que instalan y configuran (Docker, QEMU, fuentes, temas de XFCE). Reimu ofrece instalarla al terminar | Rust · ratatui · pacman |
| ◉ | [**Satori**](https://github.com/Chidaruma696/Satori) | Grabador de pantalla que vive en el navegador: graba una pantalla o ventana, recorta tiempo y área, y exporta MP4, WebM o GIF sin instalar ni subir nada · [úsalo](https://chidaruma696.github.io/Satori/) | TypeScript · WebCodecs · GitHub Pages |
| 🩸 | [**Flandre**](https://github.com/Chidaruma696/Flandre) | Colores del fondo de pantalla para todo el escritorio GNOME en un solo binario: Shell, apps libadwaita y GTK 3, iconos Tela o Papirus, Ptyxis, Console, Black Box y cada terminal abierta se regeneran con cada cambio de fondo o de modo claro/oscuro, con ventana de ajustes libadwaita y previsualización en vivo | Rust · GTK 4 · libadwaita |
| 🏷️ | [**Chimata**](https://github.com/Chidaruma696/Chimata) | Códigos de barras de báscula para Python: identidad por paquete o peso en los dígitos, tolerancia a lectores que se comen dígitos, y el formato de cada báscula escrito en un archivito Lisp que se lee y nunca se ejecuta. Sin dependencias | Python · Lisp · EAN-13 |
| 🌐 | [**azazel-dev**](https://github.com/Chidaruma696/azazel-dev) | Sitio portfolio en cuatro idiomas con animaciones, la presencia pública del estudio | Next.js 15 · Tailwind v4 |

<br/>

## 🛠️ Forma de trabajo

- **Arquitectura antes que velocidad.** Cada aplicación parte de un dominio claro y separado de la interfaz; las reglas de negocio se prueban solas, sin base de datos ni pantalla de por medio.
- **Local-first.** Los sistemas que construyo funcionan sin conexión y sincronizan cuando pueden. Un corte de internet no debe detener una caja ni un almacén.
- **Dependencias mínimas y auditables.** Prefiero compilar una fuente dentro del proyecto a instalar un paquete que no controlo. Lo que se incluye, se conoce.
- **Documentación como parte del producto.** Un README debe permitir instalar, entender y mantener el proyecto de corrido. Si hace falta preguntar al autor, la documentación está incompleta.
- **Licencias claras.** Todo lo publicado lleva licencia abierta (Apache 2.0 o MIT) y créditos explícitos a los proyectos de los que depende.
- **Software de una sola persona.** Algunos de estos proyectos los uso a diario y otros están todavía madurando; cada README dice en qué punto va. Se publican tal cual, sin garantía, como cualquier proyecto abierto. Si algo no te funciona, abre una issue y lo vemos.
- **Y sí, uso IA.** En algunos de mis proyectos me ayudo con inteligencia artificial, como ayuda, no como sustituto. Eres libre de revisarlos o rechazarlos si así te apetece, o puedes ayudarme a mejorarlos: los *issues* y los *pull requests* están abiertos.

<br/>

## 🎌 Principios

- **Android abierto.** Cada persona debería poder instalar en su propio teléfono lo que decida. Apoyo la iniciativa [Keep Android Open](https://keepandroidopen.org/es/).
- **Sin ruido.** Ningún proyecto incluye anuncios, rastreo ni paquetes que alteren el sistema. Se instala limpio y se desinstala limpio.
- **Anime, manga, Touhou y Linux.** Son el origen de la mayoría de estos proyectos y de su estética. Touhou Project y sus personajes (Reimu, Sanae, Satori, Flandre y Chimata) pertenecen a Team Shanghai Alice (ZUN); los proyectos que llevan sus nombres son obras de fans no oficiales, hechas según sus directrices para obras derivadas, sin afiliación ni respaldo.

<br/>

## ✉️ Contacto

Consultas profesionales y propuestas de trabajo: **jp@azazel.dev**

<br/>

<div align="center">

錬金 · れんきん

</div>
