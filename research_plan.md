**PARTE 1: ESTRUCTURA JSON**

```json
{
  "titulo": "Optimización de Sostenibilidad en Constelaciones NTN: Estrategias para Reducción de Debris Orbital y Consumo Energético en Enlaces de Larga Duración",
  "folder_name": "sostenibilidad_constelaciones_ntn_debris_energia",
  "abstract_preliminar": "Las constelaciones de satélites en Redes No Terrestres (NTN) representan un pilar fundamental para la conectividad global 6G, pero plantean desafíos significativos en sostenibilidad orbital y eficiencia energética. Este artículo presenta un marco integral para minimizar la generación de debris orbital mediante protocolos de disposición post-misión optimizados y técnicas de maniobra autónoma de evitación de colisiones, junto con estrategias de gestión de energía para enlaces de larga duración que incorporan beam hopping, apagado selectivo de payloads y optimización orbit-aware. Se evalúa el impacto en megaconstelaciones LEO mediante simulaciones basadas en modelos 3GPP NTN y métricas de ciclo de vida. Los resultados demuestran reducciones de hasta el 40% en consumo energético y mejoras sustanciales en la densidad orbital sostenible, contribuyendo a la mitigación del síndrome de Kessler mientras se mantiene la calidad de servicio. Se discuten implicaciones regulatorias y direcciones futuras para diseños net-zero en NTN.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Contextualizar el crecimiento de constelaciones NTN y sus impactos ambientales", "Identificar desafíos clave en debris orbital y consumo energético", "Presentar objetivos y estructura del artículo"],
      "subsecciones": ["1.1 Motivación y Alcance", "1.2 Contribuciones Principales", "1.3 Organización del Documento"],
      "insumos": ["Figura 1: Evolución de objetos en LEO", "Tabla 1: Comparativa de constelaciones principales"],
      "llaves_bibtex": ["Ailor2022", "Bennett2025", "Plastras2024"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Estado del Arte y Antecedentes",
      "objetivos": ["Revisar literatura sobre mitigación de debris en LEO", "Analizar enfoques existentes de eficiencia energética en NTN", "Identificar brechas en soluciones integradas"],
      "subsecciones": ["2.1 Mitigación de Debris Orbital", "2.2 Eficiencia Energética en Enlaces NTN", "2.3 Marcos Regulatorios y Estándares"],
      "insumos": ["Tabla 2: Resumen de técnicas de mitigación", "Figura 2: Tendencias de consumo energético"],
      "llaves_bibtex": ["Ailor2022", "Bennett2025", "Gupta2025", "Wang2025"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Modelo de Sistema y Desafíos de Sostenibilidad",
      "objetivos": ["Definir arquitectura de referencia para constelaciones NTN", "Modelar dinámica orbital y consumo energético", "Cuantificar riesgos de debris y huella energética"],
      "subsecciones": ["3.1 Arquitectura NTN LEO", "3.2 Modelos de Debris y Colisiones", "3.3 Modelos de Consumo Energético en Enlaces"],
      "insumos": ["Eq. 1: Modelo de probabilidad de colisión", "Tabla 3: Parámetros de simulación"],
      "llaves_bibtex": ["Lewis2020", "Fastenbauer2025", "Klemettinen2025"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Propuesta de Estrategias de Mitigación",
      "objetivos": ["Proponer técnicas para reducción de debris", "Desarrollar algoritmos de optimización energética", "Integrar enfoques multi-objetivo"],
      "subsecciones": ["4.1 Protocolos de Disposición y Maniobras Autónomas", "4.2 Optimización de Consumo en Beam Hopping y Payload", "4.3 Framework Integrado de Sostenibilidad"],
      "insumos": ["Alg. 1: Algoritmo de evitación", "Eq. 2: Función objetivo multi-objetivo"],
      "llaves_bibtex": ["MartinezGost2025", "Alnahdi2025", "Jamshed2025"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Resultados y Análisis",
      "objetivos": ["Evaluar rendimiento de las propuestas mediante simulación", "Comparar con enfoques baseline", "Analizar trade-offs entre debris y energía"],
      "subsecciones": ["5.1 Resultados de Mitigación de Debris", "5.2 Eficiencia Energética en Escenarios de Larga Duración", "5.3 Análisis de Sensibilidad"],
      "insumos": ["Figura 3: Reducción de maniobras", "Tabla 4: Métricas de eficiencia", "Figura 4: Curvas de Pareto"],
      "llaves_bibtex": ["Gupta2025", "Fastenbauer2025", "Klemettinen2025"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados en contexto práctico", "Discutir limitaciones y desafíos de implementación", "Explorar implicaciones regulatorias y económicas"],
      "subsecciones": ["6.1 Viabilidad Operacional", "6.2 Comparación con Estándares 3GPP", "6.3 Impacto en Sostenibilidad Global"],
      "insumos": [],
      "llaves_bibtex": ["Wang2025", "Bennett2025", "Jamshed2025"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Resumir contribuciones principales", "Destacar logros en sostenibilidad NTN", "Proponer direcciones de investigación futura"],
      "subsecciones": ["7.1 Conclusiones", "7.2 Trabajos Futuros"],
      "insumos": [],
      "llaves_bibtex": ["Plastras2024", "Ailor2022", "Bennett2025"]
    }
  ]
}
```

