# INPUT
cliente = "Gustavo"

productos = [
    ["Pan", 20, 3],
    ["Calzado", 50, 2],
    ["Accesorios", 15, 5],
    ["Chamarras", 100, 1]
]

# CALCULOS
subtotal = 0
for nombre, precio, cantidad in productos:
    subtotal += precio * cantidad

iva = subtotal * 0.16

# DESCUENTOS
if subtotal > 2000:
    descuento = subtotal * 0.20
elif subtotal > 1000:
    descuento = subtotal * 0.15
elif subtotal > 500:
    descuento = subtotal * 0.10
else:
    descuento = 0

total = subtotal + iva - descuento

# OUTPUT
print("----- TICKET -----")
print("Cliente:", cliente)
print("Productos:")

for nombre, precio, cantidad in productos:
    print(nombre, "| Precio:", precio, "| Cantidad:", cantidad)

print("Subtotal:", subtotal)
print("IVA:", iva)
print("Descuento:", descuento)
print("TOTAL:", total)

if total > 4000:
    print("CLIENTE VIP")

print("------------------")
