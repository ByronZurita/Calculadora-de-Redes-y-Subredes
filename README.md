# Calculadora de Redes y Subredes CLI (.NET)

![.NET 8](https://img.shields.io/badge/.NET-8.0-blue)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![Tipo](https://img.shields.io/badge/CLI-Console%20App-lightgrey)


Aplicación de consola en .NET para calcular redes IPv4, ya sea usando CIDR o por cantidad de hosts. Incluye soporte para VLSM y muestra todos los datos importantes de cada subred.

---

## Funcionalidades

* Calcular datos de red ingresando una IP con CIDR (ej: `192.168.1.0/24`)
* Calcular subredes indicando la IP base y los hosts necesarios
* VLSM con varios tamaños de subredes
* Muestra IP de red, rango útil, broadcast y máscara
* Permite guardar los resultados de subredes en un archivo `.txt`

---

## Cómo usar

1. Descarga la última **Release** desde la sección de _Releases_ en GitHub.
2. Extrae el `.zip` en una carpeta de tu preferencia.
3. Ejecuta el archivo `.exe` para iniciar la aplicación.
4. Elige una opción en el menú principal:

   * **Calcular Red** → Ingresa una IP con CIDR (ej: `192.168.1.0/24`)
   * **Calcular Subredes** → Ingresa IP base + cantidad de hosts

5. Revisa los resultados directamente en la consola.
6. Si calculaste subredes, puedes **guardar los resultados** en un archivo `.txt`.

---

##  Tecnologías usadas

* .NET 8
* C#
* ChatGPT
* Github Copilot

---

##  Créditos

Proyecto se inspiro en la lógica de cálculo de:

* [https://vlsmcalc.vercel.app](https://vlsmcalc.vercel.app)
* [https://github.com/michqo/vlsmcalc](https://github.com/michqo/vlsmcalc)

---

## Capturas

| Menú Cálculo de Red                        | Menú Cálculo de Subredes                        |
|---------------------------------------------|-------------------------------------------------|
| ![](Screenshots/Calcular%20Red%20Menu.png)  | ![](Screenshots/Calcular%20Subredes%20Menu.png) |

| Resultados por CIDR                                     | Subredes – Parte 1                                        |
|---------------------------------------------------------|-----------------------------------------------------------|
| ![](Screenshots/Calcular%20Red%20CIDR%20Resultados.png) | ![](Screenshots/Calcular%20Subredes%20Resultados%201.png) |

| Resultados por Hosts                                     | Subredes – Parte 2                                        |
|----------------------------------------------------------|-----------------------------------------------------------|
| ![](Screenshots/Calcular%20Red%20Hosts%20Resultados.png) | ![](Screenshots/Calcular%20Subredes%20Resultados%202.png) |
