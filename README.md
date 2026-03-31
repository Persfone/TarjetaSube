[![codecov](https://codecov.io/gh/Persfone/TrabajoTarjetaDanaCejas/graph/badge.svg?token=BQQHG2VQLD)](https://codecov.io/gh/Persfone/TrabajoTarjetaDanaCejas)

# 🚍 Tarjeta SUBE Simulation System

Sistema de simulación del transporte urbano de pasajeros de Rosario basado en el funcionamiento de la tarjeta SUBE.

El proyecto modela el comportamiento real del sistema de transporte mediante **Programación Orientada a Objetos, testing automatizado y cobertura de código**, incluyendo franquicias, transbordos, saldo negativo, bicicletas públicas y lógica de tarifas.

---

# 🧠 Descripción

Este proyecto implementa un sistema completo de pago de transporte público que simula el funcionamiento de la tarjeta SUBE.

El sistema permite:

* pagar viajes en colectivo
* aplicar franquicias
* gestionar saldo
* manejar transbordos
* controlar horarios
* aplicar descuentos por uso frecuente
* integrar el sistema de bicicletas públicas
* validar el comportamiento mediante tests automatizados

El objetivo es demostrar **modelado de dominio, arquitectura orientada a objetos, testing y buenas prácticas de desarrollo**.

---

# 🏗️ Arquitectura del Sistema

El sistema está basado en **Programación Orientada a Objetos** y modela entidades reales del transporte público.

### Entidades principales

* Tarjeta
* Colectivo
* Boleto
* MedioBoleto
* FranquiciaCompleta
* BoletoEducativo
* LineaInterurbana
* EstacionBicicletas
* Sistema de Transbordo

Cada entidad representa una parte del sistema real.

---

# 🚀 Funcionalidades

## 💳 Sistema de Tarjetas

* Carga de saldo
* Saldo máximo
* Saldo negativo permitido
* Acreditación automática
* Control de saldo pendiente

---

## 🎟️ Pago de Boletos

* Pago con tarjeta
* Generación de boleto
* Registro de fecha
* Línea de colectivo
* Saldo restante
* Tipo de tarjeta
* Total abonado

---

## 🎓 Franquicias

### Medio Boleto

* 50% de descuento
* máximo 2 viajes por día
* mínimo 5 minutos entre viajes
* tercer viaje tarifa normal

### Franquicia Completa

* viajes gratuitos
* límite de viajes diarios
* control de horario

### Boleto Educativo

* 2 viajes gratis por día
* luego tarifa normal

---

# ⏰ Control de Horarios

Las franquicias funcionan:

Lunes a viernes
6:00 a 22:00

Fuera de ese horario no se pueden usar.

---

# 🔁 Transbordos

* viajes gratis entre líneas distintas
* dentro de 1 hora
* lunes a sábado
* 7:00 a 22:00
* todas las tarjetas pueden usarlo

---

# 📊 Boleto de Uso Frecuente

Sistema automático de descuentos:

| Viajes  | Descuento |
| ------- | --------- |
| 1 a 29  | normal    |
| 30 a 59 | 20%       |
| 60 a 80 | 25%       |
| 81+     | normal    |

---

# 🚲 Mi Bici Tu Bici

Sistema de bicicletas públicas integrado.

### Funcionalidades

* pago con tarjeta SUBE
* tarifa diaria
* retiro de bicicleta
* control de tiempo
* multas por demora
* acumulación de multas

---

# 🧪 Testing

El proyecto incluye:

* tests unitarios
* tests de integración
* cobertura de código
* validación de reglas del sistema

### Casos testeados

* pago de boletos
* saldo negativo
* medio boleto
* franquicias
* transbordos
* bicicletas
* acreditación de saldo

---

# 📈 Cobertura de Código

El proyecto utiliza:

* NUnit
* GitHub Actions
* Codecov

Badge de cobertura incluido en el repositorio.

---

# 🛠️ Tecnologías

* C#
* .NET
* NUnit
* GitHub Actions
* Codecov
* Programación Orientada a Objetos
* Testing automatizado

---

# 🧩 Conceptos Aplicados

* OOP
* Herencia
* Polimorfismo
* Encapsulamiento
* Testing
* Clean Code
* Domain Modeling
* Git Workflow
* Coverage
* Integración continua

---

# ▶️ Cómo ejecutar

### Clonar repositorio

```bash
git clone https://github.com/Persfone/TarjetaSube
```

### Abrir en Visual Studio

Abrir la solución

```
TarjetaSube.sln
```

### Ejecutar tests

```
dotnet test
```

---

# 📌 Objetivo del Proyecto

Demostrar habilidades en:

* diseño de sistemas
* programación orientada a objetos
* testing
* modelado de dominio
* lógica de negocio
* uso de Git
* arquitectura de software

---

# 👩‍💻 Autor

Persfone
Técnica Informática – UNR

GitHub
https://github.com/Persfone


