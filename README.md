```cpp
#include <iostream>

using namespace std;

int main() {
    // Declarar variables
    double centimetros, metros, yardas, varas, pulgadas, pies;
    char opcion;

    // Solicitar al usuario la cantidad en centímetros
    cout << "Ingrese la longitud en centimetros: ";
    cin >> centimetros;

    // Menú de opciones
    cout << "Elija la unidad a la que desea convertir (m/metros, y/yardas, v/varas, p/pulgadas, f/pies): ";
    cin >> opcion;

    // Realizar la conversión basada en la opción elegida
    switch (opcion) {
        case 'm':
            metros = centimetros / 100.0;
            cout << "La longitud en metros es: " << metros << " metros." << endl;
            break;
        case 'y':
            yardas = centimetros / 91.44;
            cout << "La longitud en yardas es: " << yardas << " yardas." << endl;
            break;
        case 'v':
            varas = centimetros / 50.8;
            cout << "La longitud en varas es: " << varas << " varas." << endl;
            break;
        case 'p':
            pulgadas = centimetros / 2.54;
            cout << "La longitud en pulgadas es: " << pulgadas << " pulgadas." << endl;
            break;
        case 'f':
            pies = centimetros / 30.48;
            cout << "La longitud en pies es: " << pies << " pies." << endl;
            break;
        default:
            cout << "Opción no válida. Por favor, seleccione una unidad válida." << endl;
    }

    return 0;
}

---------------------------------------------------------------------------------------------------------------
```python
# Solicitar al usuario la cantidad en centímetros
centimetros = float(input("Ingrese la longitud en centimetros: "))

# Menú de opciones
print("Elija la unidad a la que desea convertir (m/metros, y/yardas, v/varas, p/pulgadas, f/pies): ")
opcion = input()

# Realizar la conversión basada en la opción elegida
if opcion == 'm':
    metros = centimetros / 100.0
    print(f"La longitud en metros es: {metros} metros.")
elif opcion == 'y':
    yardas = centimetros / 91.44
    print(f"La longitud en yardas es: {yardas} yardas.")
elif opcion == 'v':
    varas = centimetros / 50.8
    print(f"La longitud en varas es: {varas} varas.")
elif opcion == 'p':
    pulgadas = centimetros / 2.54
    print(f"La longitud en pulgadas es: {pulgadas} pulgadas.")
elif opcion == 'f':
    pies = centimetros / 30.48
    print(f"La longitud en pies es: {pies} pies.")
else:
    print("Opción no válida. Por favor, seleccione una unidad válida.")
---------------------------------------------------------------------------------------------------------------


Inicio
    // Declarar variables
    Real centimetros, metros, yardas, varas, pulgadas, pies
    Caracter opcion

    // Solicitar al usuario la cantidad en centímetros
    Escribir "Ingrese la longitud en centímetros: "
    Leer centimetros

    // Menú de opciones
    Escribir "Elija la unidad a la que desea convertir (m/metros, y/yardas, v/varas, p/pulgadas, f/pies): "
    Leer opcion

    // Realizar la conversión basada en la opción elegida
    Según opcion Hacer
        Caso 'm':
            metros <- centimetros / 100.0
            Escribir "La longitud en metros es: ", metros, " metros."
        Caso 'y':
            yardas <- centimetros / 91.44
            Escribir "La longitud en yardas es: ", yardas, " yardas."
        Caso 'v':
            varas <- centimetros / 50.8
            Escribir "La longitud en varas es: ", varas, " varas."
        Caso 'p':
            pulgadas <- centimetros / 2.54
            Escribir "La longitud en pulgadas es: ", pulgadas, " pulgadas."
        Caso 'f':
            pies <- centimetros / 30.48
            Escribir "La longitud en pies es: ", pies, " pies."
        De Otro Modo:
            Escribir "Opción no válida. Por favor, seleccione una unidad válida."
    Fin Según

Fin
