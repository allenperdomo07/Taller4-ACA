# Configuración avanzada de Inventrack

Estas son las variables que podés modificar en el archivo `config.json`:

| Clave             | Función                                        |
|-------------------|-----------------------------------------------|
| `alerta_stock`    | Notifica cuando un producto baja de cantidad  |
| `idioma`          | Cambia el idioma de la interfaz                |
| `modo_ventas`     | Habilita o desactiva ventas por crédito       |

## Fragmento del archivo de configuración

```json
{
  "alerta_stock": true,
  "idioma": "es",
  "modo_ventas": false
}
