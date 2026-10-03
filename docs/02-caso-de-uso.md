# Caso de uso · Reposición de compras

Isla Eea Distribución es una empresa ficticia. Compras necesita una propuesta para los próximos siete días que considere existencias, entradas confirmadas, demanda, stock objetivo y lotes de pedido.

Circe consulta una política y usa un script Python incluido en una skill para calcular la propuesta. Las filas con datos obligatorios ausentes quedan como incidencias; no se completan por intuición.

El inventario, las políticas y los paquetes vigentes están en [demo/ del repositorio operativo](https://github.com/javiarmesto/circe-compras-copilot-studio/tree/main/demo).

Con esos datos, el total es 2216 EUR. El cambio de política de 500 a 1000 EUR modifica la revisión especial de B200 sin cambiar cantidades ni total. Toda propuesta requiere decisión humana. El agente no crea pedidos ni accede a Business Central.
