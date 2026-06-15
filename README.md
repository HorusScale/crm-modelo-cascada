# El CRM como cascada gateada — modelo conceptual

Explainer interactivo del modelo que comparten los operativos comerciales de
Horus Scale (NIMED · CRM interno BOS · ADO · JD Emirates). Pensado para
explicar el modelo a una sola voz, sin glosario denso.

**Página publicada:** GitHub Pages (ver el entorno del repo).

## Qué contiene

- **Recorrido guiado animado** — 9 pasos que iluminan el modelo en orden y
  animan la cadena `Acción → Resultado → mueve de cola`, el zoom fractal a una
  fase con tabs, y los roles/zonas.
- **Modelo en vivo** — colas por estado con casos que saltan de cola al elegir
  un resultado; una fase con tabs que hace zoom a su mini-cascada; switcher de
  rol que demuestra *ver ≠ actuar*.
- **Mapa conceptual clicable** — cada término del vocabulario, definido una vez.

## El modelo, en una línea

> Flujo cerrado → **cascada gateada** (recursiva) → { Navegación: colas → panorámica · Resultados: acción → resultado → transición } → 4 superficies de navegación → roles/zonas componibles.

La fuente canónica del vocabulario vive en el vault de Horus
(`03 Conocimiento/Horus CRM Build Framework.md`).

## Técnico

- Una sola página estática autocontenida (`index.html`), sin build.
- Vanilla JS + CSS. Tipografía Inter (Google Fonts).
- Para servir en local: abrir `index.html` en el navegador, o `python3 -m http.server`.

## Pendiente

- Nombre y poderes del tier **Manager / Supervisor** — por cerrar con Álvaro.