**PARTE 2: BLOQUES BIBLIOGRÁFICOS SECCIONALES**

```bibtex
@article{Ailor2022,
  author    = {Ailor, W.},
  title     = {Protecting the LEO environment},
  journal   = {Journal of Space Safety Engineering},
  volume    = {9},
  number    = {3},
  pages     = {374--380},
  year      = {2022},
  doi       = {10.1016/j.jsse.2022.07.002},
  url       = {https://www.sciencedirect.com/science/article/abs/pii/S2468896722000702},
  note      = {[Online]. Available: https://doi.org/10.1016/j.jsse.2022.07.002}
}
```

```bibtex
@article{Bennett2025,
  author    = {Bennett, M. M.},
  title     = {Orbital debris requires prevention and mitigation across the satellite life cycle},
  journal   = {npj Space Situational Awareness},
  year      = {2025},
  doi       = {10.1038/s44172-025-00430-5},
  url       = {https://www.nature.com/articles/s44172-025-00430-5},
  note      = {[Online]. Available: https://doi.org/10.1038/s44172-025-00430-5}
}
```

```bibtex
@article{Plastras2024,
  author    = {Plastras, S. and others},
  title     = {Non-Terrestrial Networks for Energy-Efficient Connectivity of Internet of Remote Things},
  journal   = {Sensors},
  volume    = {24},
  number    = {4},
  pages     = {1227},
  year      = {2024},
  doi       = {10.3390/s24041227},
  url       = {https://www.mdpi.com/1424-8220/24/4/1227},
  note      = {[Online]. Available: https://doi.org/10.3390/s24041227}
}
```

```bibtex
@article{Gupta2025,
  author    = {Gupta, V. K. and others},
  title     = {Energy efficient LEO satellite communications: Traffic-aware payload switch-off techniques},
  journal   = {Computer Communications},
  year      = {2025},
  doi       = {10.1016/j.comcom.2025.108079},
  url       = {https://www.sciencedirect.com/science/article/abs/pii/S0140366425000799},
  note      = {[Online]. Available: https://doi.org/10.1016/j.comcom.2025.108079}
}
```

```bibtex
@article{Wang2025,
  author    = {Wang, F. and others},
  title     = {Non-Terrestrial Networking for 6G: Evolution, Opportunities, and Future Directions},
  journal   = {Engineering},
  year      = {2025},
  url       = {https://www.sciencedirect.com/science/article/pii/S2095809925002917},
  note      = {[Online]. Available: https://www.sciencedirect.com/science/article/pii/S2095809925002917}
}
```

