# Calculadora con Interfaz Gráfica en Python (Tkinter)

![Interfaz de la calculadora](/calculadora.png)

Este proyecto es una calculadora básica construida con **Python** y **Tkinter**, la librería estándar para interfaces gráficas en Python. Incluye operaciones aritméticas fundamentales y una interfaz amigable para el usuario.

## 🎯 Funcionalidades

- Operaciones básicas: suma, resta, multiplicación, división
- Operadores adicionales: módulo, punto decimal
- Evaluación automática de expresiones
- Botón de limpiar (`C`)
- Interfaz adaptada a teclado y ratón
- Validación de errores (evita cierres por operaciones inválidas)

## ⚙️ Requisitos

- Python 3.x
- Sistema operativo con soporte para interfaces gráficas (Windows, macOS o Linux con entorno gráfico)
- Archivo `calculadora.ico` en el mismo directorio para el ícono (opcional)

## 🛠️ Instalación y ejecución

1. Clona el repositorio:

```bash
git clone https://github.com/niespihu12/calculadora.git
cd calculadora
```

2. Ejecuta el programa:

```bash
python calculadora.py
```

## 📂 Estructura del proyecto

```
calculadora/
├── calculadora.py     # Script principal con interfaz gráfica Tkinter
├── calculadora.ico    # Ícono del programa (opcional)
├── README.md          # Documentación
└── img/
    └── screenshot.png # Imagen de la calculadora (añádela manualmente)
```

## 🧠 Detalles técnicos

- Se utiliza la clase `Calculadora` que hereda de `tk.Tk`.
- Uso de `StringVar` para enlazar la entrada con los botones.
- La evaluación se realiza con `eval()` (con manejo de errores controlado).
- Los botones están diseñados con colores personalizados para mejorar la usabilidad.

## 🚀 Mejoras futuras

- Agregar historial de operaciones
- Soporte para teclas del teclado
- Operaciones científicas (trigonometría, logaritmos, etc.)
- Internacionalización (i18n)

## 📄 Licencia

MIT License. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

**Nicolás Esteban Pinzón Huaza**  
[LinkedIn](https://www.linkedin.com/in/nicolasestebanpinzon)

---

¡Si te fue útil este proyecto, no olvides dejar una ⭐ en GitHub!
