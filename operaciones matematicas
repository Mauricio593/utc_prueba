import math

class OperacionesMatematicas:
    # Constructor de la clase
    def __init__(self, numero1, numero2=0):
        self.numero1 = numero1
        self.numero2 = numero2

    # Método para sumar
    def sumar(self):
        return self.numero1 + self.numero2

    # Método para restar
    def restar(self):
        return self.numero1 - self.numero2

    # Método para multiplicar
    def multiplicar(self):
        return self.numero1 * self.numero2

    # Método para dividir
    def dividir(self):
        if self.numero2 != 0:
            return self.numero1 / self.numero2
        else:
            return "Error: División por cero"

    # Método para calcular la raíz cuadrada
    def raiz_cuadrada(self):
        return math.sqrt(self.numero1)

# Ejemplo de uso de la clase
numero1 = float(input("Ingrese el primer número: "))
numero2 = float(input("Ingrese el segundo número (o 0 si no es necesario): "))

# Crear una instancia de la clase
operacion = OperacionesMatematicas(numero1, numero2)

# Realizar las operaciones
print(f"Suma: {operacion.sumar()}")
print(f"Resta: {operacion.restar()}")
print(f"Multiplicación: {operacion.multiplicar()}")
print(f"División: {operacion.dividir()}")
print(f"Raíz cuadrada del primer número: {operacion.raiz_cuadrada()}")