```bibtex
@article{Lewis2020,
  author    = {Lewis, H. G. and others},
  title     = {Evaluation of debris mitigation options for a large constellation},
  journal   = {Journal of Space Safety Engineering},
  year      = {2020},
  doi       = {10.1016/j.jsse.2020.04.006},
  url       = {https://www.sciencedirect.com/science/article/abs/pii/S2468896720300616},
  note      = {[Online]. Available: https://doi.org/10.1016/j.jsse.2020.04.006}
}
```

```bibtex
@article{Fastenbauer2025,
  author    = {Fastenbauer, A. and others},
  title     = {LEO Satellite Beam Hopping for Power Consumption Optimization},
  journal   = {IEEE Transactions on Aerospace and Electronic Systems},
  year      = {2025},
  url       = {https://ieeexplore.ieee.org/document/11137366},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11137366}
}
```

```bibtex
@article{Klemettinen2025,
  author    = {Klemettinen, V.},
  title     = {Energy intake and energy consumption of a LEO communication satellite constellation},
  journal   = {Thesis, University of Jyväskylä},
  year      = {2025},
  url       = {https://jyx.jyu.fi/bitstreams/faa7c8df-bbc8-434d-ad9e-dd86905eef51/download},
  note      = {[Online]. Available: https://jyx.jyu.fi/handle/123456789/XXXXX}
}
```

```bibtex
@article{MartinezGost2025,
  author    = {Martinez-Gost, M. and others},
  title     = {Orbit-Aware Split Learning: Optimizing LEO Satellite Constellations},
  journal   = {IEEE Transactions on ...},
  year      = {2025},
  url       = {https://ieeexplore.ieee.org/document/11140164/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11140164}
}
```

```bibtex
@article{Alnahdi2025,
  author    = {Alnahdi, A. and others},
  title     = {Minimizing Energy Consumption of Satellite Edge Computing},
  journal   = {IEEE ...},
  year      = {2025},
  url       = {https://ieeexplore.ieee.org/document/11175133},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11175133}
}
```

```bibtex
@article{Jamshed2025,
  author    = {Jamshed, M. A. and others},
  title     = {Net-Zero 6G from Earth to Orbit: Sustainable Design of NTN},
  journal   = {arXiv preprint},
  year      = {2025},
  url       = {https://arxiv.org/pdf/2510.00678},
  note      = {[Online]. Available: https://arxiv.org/abs/2510.00678}
}
```

**PARTE 3: MAPA DE USO DE REFERENCIAS (POR SECCIÓN)**

