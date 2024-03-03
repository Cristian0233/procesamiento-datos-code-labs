import numpy as np
from typing import Tuple

def ej_1_get_array() -> np.ndarray:
    temperaturas = np.array([25, 30, 27, 22, 29, 31, 26, 28])
    return temperaturas

def ej_2_media_std(array: np.ndarray) -> Tuple[float, float]:
    media = np.mean(array)
    desviacion = np.std(array)
    return media, desviacion

def ej_3_temperaturas(array: np.ndarray) -> np.ndarray:
    temperaturas_fahrenheit = array * 9/5 + 32
    return temperaturas_fahrenheit

def ej_4_min_max(temperaturas_fahrenheit: np.ndarray) -> Tuple[float, float]:
    temp_min = np.min(temperaturas_fahrenheit)
    temp_max = np.max(temperaturas_fahrenheit)
    return temp_min, temp_max

def ej_5_diferencias(temperaturas: np.ndarray, media: float) -> np.ndarray:
    diferencias = temperaturas - media
    return diferencias

def ej_6_cuadrado(diferencias: np.ndarray) -> np.ndarray:
    diferencias_cuadrado = np.square(diferencias)
    return diferencias_cuadrado

def ej_7_suma(diferencias_cuadrado: np.ndarray) -> float:
    suma_cuadrados = np.sum(diferencias_cuadrado)
    return suma_cuadrados

def ej_8_raiz(suma_cuadrados: float) -> float:
    raiz_suma_cuadrados = np.sqrt(suma_cuadrados)
    return raiz_suma_cuadrados
