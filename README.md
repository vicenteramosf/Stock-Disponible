# Stock disponible

Página pública donde los clientes ven el stock de cada producto. Lee el archivo `stock.xlsx` de este repositorio cada vez que alguien la abre.

## Actualizar el stock (cada vez)

1. Entra al repositorio en github.com.
2. Haz clic en **Add file → Upload files**.
3. Arrastra tu Excel. **Debe llamarse exactamente `stock.xlsx`** (reemplaza al anterior).
4. Abajo, haz clic en **Commit changes**.
5. En 1 o 2 minutos la página muestra el stock nuevo.

El Excel necesita las columnas **SKU, Producto, Categoría, Stock** en la primera hoja. Se toleran nombres parecidos ("Cantidad", "Código").

## Ajustes

En `index.html`, arriba del todo, puedes cambiar:

- `COMPANY_NAME`: el nombre que ven tus clientes.
- `LOW_STOCK_THRESHOLD`: desde cuántas unidades se marca "Pocas unidades".
