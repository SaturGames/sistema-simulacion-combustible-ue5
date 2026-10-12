# UE5 - Sistema Modular de Simulación de Combustible (SG 0.1 & 0.2)

Sistema modular y desacoplado de interacción y simulación de combustible desarrollado en **Unreal Engine 5.4**. Diseñado enfocado en arquitectura limpia, escalabilidad y separación de responsabilidades lógicas mediante el uso de Eventos Personalizados (CE) y Funciones (FN).

> **Core Focus:** Clean Architecture, Modular Interaction, State Management & Event-Driven UI.

---

## Demostración Visual y Arquitectura de Blueprints

### Showcase del Prototipo (Greybox & Gameplay)
<img width="1920" alt="Gameplay 1" src="https://github.com/user-attachments/assets/c8655256-4b58-47ea-9c02-235653d3a3eb" />
<img width="1920" alt="Gameplay 2" src="https://github.com/user-attachments/assets/d5998ed1-cfaa-4ba5-b545-25bd6e8091aa" />
<img width="1920" alt="Gameplay 3" src="https://github.com/user-attachments/assets/f668519d-1202-430b-bba4-06307e73e7a2" />
<img width="1920" alt="Gameplay 4" src="https://github.com/user-attachments/assets/2e289b84-463a-434c-9810-a70b1963c464" />
<img width="1920" alt="Gameplay 5" src="https://github.com/user-attachments/assets/ac5b7c5c-f90c-47a2-8b81-112f2e4bb39e" />

### Arquitectura de Blueprints y Código Documentado
<img width="1920" alt="Blueprint Logic 1" src="https://github.com/user-attachments/assets/55bff8ac-12ac-4365-996d-a0fd4dce0710" />
<img width="1920" alt="Blueprint Logic 2" src="https://github.com/user-attachments/assets/2c8d5600-a980-4249-a188-cac4d569f8ba" />
<img width="1920" alt="Blueprint Logic 3" src="https://github.com/user-attachments/assets/979ba56f-c09f-47e6-adbd-ae0a7c792e9a" />
<img width="1920" alt="Blueprint Logic 4" src="https://github.com/user-attachments/assets/664983b7-1e5c-41f8-8e7b-9f5f1d30b650" />
<img width="1920" alt="Blueprint Logic 5" src="https://github.com/user-attachments/assets/114a9ee9-d90e-46bb-ac69-7497039af6cf" />
<img width="1920" alt="Blueprint Logic 6" src="https://github.com/user-attachments/assets/d803ad92-8308-4a23-b347-33e2966ae5bb" />

---

## Aspectos Técnicos e Implementación

- **Desacoplamiento Lógico:** Separación entre lógica de procesamiento puro (Funciones) y el flujo de eventos en tiempo de ejecución (Custom Events).
- **Flujo de Gameplay & Estados:** Control riguroso de estados del vehículo, simulación de repostaje, restricción de inputs y UI reactiva mediante delegados/eventos.
- **Detección Eficiente:** Sistema de interacción por *Line Trace* optimizado evitando sobrecargar el *Tick* del personaje.
- **Workflow & Assets:** Integración de modelos de prueba (surtidor, vehículo, bidones) con colisiones optimizadas en UE5.

---

## Demostración en Video

-  **Prototipo Fase 1 (Base & Interaction):** [Ver demostración en LinkedIn](https://lnkd.in/p/d6fd_FJ9)
-  **Prototipo Fase 2 (Game Loop & Final Polish):** [Ver demostración en LinkedIn](https://lnkd.in/p/d5Qfkdfb)

---

**Desarrollado por Satur Games** | *Gameplay & Systems Programmer*
