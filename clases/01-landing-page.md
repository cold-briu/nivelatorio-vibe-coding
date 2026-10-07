# Sesión 1 de 3: Cómo hacer una landing page

**Proyecto: tu landing page personal como profesional, construida desde cero.** Una hoja de vida interactiva con una sección /now.

**Jueves 7:00 p. m. · 1 hora · Google Meet + streaming en YouTube**

## Objetivo

Que cada persona termine la clase con:

1. Su landing page personal: una presencia online propia, hecha desde cero con IA en Antigravity.
2. Su código guardado en GitHub, con historial de cambios.
3. Un link público en GitHub Pages para compartir.
4. Una primera idea de cómo colaborar con otras personas en un mismo proyecto.

La landing es el vehículo. Lo importante es GitHub: el lugar donde guardas tu progreso y trabajas con otros.

## Para quién es

Profesionales que no son ingenieros y quieren diseñar sus propios productos con buenas prácticas desde el inicio. No necesitas saber programar.

## Antes de la clase (obligatorio)

- [ ] Crear una cuenta en [github.com](https://github.com)
- [ ] Instalar [Antigravity](https://antigravity.google)
- [ ] Instalar Git
  - Mac: abre la Terminal y escribe `git --version`. Si no lo tienes, el sistema te ofrece instalarlo.
  - Windows: instala [Git for Windows](https://git-scm.com/download/win)
- [ ] Verificar que funciona: `git --version` debe mostrar un número de versión
- [ ] Tener a mano tu material: tu hoja de vida o perfil de LinkedIn, y 3 cosas en las que estás enfocado en este momento (para tu sección /now)

## Agenda

| Min | Bloque | Temas |
|---|---|---|
| 0-5 | Bienvenida | Historia: un economista que aprendió a programar solo. Demo de una landing personal terminada |
| 5-10 | Modelo mental | GitHub es como un Google Drive con historial de cambios y trabajo en equipo |
| 10-25 | Construir la landing | 1.1 Terminal, 1.2 Antigravity IDE, 1.3 Code y UI lingo. Hoja de vida interactiva + /now |
| 25-45 | Guardar y publicar | 1.4 Publish to GitHub desde Antigravity, 1.5 qué pasó por dentro (init, commit, remote, push), GitHub Pages |
| 45-55 | Colaborar | Agregar un colaborador al repo, demo en vivo con un voluntario |
| 55-60 | Cierre | Cada persona comparte su link público en el chat |

## Desarrollo

### 0-5 · Bienvenida

- Presentación personal y del nivelatorio: 3 sesiones, 3 productos cada vez más complejos.
- Mostrar el resultado final: una landing personal publicada con su link.
- El proyecto: no es la página de un negocio, es **tu presencia online como profesional**. Una hoja de vida interactiva que tú controlas, con una sección /now.
- Hilo del nivelatorio: en la sesión 3 integraremos inteligencia artificial, y mostraré mi página personal como ejemplo de hasta dónde se puede llegar.
- Reglas de juego: en Meet se puede preguntar por voz o chat; en YouTube, por chat (con retraso).

### 5-10 · Modelo mental

| Concepto | Analogía |
|---|---|
| Repositorio | Una carpeta de proyecto en la nube |
| Commit | Un punto de guardado con nombre, como en un videojuego |
| Push | Subir tus puntos de guardado a la nube |
| GitHub Pages | Convertir la carpeta en una página web pública |
| Colaborador | Alguien con permiso para editar tu carpeta |

### 10-25 · Construir la landing

**1.1 Terminal (mínimo necesario)**

```bash
pwd          # ¿dónde estoy?
ls           # ¿qué hay aquí?
mkdir TU-USUARIO.github.io   # tu usuario de GitHub, exacto y en minúsculas
cd TU-USUARIO.github.io
```

**1.2 Antigravity**

- Abrir la carpeta `TU-USUARIO.github.io` en Antigravity.

**¿Por qué ese nombre?** Si la carpeta (y el repo) se llama exactamente `TU-USUARIO.github.io`, tu página queda en `https://TU-USUARIO.github.io`, sin nada más al final. Es tu dirección personal en internet. Si te equivocas en una letra, no funciona: copia tu usuario desde tu perfil de GitHub.
- Prompt sugerido (pegar después tu hoja de vida o el texto de tu LinkedIn):

> Crea mi landing page personal como profesional, desde cero, en un solo archivo index.html.
> Secciones:
> 1. Hero con mi nombre, mi rol y una frase sobre lo que hago.
> 2. Sobre mí, en un párrafo corto.
> 3. Trayectoria como hoja de vida interactiva: cada experiencia se expande al hacer clic para ver el detalle.
> 4. Una sección /now con lo que estoy haciendo en este momento.
> 5. Contacto con un botón de llamada a la acción.
> Usa CSS y JavaScript dentro del mismo archivo y que se vea bien en celular.
> Esta es mi información: [pegar hoja de vida o LinkedIn]
> Lo que estoy haciendo ahora: [3 cosas]

- Abrir `index.html` en el navegador y pedir un cambio.

**¿Qué es /now?** Una idea de [Derek Sivers](https://nownownow.com/about): una página que responde "¿en qué estás enfocado en este momento?". No es tu hoja de vida (lo que hiciste) ni tu bio (quién eres), es tu presente. Se actualiza cada pocos meses y le dice a quien te visita qué te importa hoy. Ejemplos en [nownownow.com](https://nownownow.com).

**1.3 Lingo para pedirle bien a la IA**

| Término | Qué es |
|---|---|
| HTML | La estructura: títulos, textos, botones |
| CSS | El estilo: colores, tamaños, posiciones |
| Hero | El primer bloque grande que ves al entrar |
| CTA | Botón de llamada a la acción ("Escríbeme", "Comprar") |
| Sección | Un bloque horizontal de contenido |
| Responsive | Que se adapta a celular y computador |
| Interactivo | Que reacciona cuando haces clic o pasas el mouse |
| /now | Sección que cuenta en qué estás enfocado hoy |

### 25-45 · Guardar y publicar

**Principio de la sesión: cero terminal. Publicamos con un clic desde Antigravity, entendemos qué pasó por dentro y verificamos en github.com.**

**1.4 Publicar en GitHub desde Antigravity** (todos, en vivo)

1. Abrir el panel **Source Control** en la barra lateral izquierda (el icono de ramas, o `Cmd+Shift+G` / `Ctrl+Shift+G`).
2. Clic en **Publish to GitHub**.
3. Cuando pregunte si quieres iniciar sesión con GitHub: **Permitir**. Se abre el navegador, autorizas y vuelves a Antigravity.
4. Verificar que el nombre del repo sea exactamente `TU-USUARIO.github.io` y elegir **repositorio público** (GitHub Pages gratis solo funciona con repos públicos). **Nota:** Revisar cómo hacerlo con dos clicks como propone AF.
5. Esperar a que termine. Antigravity muestra un aviso con el link al repo.

✅ *Checkpoint: escribe "publicado" en el chat.*

**1.5 Qué pasó por dentro** (yo explico, ellos observan)

Ese clic hizo por ti lo que antes eran cinco comandos:

| Lo que hizo Antigravity | Comando de git | En palabras simples |
|---|---|---|
| Empezó a guardar historial | `git init` | Esta carpeta ahora tiene memoria |
| Creó el primer guardado | `git commit` | Un punto de guardado con nombre |
| Creó el repo en GitHub | (en github.com) | Una carpeta en la nube |
| Conectó tu carpeta con la nube | `git remote add` | Tu computador sabe a dónde subir |
| Subió los archivos | `git push` | Tus puntos de guardado ya están en la nube |

No tienen que memorizar los comandos. Tienen que reconocer las palabras cuando el agente o el IDE las usen.

**Verificar** (la habilidad más importante: la máquina hace, tú revisas)

- Abrir el repo en github.com: ¿aparece `index.html`?
- Entrar a **Commits**: ¿aparece el primer guardado?

**GitHub Pages** (todos, en el navegador)

- Con el nombre `TU-USUARIO.github.io`, GitHub publica la página solo. Esperar 1 o 2 minutos y abrir `https://TU-USUARIO.github.io`
- Si no aparece: en el repo, **Settings > Pages > Branch: main > Save**.

✅ *Checkpoint: pega tu link en el chat.*

**Ciclo de trabajo de aquí en adelante:** pedir un cambio al agente, revisar la página, y luego:

> Guarda mis cambios con un commit que describa qué cambió y súbelos a GitHub.

Verificar en github.com que el commit llegó y, 1 minuto después, que la página se actualizó.

### 45-55 · Colaborar

Demo en vivo con un voluntario:

1. **Settings > Collaborators > Add people** y agregar al voluntario.
2. El voluntario acepta la invitación desde su correo.
3. El voluntario cambia una línea directamente en github.com y hace commit.
4. Yo traigo el cambio a mi computador con `git pull`.
5. Ver el historial de commits: quién cambió qué y cuándo.

### 55-60 · Cierre

- Cada persona pega su link de GitHub Pages en el chat.
- Tarea: personalizar tu landing con 3 cambios, cada uno en su propio commit. Opcional: registrar tu página /now en [nownownow.com](https://nownownow.com).
- Adelanto de la sesión 2: un ecommerce con carrito y pagos por WhatsApp.

## Problemas frecuentes

| Problema | Solución en vivo |
|---|---|
| No aparece el botón **Publish to GitHub** | Falta Git. Mac: en la terminal escribir `git --version` y aceptar la instalación. Windows: instalar Git for Windows y reiniciar Antigravity |
| El login de GitHub no vuelve a Antigravity | Cerrar la pestaña del navegador, volver a Antigravity y repetir **Publish to GitHub** |
| `Please tell me who you are` | Pedirle al agente: "Configura git con mi nombre TU NOMBRE y mi correo TU CORREO" |
| La página no aparece en `TU-USUARIO.github.io` | Revisar que el repo se llame exactamente igual a tu usuario. Si no: **Settings > General > Repository name** y corregirlo |
| Ya tengo un repo `TU-USUARIO.github.io` | Solo se puede tener uno. Usar otro nombre (por ejemplo `mi-landing`) y la página queda en `https://TU-USUARIO.github.io/mi-landing/` |
| Elegí repositorio privado | En github.com: **Settings > General > Change visibility > Public** |
| Pages muestra error 404 | Esperar 2 minutos y verificar que el archivo se llame exactamente `index.html` |
| Nada funciona y la clase sigue | Plan B: en github.com crear el repo `TU-USUARIO.github.io` a mano, **Add file > Upload files** y arrastrar `index.html`. Resolver git después |