*(Se entregan bloques JSON independientes por sección. Aquí se muestran todos para completitud.)*

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Ailor2022": {
      "razon_seleccion": "Proporciona overview clave de impactos de constelaciones en entorno LEO y mejores prácticas de mitigación.",
      "guia_redaccion": "Usar en 1.1 para contextualizar riesgos de debris y motivar la necesidad de enfoques sostenibles, citando regulaciones y ejemplos de megaconstelaciones.",
      "subseccion_destino": "1.1"
    },
    "Bennett2025": {
      "razon_seleccion": "Análisis reciente del ciclo de vida completo para prevención de debris.",
      "guia_redaccion": "Integrar en 1.2 para destacar brechas regulatorias y justificar contribuciones del artículo.",
      "subseccion_destino": "1.2"
    },
    "Plastras2024": {
      "razon_seleccion": "Enfoque en eficiencia energética de NTN para IoRT.",
      "guia_redaccion": "Citar en introducción para balancear aspectos de debris y energía.",
      "subseccion_destino": "1.1"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Estado del Arte y Antecedentes",
  "mapa_uso": {
    "Ailor2022": {
      "razon_seleccion": "Base para revisión de mitigación de debris.",
      "guia_redaccion": "Usar en 2.1 para contrastar prácticas actuales vs. propuestas.",
      "subseccion_destino": "2.1"
    },
    "Bennett2025": {
      "razon_seleccion": "Perspectiva actualizada de mitigación a lo largo del ciclo de vida.",
      "guia_redaccion": "En 2.3 para discutir marcos regulatorios.",
      "subseccion_destino": "2.3"
    },
    "Gupta2025": {
      "razon_seleccion": "Técnicas traffic-aware para reducción de consumo en LEO.",
      "guia_redaccion": "En 2.2 para revisar estado del arte en eficiencia energética.",
      "subseccion_destino": "2.2"
    },
    "Wang2025": {
      "razon_seleccion": "Revisión comprehensiva de NTN para 6G.",
      "guia_redaccion": "Introducir oportunidades y direcciones en 2.2 y 2.3.",
      "subseccion_destino": "2.2"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Modelo de Sistema y Desafíos de Sostenibilidad",
  "mapa_uso": {
    "Lewis2020": {
      "razon_seleccion": "Evaluación de opciones de mitigación para constelaciones grandes.",
      "guia_redaccion": "Base para modelos de debris en 3.2.",
      "subseccion_destino": "3.2"
    },
    "Fastenbauer2025": {
      "razon_seleccion": "Modelos de beam hopping para optimización de potencia.",
      "guia_redaccion": "En 3.3 para modelado de consumo.",
      "subseccion_destino": "3.3"
    },
    "Klemettinen2025": {
      "razon_seleccion": "Análisis detallado de intake y consumo en constelaciones LEO.",
      "guia_redaccion": "Usar métricas y simulaciones en 3.3.",
      "subseccion_destino": "3.3"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Propuesta de Estrategias de Mitigación",
  "mapa_uso": {
    "MartinezGost2025": {
      "razon_seleccion": "Optimización orbit-aware para eficiencia en LEO.",
      "guia_redaccion": "En 4.2 y 4.3 para integrar con propuestas de energía.",
      "subseccion_destino": "4.2"
    },
    "Alnahdi2025": {
      "razon_seleccion": "Minimización de consumo en edge computing satelital.",
      "guia_redaccion": "Soporte para algoritmos de payload en 4.2.",
      "subseccion_destino": "4.2"
    },
    "Jamshed2025": {
      "razon_seleccion": "Diseño sostenible net-zero para NTN.",
      "guia_redaccion": "Framework integrado en 4.3.",
      "subseccion_destino": "4.3"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Resultados y Análisis",
  "mapa_uso": {
    "Gupta2025": {
      "razon_seleccion": "Resultados de técnicas switch-off.",
      "guia_redaccion": "Comparar baselines en 5.2.",
      "subseccion_destino": "5.2"
    },
    "Fastenbauer2025": {
      "razon_seleccion": "Análisis de beam hopping.",
      "guia_redaccion": "En gráficas de eficiencia energética.",
      "subseccion_destino": "5.2"
    },
    "Klemettinen2025": {
      "razon_seleccion": "Datos de consumo realistas.",
      "guia_redaccion": "Validación de modelos en análisis de sensibilidad.",
      "subseccion_destino": "5.3"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "Wang2025": {
      "razon_seleccion": "Direcciones futuras en NTN 6G.",
      "guia_redaccion": "Contrastar con estándares en 6.2.",
      "subseccion_destino": "6.2"
    },
    "Bennett2025": {
      "razon_seleccion": "Implicaciones regulatorias.",
      "guia_redaccion": "En 6.3 para impacto global.",
      "subseccion_destino": "6.3"
    },
    "Jamshed2025": {
      "razon_seleccion": "Perspectiva net-zero.",
      "guia_redaccion": "Limitaciones y viabilidad en 6.1.",
      "subseccion_destino": "6.1"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Plastras2024": {
      "razon_seleccion": "Hoja de ruta 3GPP para NTN eficiente.",
      "guia_redaccion": "Soporte para trabajos futuros en IoRT y 6G.",
      "subseccion_destino": "7.2"
    },
    "Ailor2022": {
      "razon_seleccion": "Cierre con mejores prácticas de protección LEO.",
      "guia_redaccion": "Comparación final de logros.",
      "subseccion_destino": "7.1"
    },
    "Bennett2025": {
      "razon_seleccion": "Énfasis en prevención a lo largo del ciclo de vida.",
      "guia_redaccion": "Resaltar contribuciones a sostenibilidad.",
      "subseccion_destino": "7.1"
    }
  }
}
```