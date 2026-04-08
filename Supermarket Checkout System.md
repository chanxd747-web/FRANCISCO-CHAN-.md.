🛒 Sistema de Chequeo de Supermercado (Python)
 Descripción

Este proyecto simula un sistema básico de cobro de supermercado desarrollado en Python. Permite ingresar datos de un cliente, calcular el subtotal de compra, aplicar impuestos (IVA), descuentos para clientes frecuentes y mostrar el total final.


 Funcionalidades
Entrada de datos de cliente y producto
Cálculo automático de subtotal
Aplicación de IVA (16%)
Descuento del 10% para clientes frecuentes
Identificación de clientes frecuentes por cantidad de productos
Cálculo del total final
Salida detallada en consola
 
 
 Lógica del sistema
Si el cliente es "Lucas" y el subtotal es mayor a 500 → se aplica 10% de descuento
Si la cantidad de productos es mayor a 5 → se considera cliente frecuente
Se calcula:
Subtotal = precio × cantidad
IVA = 16% del subtotal
Total = subtotal + IVA - descuento
🛠️ Tecnologías
Python 3
Ejecución en consola

 
 Instalación y ejecución
Clona el repositorio:
git clone https://github.com/tu-usuario/tu-repo.git
Entra a la carpeta:
cd tu-repo
Ejecuta el programa:
python main.py
Ejemplo de uso

Entrada:

Lucas
Juguetes

Salida:

cliente frecuente

cliente Lucas

producto Juguetes

precio 100

cantidad 67

subtotal 6700

iva 1072.0

descuento 670.0

total 7102.0

 
 Estructura del proyecto
/main.py
/README.md
 
 Limitaciones
Los valores de precio y cantidad están fijos en el código
No hay validación de entradas
No maneja múltiples productos
No tiene interfaz gráfica
 
  
  
  Mejoras futuras
Permitir múltiples productos
Entrada dinámica de precios
Interfaz gráfica (Tkinter o web)
Generación de ticket en archivo
Base de datos de clientes
 
 Autor

 Chan
