# Codigo-de-longitud-de-la-circunferencia
nclude <iostream>
using namespace std;

int main() {
    float radio, longitud;
    const float pi = 3.1416; // Definimos el valor de pi como constante
    
    // Solicitamos el radio al usuario
    cout << "Ingrese el radio de la circunferencia: ";
    cin >> radio;
    
    // Calculamos la longitud de la circunferencia
    longitud = 2 * pi * radio;
    
    // Mostramos el resultado al usuario
    cout << "La longitud de la circunferencia es: " << longitud << endl;
    
    return 0;
}
