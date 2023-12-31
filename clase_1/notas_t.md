# Simulación de sistemas
Bibliografía Pooch & Wall, 2000 
- [Simulación Monte Carlo](https://aws.amazon.com/es/what-is/monte-carlo-simulation/)

### Sistema:
Es un co

## Modelo:
Declaración no ambigua de la forma en la que interactuan los componentes del sistema. Se utilizarán modelos numéricos. Siempre va abstraer condiciones reales

  - Físico
  - Matemáticos

### ¿Qué tiene un modelo?
- Componentes del sistema
- Variables exógenas, endógenas, de estado
- Parámetros
- Relaciones funcionales entre los elementos de ese modelo

## Experimentos de simulación
Son ensayos en los que cambiamos una condición del sistema, mirando que salida se obtiene. Se quieren observar las salidas bajo distintas condiciones.

  1. Se definen combinaciones especificas de entradas MANIPULABLES
  2. Se hacen corridas bajo estas condiciones de control

- ¿Qué se cambia?: Entradas manipulables.
- Salidas: Medidas de desempeño


## Técnicas de simulación
Hay técnicas de simulación adecuadas a la naturaleza y tipo de sistema.
Se concentrará en el componente estocástico.

|  | Tiempo | ...|
|----------|----------|----------|
|     | Dinámica   | Estática  |
| Determinística   | Dinámica de sistemas   | --- |
| Estocástica   | Simulación basada en eventos, SBA  | Simulación Carlo |

### Simular o experimentar?
Considerar las condiciones de: costo, tiempo, replicación, seguridad, legalidad.
- ¿Por qué es conveniente usar simulación?
  - Porque algunos problemas matemáticos o de sistemas no tienen solución analítica
  - Porque la experimentación en sistemas reales suele ser costosa
  - Porque investiga estrategias posibles



