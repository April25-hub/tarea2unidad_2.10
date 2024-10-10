# tarea2unidad_2.10
Arzaba Diaz April 1173 3W
print(" ")
print("Arzaba Diaz April 3W 1173")
def es_vocal(caracter):
    """
    esta funcion verifica si un caracter es una vocal
    
    args:
    caracter (str): El caracter a verificar

    returns:
    bool: true si el caracter es una vocal, False en caso contrario
    """
    #esta linea convertira caracter a minusculas para facilitar la comparacion
    caracter = caracter.lower()
    #esta linea verificara si el caracter es una vocal
    return caracter in 'aeiou'

#esta lonea dara un ejemplo de uso
resultado = es_vocal('a')
print(resultado)  #salida: true
![image](https://github.com/user-attachments/assets/77d3e301-6547-46db-adcb-adb187b855d3)
