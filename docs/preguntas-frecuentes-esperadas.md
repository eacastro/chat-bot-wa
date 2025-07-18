# 📋 Preguntas Frecuentes Esperadas (FAQ) - Bot de Atención al Cliente

Este documento describe las preguntas frecuentes que el bot debe ser capaz de entender y responder adecuadamente. Las preguntas están agrupadas por temática y asociadas a una posible intención (`intent`) para el modelo NLP.

---

## 👕 1. Tallas

**Intent:** `consultar_talla_disponible`

**Ejemplos de preguntas:**
- ¿Tienen talla S?
- ¿Hay en talla M?
- ¿Qué tallas manejan?
- ¿Tienen tallas grandes?
- ¿Tienen talla para niños?

**Notas:**
- El bot debe identificar la prenda y la talla solicitada.
- Puede sugerir tallas similares si la solicitada no está disponible.

---

## 💵 2. Precios

**Intent:** `consultar_precio`

**Ejemplos de preguntas:**
- ¿Cuánto cuesta esta blusa?
- ¿Cuál es el precio del jean negro?
- ¿Cuánto vale la chaqueta?
- ¿Tienen algo en descuento?
- ¿Hay promociones esta semana?

**Notas:**
- El bot debe identificar la prenda mencionada.
- Puede sugerir combos o productos en oferta si el usuario muestra interés.

---

## 📦 3. Disponibilidad

**Intent:** `consultar_disponibilidad`

**Ejemplos de preguntas:**
- ¿Está disponible esta camisa?
- ¿Tienen esta referencia en stock?
- ¿Hay disponibilidad en color negro?
- ¿Tienen este producto en la tienda?
- ¿Cuándo reponen esta prenda?

**Notas:**
- Puede conectarse a un sistema de inventario si está disponible.
- De lo contrario, responder con base en información configurada manualmente.

---

## 🚚 4. Envíos

**Intent:** `consultar_envio`

**Ejemplos de preguntas:**
- ¿Cuánto cuesta el envío?
- ¿A qué ciudades hacen envíos?
- ¿Cuánto tarda en llegar?
- ¿Envían a domicilio?
- ¿Puedo recoger en tienda?

---

## 🛒 5. Pedidos y compras

**Intent:** `realizar_pedido`

**Ejemplos de preguntas:**
- ¿Cómo puedo hacer un pedido?
- Quiero comprar esta prenda
- ¿Puedo pagar contra entrega?
- ¿Tienen tienda online?
- ¿Aceptan pagos por Nequi/Daviplata?

---

## 📏 6. Cambios y devoluciones

**Intent:** `consultar_cambios_devoluciones`

**Ejemplos de preguntas:**
- ¿Puedo cambiar una prenda?
- ¿Tienen garantía?
- ¿Qué pasa si no me queda?
- ¿Cómo devuelvo un producto?

---

## 📞 7. Atención humana

**Intent:** `contactar_humano`

**Ejemplos de preguntas:**
- ¿Me puedes comunicar con alguien?
- Quiero hablar con un asesor
- ¿Puedo hablar con alguien?
- Esto no me ayuda, ¿me conectas con una persona?

**Notas:**
- El bot debe redirigir al equipo de atención si detecta frustración o solicitud directa.

---

## 🔚 Notas finales

- Este listado no es exhaustivo. Se debe actualizar con base en las interacciones reales.
- Cada grupo puede vincularse con una respuesta predefinida o lógica dinámica (por ejemplo, integración con catálogo o CRM).
            