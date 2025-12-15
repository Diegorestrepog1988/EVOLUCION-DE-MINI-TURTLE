# EVOLUCION-DE-MINI-TURTLE
En este repositorio se aplican los conceptos de modularidad, empaquetado y programación orientada a objetos (POO)

reto1

import turtle
turtle.forward(100)
turtle.done()

#reto1
#simula el movimiento de la tortuga

print("simulación de la tortuga")

#posición inicial
posición=0
print("posición inicial de la tortuga:", posición)

#movimiento hacia adelante
input("Presiona Enter para mover la tortuga hacia adelante 50 unidades...")

#dibujar el rastro del movimiento con '-' y flecha al final
pasos= 50
print("-" * (pasos-1) + ">")
posición += pasos


#posición después del movimiento
print("la tortuga avanzó", pasos, "unidades.")
print("posición actual de la tortuga:", posición)
