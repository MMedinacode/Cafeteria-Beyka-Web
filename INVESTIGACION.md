# Cafetería Beyka — Conchalí · dossier de investigación verificado

> Verificado **en vivo en Google Maps el 15-09-2026**.
> Estado: **CONSTRUIDA, probada y commiteada.** Falta publicar en Pages.
> **Nada acá está inventado.**

## Ficha Google Maps

| Dato | Valor |
|---|---|
| Nombre | Cafeteria beyka |
| Categoría | Cafetería |
| Dirección | Av. Los Zapadores 1961, 8550756 Conchalí, Región Metropolitana |
| Plus Code | J878+5Q Conchalí |
| Teléfono | **+56 9 4532 6568** (confirmado dos veces: ficha de Maps **y** el pie de su propia carta) |
| Rating | 4,6 ★ |
| Nº reseñas | 124 |
| Rango de precio | $5.000–10.000 por persona (notificado por 53 personas) |
| Servicios | Consumo en el lugar · Para llevar · Entrega a domicilio |
| Sitio web | NO tiene |

```
Place ID  : ChIJQ8B9mrjHYpYR7n0O5ilNmQ8
CID hex   : 0x9662c7b89a7dc043:0xf994d29e60e7dee
Coordenadas: -33.3871097, -70.6830053
```

> ⚠️ Recordar: **sin `loading="lazy"` en el iframe del mapa**, y `height:auto`
> en la regla global de `img`. Ver la entrada del 15-09-2026 en la bitácora.

## Horario — el dato más distintivo del local

Abren **los siete días**, de lunes a viernes sólo de tarde/noche, y el fin
de semana desde temprano. Casi nadie hace eso, y es el gancho del hero.

| Día | Horario |
|---|---|
| Lunes | 17:00 – 21:00 |
| Martes | 17:00 – 21:00 |
| Miércoles | 17:00 – 21:00 |
| Jueves | 17:00 – 21:00 |
| Viernes | **17:00 – 22:00** |
| Sábado | **10:00 – 22:00** (de su bio de Instagram) |
| Domingo | **12:00 – 21:00** (de su bio de Instagram) |

```js
window.HORARIO = {
  dias: ["17:00 - 21:00","17:00 - 21:00","17:00 - 21:00","17:00 - 21:00",
         "17:00 - 22:00","10:00 - 22:00","12:00 - 21:00"],
  fuente: "Bio de @cafeteriabeyka (sáb y dom) + Google Maps, 15-09-2026"
};
```

> Ojo: Maps marcaba viernes y sábado con "El horario podría cambiar" por
> Fiestas Patrias. Es una nota de feriado, no otro horario. **Abren los 7
> días**, cosa que tampoco es común.

## Identidad del local — muy marcada

Beyka es **una cafetería-jardín rosada**, y es de las identidades más
claras que han aparecido en el portafolio. En sus propias fotos:

- Salón con **paredes y sillas rosadas**, **césped verde en el piso**,
  guirnaldas de luces cálidas colgando del techo y **flores por todas
  partes** (rosas, hortensias artificiales).
- **Vitrina llena de tortas y pasteles**, y una estatuilla de querubín.
- Copas de helado enormes, waffles con helado, churros con milkshake,
  milkshakes de oreo, jugos en vasos de vidrio tipo mason jar.
- Su carta impresa es **rosa con tipografía manuscrita** y un corazón.

Su resumen de reseñas en Google: *tortas, variedad de helados, excelente
café, ambiente acogedor y armonioso, ideal para una visita relajante,
personal atento y cordial incluso en horas de mayor afluencia*.

→ Dirección de diseño: rosa de su propio local + verde del césped + crema.
**Ningún otro proyecto del portafolio usa rosa como dominante** — revisar
igual la bitácora antes de fijarlo. La paleta se puede muestrear con Pillow
de `fotos/b01.jpg` o `fotos/b15.jpg`, como se hizo con Café Küpa.

## 📱 Instagram VERIFICADO — y contradice el horario de Google

La pista salió del pie de su carta (`fotos/carta.jpg`): **`Cafeteriabeyka`**
junto a un corazón. **Verificado el 15-09-2026**: el perfil
`instagram.com/cafeteriabeyka` existe, tiene **8.459 seguidores y 162
publicaciones**, y su bio declara **la misma dirección y el mismo teléfono**
que la ficha de Maps. Es de ellos, sin duda.

Su bio, textual:

> "Abierto Domingo de 12hrs a 21hrs sábado 10am a 22pm lunes a jueves de
> 17hrs a 21hrs reservas al +56945326568 Av Los Zapadores 1961, Conchali"

**El horario del fin de semana NO es el que dice Google.** Se aplicó el
criterio del proyecto (gana el material del propio local) y el sitio usa el
de la bio para sábado y domingo. El viernes se mantiene el de Google porque
la bio no lo menciona, y no mencionarlo no es desmentirlo.

## Carta — parcial, y hay que tener cuidado

`fotos/b02.jpg` es su carta impresa. Se lee bien la parte de **bebestibles
sin precio** (lista de opciones) y una tabla de **café en grano con precios**,
pero **la foto está cortada por el borde izquierdo** y los nombres de los
productos de esa tabla quedan a medias.

| Lo que se lee | Precio | ¿Publicable? |
|---|---|---|
| `…ricano` → Americano | $2.000 | sí, el nombre es inequívoco |
| `…e` → ¿Latte? ¿Corte? | $2.500 | **NO — no se puede saber cuál es** |
| `…uchino` → Capuchino | $2.500 | sí, inequívoco |
| `…so` → Expreso | $2.000 | sí; Maps destaca "Expreso Doble Y Capuchino" |

