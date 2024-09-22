# Aylin
TAREA ACT 1
#Función para combertir pesos a dolares
def
convertir_pesos_a_dolares(precio_pesos, tipo_cambio):
    precio_dolares = precio_pesos / tipo_cambio
    return precio_dolares
precio_pesos = 60(input("Ingresa el precio del producto en pesos: "))
tipo_cambio =60(input("Ingresa el tipo de cambio (pesos por dólar): "))

precio_en_dolares = convertir_pesos_a_dolares(precio_pesos, tipo_cambio)
print(f"El precio del producto en dólares es: {precio_en_dolares:.2f}")
