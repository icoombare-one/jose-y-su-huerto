# Explicación del Huerto de José 🌱

José tiene un terreno grande con forma de rectángulo, y lo dividió en **4 pedazos** para sembrar verduras diferentes.


![Terreno](terreno4.png)

Así se ve el terreno:

```
         |<-- 3 -->|<----  (2x - 3)  ---->|
         ┌─────────┬──────────────────────┐  ─┬─
         │         │                      │   │
         │ BROCOLI │      JITOMATE        │   x  (alto de arriba)
         │         │                      │   │
         ├─────────┼──────────────────────┤  ─┼─
         │ CEBOLLA │       ACELGA         │   2  (alto de abajo)
         └─────────┴──────────────────────┘  ─┴─
         |<───────────── 2x ─────────────>|
                    (ancho total)
```

Antes de empezar, recuerda dos cosas:

1. El terreno completo mide **$2x$** de ancho (de izquierda a derecha)
2. El terreno completo mide **$x + 2$** de alto (de arriba a abajo)

José lo cortó con **dos líneas**:
- Una línea **vertical** que deja **3** a la izquierda
- Una línea **horizontal** que deja **2** abajo

¡Ahora vamos pedazo por pedazo!

---

## 🥬 1. La Acelga (abajo a la derecha)

La acelga está aquí:

```
         ┌─────────┬──────────────────────┐
         │         │                      │
         │         │                      │
         ├─────────┼──────────────────────┤
         │         │                      │  ↑
         │         │      ACELGA          │  2
         └─────────┴──────────────────────┘  ↓
                   |<----  (2x - 3)  ---->|
```

### Paso 1: ¿Cuánto mide de alto?

Mira el lado izquierdo del dibujo. José cortó una línea horizontal. La parte de **abajo** mide **2**.

La acelga está abajo, entonces su alto es **2**. ¡Fácil!

```
         ┌────────────────────────┐  ─┬─
         │   parte de arriba      │   x
         ├────────────────────────┤  ─┼─  ← aquí cortó
         │   parte de abajo       │   2
         └────────────────────────┘  ─┴─
```

### Paso 2: ¿Cuánto mide de ancho?

El terreno completo mide **$2x$** de ancho.

José cortó una línea vertical y el pedazo de la izquierda mide **3**.

Piensa así: si tienes una cuerda que mide $2x$ y le cortas un pedazo de $3$, ¿cuánto te queda?

$$2x - 3$$

La acelga está a la **derecha**, entonces su ancho es $2x - 3$.

```
         |<- 3 -->|<--- (2x - 3) ---->|
         ┌────────┬──────────────────┐
         │   ya   │   lo que sobra   │
         │ usamos │     = 2x - 3     │
         └────────┴──────────────────┘
         |<─────────── 2x ──────────>|
```

### Paso 3: Juntamos los dos lados

La acelga es un rectángulo con:
- **Alto** = $2$
- **Ancho** = $2x - 3$

El área de un rectángulo es **ancho × alto**, entonces:

$$\text{Área de la acelga} = (2x - 3)(2) = 4x - 6$$

---

## 🧅 2. La Cebolla (abajo a la izquierda)

La cebolla está aquí:

```
         ┌─────────┬──────────────────────┐
         │         │                      │
         │         │                      │
         ├─────────┼──────────────────────┤
         │         │                      │  ↑
         │ CEBOLLA │                      │  2
         └─────────┴──────────────────────┘  ↓
         |<-- 3 -->|
```

### Paso 1: ¿Cuánto mide de alto?

La cebolla también está en la parte de **abajo** del terreno.

La parte de abajo mide **2**, entonces el alto de la cebolla es **2**.

### Paso 2: ¿Cuánto mide de ancho?

La cebolla está a la **izquierda**. El pedazo de la izquierda mide **3**.

Entonces su ancho es **3**.

### Paso 3: Juntamos los dos lados

La cebolla es un rectángulo con:
- **Alto** = $2$
- **Ancho** = $3$

$$\text{Área de la cebolla} = (3)(2) = 6$$

¡Este es el más fácil porque no tiene letras, solo números! 🎉

---

## 🥦 3. El Brócoli (arriba a la izquierda)

El brócoli está aquí:

```
         |<-- 3 -->|
         ┌─────────┬──────────────────────┐  ─┬─
         │         │                      │   │
         │ BROCOLI │                      │   x
         │         │                      │   │
         ├─────────┼──────────────────────┤  ─┴─
         │         │                      │
         └─────────┴──────────────────────┘
```

### Paso 1: ¿Cuánto mide de alto?

El brócoli está en la parte de **arriba** del terreno.

El terreno completo mide $x + 2$ de alto. La parte de abajo mide $2$.

¿Cuánto queda para arriba?

$$(x + 2) - 2 = x$$

¡El alto de arriba es **$x$**!

### Paso 2: ¿Cuánto mide de ancho?

El brócoli está a la **izquierda**. El pedazo de la izquierda mide **3**.

Entonces su ancho es **3**.

### Paso 3: Juntamos los dos lados

El brócoli es un rectángulo con:
- **Alto** = $x$
- **Ancho** = $3$

$$\text{Área del brócoli} = (3)(x) = 3x$$

---

## 🍅 4. El Jitomate (arriba a la derecha)

El jitomate está aquí:

```
                   |<----  (2x - 3)  ---->|
         ┌─────────┬──────────────────────┐  ─┬─
         │         │                      │   │
         │         │      JITOMATE        │   x
         │         │                      │   │
         ├─────────┼──────────────────────┤  ─┴─
         │         │                      │
         └─────────┴──────────────────────┘
```

### Paso 1: ¿Cuánto mide de alto?

El jitomate está en la parte de **arriba**. Como vimos con el brócoli, la parte de arriba mide **$x$**.

### Paso 2: ¿Cuánto mide de ancho?

El jitomate está a la **derecha**. Como vimos con la acelga, el ancho de la derecha es lo que sobra cuando le quitas 3 al total:

$$2x - 3$$

### Paso 3: Juntamos los dos lados

El jitomate es un rectángulo con:
- **Alto** = $x$
- **Ancho** = $2x - 3$

$$\text{Área del jitomate} = (2x - 3)(x) = 2x^2 - 3x$$

¡Este es el más grande de todos! 🍅

---

## 📋 Resumen de todo

| Producto | ¿Dónde está? | Ancho | Alto | Área |
|----------|--------------|-------|------|------|
| 🥬 Acelga | Abajo-derecha | $2x - 3$ | $2$ | $(2x-3)(2) = 4x - 6$ |
| 🧅 Cebolla | Abajo-izquierda | $3$ | $2$ | $(3)(2) = 6$ |
| 🥦 Brócoli | Arriba-izquierda | $3$ | $x$ | $(3)(x) = 3x$ |
| 🍅 Jitomate | Arriba-derecha | $2x - 3$ | $x$ | $(2x-3)(x) = 2x^2 - 3x$ |

### ¿Y si sumamos todas las áreas?

$$6 + (4x - 6) + 3x + (2x^2 - 3x) = 2x^2 + 4x$$

¡Y eso es igual al área del terreno completo!

$$\text{Área total} = 2x \times (x + 2) = 2x^2 + 4x \quad ✅$$

¡Todo cuadra! 🎉