**Criterio a aplicar:** publicar sólo los tres inequívocos, dejar el de
$2.500 fuera, y **pedirle la carta completa al local**. Es exactamente la
regla de "si no se lee el encabezado, el precio no se publica".

### Bebestibles que sí constan (sin precio)

Bebida en lata: Sprite · Sprite zero · Coca-cola · Coca-cola zero · Fanta ·
Kem piña · Bilz · Pap. Aloe vera: original · zero. Agua mineral: con gas ·
sin gas.

### Productos reales vistos en sus fotos y reseñas (sin precio)

tortas y pasteles de vitrina · copas de helado · waffles con helado ·
churros con milkshake · milkshake de oreo · chocolate caliente · jugos
naturales · ensaladas · un plato de carne mechada con papas · tequeños

## Reseñas reales positivas (ordenadas por "Valoración más alta")

Las que Google muestra por defecto son **mixtas**, así que hubo que ordenar.
Copiadas textuales. **No corregir la ortografía.**

1. **Nicolás Rojas** — Local Guide · 24 reseñas
   > Excelente cafetería con una muy buena variedad de preparaciones,
   > destaca mucho en la calidad y abundancia de sus platos como por ejemplo
   > de sus Waffles tanto dulces como salados. Muy buena ambientación y
   > siempre se agradece comer algo rico después del trabajo. Espero que
   > sigan mejorando y que les vaya excelente.

2. **Claudia Flores** — 3 reseñas
   > Un ambiente acogedor, con excelente atención, exquisita variedad de
   > platos dulces y salados. Este sandwich en pan italiano hecho aquí mismo
   > es simplemente delicioso!!! Recomendadísimo.

3. **Isidora Cortés (Tay)** — Local Guide · 18 reseñas
   > Muy buen lugar, linda estética y platos deliciosos con porciones
   > abundantes. Hoy viernes hubo violinista en vivo.

4. **Manuel Parra Zúñiga** — Local Guide · 30 reseñas · hace 5 meses
   > Muy lindo lugar, se nota el cariño que le ponen, la comida muy rica y
   > la atención con amabilidad, un siete.

5. **Lourdes Sabel** — Local Guide · 20 reseñas (va en Nosotros, no en Reseñas)
   > Me encantó el lugar, hacía 1 año que no lo visitaba y si bien se
   > mantiene su esencia estaba renovado, la música ambiental es muy
   > agradable, mi madre estaba de cumpleaños y el dueño la saludo y nos
   > atendieron muy bien, ella estaba feliz

### ⚠️ La reseña negativa que Matías debería conocer

**Katherine Noemi Covarrubias González** (Local Guide, 82 reseñas, 784
fotos) escribió *"Lo pase PÉSIMO"* y reclama que al llegar no la saludaron.
**No va al sitio**, pero es una Local Guide con mucho alcance y sale
segunda por defecto en su ficha. Conviene saberlo antes de escribirles.

**Sin red flags** del tipo "café con piernas".

## Fotos reales → `fotos/` (17 usables, ya renombradas)

Bajadas de su ficha, **revisadas una por una** en hoja de contacto y luego
comprimidas a 1600px / calidad 80.

| Archivo | Qué es |
|---|---|
| `salon-jardin.jpg` | **El salón rosado con luces y flores** — es el hero |
| `salon-amplio.jpg` | Vista amplia del salón |
| `vitrina-flores.jpg` | Pasteles entre flores |
| `carta.jpg` | Su carta impresa (rosa) |
| `vitrina-tortas.jpg`, `pasteles.jpg` | Vitrina de tortas y pasteles |
| `chocolate.jpg` | Chocolate caliente |
| `postre-frutos.jpg` | Postre con crema y frutos rojos |
| `limonada.jpg` | Limonada en copa alta |
| `churros-milkshake.jpg` | Churros con milkshake |
| `waffle-jugos.jpg`, `waffle-ensalada.jpg`, `waffle-frutas.jpg` | Waffles |
| `milkshake-oreo.jpg` | Milkshake de oreo |
| `bandeja.jpg` | Bandeja de bocados |
| `copa-helado.jpg` | Copa de helado grande |
| `mechada.jpg` | Carne mechada con papas |

**Las 17 están en uso en el sitio** (auditado con el chequeo de fotos sin
enlazar de la bitácora).

### 🚨 Se volvieron a colar fotos de otros negocios

De 19 bajadas **se borraron 2**:

- Una era la fachada de **“MENTA NEGRA”** — que aparece en el carrusel
  *"Otras personas también buscan"* de esta misma ficha.
- La otra era un comedor con un letrero de **“PARRILLADA”** y mucha gente
  sentada: ni la estética ni el rubro corresponden a Beyka.

Es el **tercer** caso del día (también pasó en Café Küpa). El extractor por
`background-image` no aplica el corte de "También se buscó". **Arreglarlo.**

## Lo que falta

- [x] 2–3 reseñas positivas con nombre — hechas: Nicolás Rojas, Claudia Flores, Isidora Cortés, Manuel Parra
- [x] Verificar `instagram.com/cafeteriabeyka` — confirmado, 8.459 seguidores
- [x] Renombrar las fotos — hecho
- [x] Paleta definida: rosa `#E0637F` + `#F6AFC0` + verde `#6B8E5A`
- [ ] Confirmar si el teléfono tiene WhatsApp (`wa.me/c/56945326568`)
- [ ] Pedir la carta completa con precios
