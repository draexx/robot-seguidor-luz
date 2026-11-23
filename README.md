# Robot Seguidor de Luz 🤖💡

Este proyecto consiste en un robot que sigue fuentes de luz utilizando fotorresistencias (LDRs) como sensores. El robot navega automáticamente hacia la fuente de luz más intensa mediante un sistema de control basado en transistores NPN.

## 📝 Tabla de Contenidos
- [Robot Seguidor de Luz 🤖💡](#robot-seguidor-de-luz-)
  - [📝 Tabla de Contenidos](#-tabla-de-contenidos)
  - [📖 Descripción](#-descripción)
    - [Características principales:](#características-principales)
  - [🛠️ Materiales](#️-materiales)
    - [Componentes electrónicos:](#componentes-electrónicos)
    - [Herramientas necesarias:](#herramientas-necesarias)
  - [💻 Instalación](#-instalación)
  - [🚀 Uso](#-uso)
    - [Recomendaciones:](#recomendaciones)
  - [📚 Documentación](#-documentación)
  - [🔬 Simulaciones](#-simulaciones)
  - [🤝 Contribuir](#-contribuir)
  - [📄 Licencia](#-licencia)
  - [📫 Contacto](#-contacto)

## 📖 Descripción

El robot seguidor de luz es un proyecto educativo que demuestra principios básicos de electrónica y robótica. Utiliza fotorresistencias para detectar la intensidad de luz y transistores NPN para controlar los motores, permitiendo que el robot se mueva hacia la fuente de luz más brillante.

### Características principales:
- Control automático basado en intensidad lumínica
- Diseño modular y fácil de replicar
- Componentes accesibles y económicos
- Ideal para aprendizaje de electrónica básica

## 🛠️ Materiales

### Componentes electrónicos:
- 1 LED rojo (633nm) de 5mm
- 1 LED verde (570nm) de 5mm
- 2 motores de engranajes (gear motors)
- 2 transistores NPN TIP41 (TO92)
- 2 transistores NPN BC548 (TO92)
- 4 resistencias de 1kΩ
- 2 resistencias de 220Ω
- 2 resistencias de 10kΩ
- 2 fotorresistencias LDR (300kΩ en oscuridad, 16kΩ a 10 lux)
- 1 batería de 9V

### Herramientas necesarias:
- Protoboard
- Cables jumper
- Soldador (opcional)
- Multímetro
- Destornilladores

## 💻 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/draexx/robot-seguidor-luz.git
cd robot-seguidor-luz
```

2. Abre los archivos de diseño:
- Para Fritzing: Abre `/fritzing/robot-seguidor-luz.fzz`
- Para Proteus: Abre `/proteus/robot-seguidor-luz.pdsprj`

3. Sigue las instrucciones de montaje en la documentación (`/docs/manual-construccion.pdf`)

## 🚀 Uso

1. Asegúrate de que todas las conexiones estén correctamente realizadas
2. Conecta la batería de 9V
3. Coloca el robot en una superficie plana
4. Utiliza una fuente de luz (linterna, lámpara) para guiar al robot

### Recomendaciones:
- Usa el robot en ambientes con iluminación controlada
- Mantén la fuente de luz a una distancia de 20-50 cm
- Verifica la carga de la batería regularmente

## 📚 Documentación

La documentación completa está disponible en la carpeta `/docs`:
- Informe técnico completo (Estructura Sugerida)
- Manual de construcción
- Esquemas de conexión
- Lista detallada de materiales

## 🔬 Simulaciones

- [Simulación en Tinkercad](https://www.tinkercad.com/things/dYh0102oI5U-micro-robot-movil-seguir-de-luz)
- [Video demostrativo en YouTube](https://www.youtube.com/watch?v=fTKlbXQNJEY)

## 🤝 Contribuir

Las contribuciones son bienvenidas. Para contribuir:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📫 Contacto

[Draexx] - [@twitter](https://twitter.com/draexx) - contacto@pedrocarranza.com

Link del proyecto: [https://github.com/draexx/robot-seguidor-luz](https://github.com/draexx/robot-seguidor-luz)

---
⌨️ con ❤️ por [Pedro Carranza]
