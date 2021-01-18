# Productos de Supermercados

Productos con su precio y descripción en los principales supermercados de España. Este dataset se puede adquirir en [Data Market](https://datamarket.es/#productos-de-supermercados-dataset), plataforma de referencia de datos externos en España. Puede consultar nuestro catálogo de datos en la siguiente url: [datamarket.es](https://datamarket.es/)

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre          | tipo     | descripción                                                                                                      | ejemplo                             |
|-----------------|----------|------------------------------------------------------------------------------------------------------------------|-------------------------------------|
| supermarket     | str      | Supermercado al que pertenece el producto (encriptado). Este campo será visible tras la subscripción al dataset. | 433463D95980C252B92C204E3655BB81    |
| category        | str      | Categoría del producto.                                                                                          | marisco_y_pescado_pescado_congelado |
| name            | str      | Nombre del producto.                                                                                             | Anguriñas de surimi Pescanova       |
| description     | str      | Información adicional del producto (formato de empaquetado, etc.).                                               | Pack-2                              |
| price           | float    | Precio absoluto del producto. En caso de existir algún tipo de descuento aparecerá el menor precio disponible.   | 1.99                                |
| reference_price | float    | Precio unitario (por unidad de medida del producto, €/Kg, €/L, etc.).                                            | 7.96                                |
| reference_unit  | str      | Unidad de referencia del producto (Kg, L, etc.).                                                                 | kg                                  |
| insert_date     | datetime | Fecha de extracción de la información.                                                                           | 2020-09-23 14:15:00                 |
