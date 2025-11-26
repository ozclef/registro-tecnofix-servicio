# registro-tecnofix-servicio
formulario de servicio de reparacion BIO-US/TECHNOIFX  por oscar..... completo v1 



formulario completo a la izquierda, vista previa del ticket a la derecha (en desktop) y debajo en mobile; folio automático, catálogo de marcas/modelos básico, selección de servicios con precios, cálculo de subtotal/anticipo/total, generación de PDF tanto de estimado como de recibo final, y opción de QR.

Qué incluye exactamente y cómo usarlo ya:

Folio automático (8 dígitos) que puedes regenerar si quieres.

Campo para cliente, contacto, tipo, marca, modelo (modelos se rellenan según marca).

Selector de servicios (reconexión flex, limpieza, cambio display, batería, diagnóstico) que suma precios automáticamente.

Estimado automático (subtotal) y campo de anticipo editable.

Vista previa del ticket que se actualiza en tiempo real al escribir.

Botón Generar Estimado (PDF) — crea un PDF que dice “ESTIMADO PREVIO”.

Botón Descargar Recibo (PDF) — genera el recibo final con folio igual al estimado.

Opción QR (usa Google Charts si estás online) que codifica folio/total/servicios.

Diseño responsive: en desktop verás form + ticket; en móvil el ticket queda abajo.

Cómo verlo en tu compu / teléfono:

Guarda el contenido del canvas como index.html (ya está listo para copiar desde el canvas).

Abre con doble clic en tu navegador (no necesitas servidor).

Rellena los campos y verás el ticket a la derecha actualizarse al instante.

Usa “Generar Estimado (PDF)” para entregar un documento antes de empezar.

Cuando termines, marca los servicios reales y descarga el recibo con el mismo folio.

Si querés, lo siguiente que puedo hacer ahora (elige lo que querés que haga ya):

Pegar dentro del repo un README.md listo con instrucciones y estructura (te lo genero ahora).

Añadir más modelos en el catálogo (pásame marcas/modelos comunes que quieras).

Incluir validaciones (teléfono, email), firma digital simple o campo de firma para imprimir.

Conectar esto a Supabase más adelante (registro de usuarios, guardar tickets y generar historial).

Adaptarlo a ticket 80mm para impresora térmica y añadir plantilla para impresión térmica.
