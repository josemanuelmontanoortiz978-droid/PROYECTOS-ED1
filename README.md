# PROYECTOS-ED1
Documentacion de los avances el Estructura de datos 1

Implementación académica desde cero (**sin depender de atajos nativos** como `list.append()`, `list.pop()` o `set()` para simular estructuras) de Tipos Abstractos de Datos (ADT), estructuras lineales estáticas y dinámicas, estructuras dispersas, tablas hash y patrones de arquitectura desacoplada.

Todos los módulos están diseñados para ejecutarse directamente en **Google Colab** 
---

## 🗂️ Estructura del Repositorio

```text
├── 01_polimorfismo_y_auditoria_ast/
│   ├── estructuras_lineales.py    # Interfaz EstructuraLineal, Pila (LIFO) y Cola (FIFO)
│   └── auditor_ast.py             # Script de verificación automática mediante módulo ast
├── 02_adt_pila_estatico_vs_dinamico/
│   ├── adt_pila.py                # ADTPila, PilaArray (ctypes) y PilaLista (nodos)
│   ├── estatico_vs_dinamico.py    # ArrayEstatico vs. ListaDinamica + Benchmark 50 estudiantes
│   └── repositorio_persistencia.py# Persistencia JSON/Pickle con Patrón Strategy
├── 03_adt_algebraicos_y_dispersos/
│   ├── polinomio_adt.py           # Polinomio sobre lista enlazada ordenada descendente
│   ├── conjunto_adt.py            # ConjuntoADT algebraico desde cero (∪, ∩, -, Δ, ⊆)
│   ├── matriz_dispersa.py         # MatrizDispersa (DOK) vs. Matriz Densa (memoria/tiempo)
│   └── inventario_regional.py     # Sistema integrado (Conjuntos + Polinomio + MatrizDispersa)
└── 04_estructuras_avanzadas_y_turnos/
    ├── lista_simple_y_pilas.py    # ListaSimple y comparativa intensiva PilaEstatica vs. PilaDinamica
    ├── cola_circular_y_bicola.py  # ColaCircular modular y Bicola doblemente enlazada
    ├── tabla_hash.py              # TablaHash con función polinómica y encadenamiento separado
    └── sistema_turnos.py          # Mini sistema de turnos (ColaCircular + TablaHash + JSON)
