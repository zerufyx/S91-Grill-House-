# S91 House Grill — menú digital

Menú digital del food truck S91 House Grill. **Cliente**. **En línea: https://s91housegrill.com**

| Archivo | Qué es |
|---|---|
| `index.html` | El menú que ve el cliente (QR o link), con fotos, precios y pedido por WhatsApp |
| `admin.html` | Panel para cambiar platos, precios, fotos, agotados y orden del menú |
| `CNAME` | Dominio s91housegrill.com |

**Supabase:** sistema de Menús, `store_id = 4` (tablas `tiendas`, `categorias`, `platos`, `ajustes`, `tienda_admins`). Fotos en el bucket `menu`. Solo se usa la llave pública.

Si la base de datos no responde, el menú sigue funcionando con los platos que vienen dentro de `index.html`.

---
Hecho por **Zerufy Studio** · zerufystudio.com · El mapa de todos los repos está en el README de `Zerufy-Studio-`.
