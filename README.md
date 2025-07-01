```mermaid
graph TD
    A[PROYECTO DEBIDA DILIGENCIA<br/>Diligence Platform] --> B[FASE 1: LANDING PAGE]
    A --> C[FASE 2: PEP NATURALES]
    A --> D[FASE 3: PEP JURÍDICOS]
    A --> E[FASE 4: IA OFICIAL CUMPLIMIENTO]
    A --> F[FASE 5: EVALUACIÓN RIESGO COOPAC]
    A --> G[FASE 6: EVALUACIÓN RIESGO SOCIO NATURAL]
    A --> H[FASE 7: EVALUACIÓN RIESGO SOCIO JURÍDICO]
    A --> I[FASE 8: EVALUACIÓN RIESGO CONTRAPARTES]

    B --> B1[Página web independiente]
    B --> B2[Generación de leads]
    B --> B3[Conversión de visitantes]

    C --> C1[Análisis y diseño del sistema]
    C --> C2[Sistema de Login]
    C --> C3[Registro de Coopac]
    C --> C4[Alta de usuario y contraseña]
    C --> C5[Dashboard con instrucciones]
    C --> C6[Búsqueda por DNI<br/>Listas: PEP, OFAC, ONU]
    C --> C7[Búsqueda por Nombres<br/>Listas: PEP, OFAC, ONU]
    C --> C8[Diseño de certificado<br/>de no inclusión en listas]

    D --> D1[Carga masiva Excel<br/>socios naturales]
    D --> D2[Búsqueda empresas por RUC<br/>Listas: PEP, OFAC, ONU]
    D --> D3[Búsqueda por Razón Social<br/>Listas: PEP, OFAC, ONU]
    D --> D4[Certificado empresas<br/>no incluidas en listas]

    E --> E1[Crear IA en plataforma]
    E --> E2[Evaluación de costos]
    E --> E3[Plan entrenamiento IA]
    E --> E4[Integrar chatBot IA]
    E --> E5[Pruebas de integración]

    F --> F1[Sistema evaluación<br/>riesgo cooperativas]
    G --> G1[Sistema evaluación<br/>riesgo personas naturales]
    H --> H1[Sistema evaluación<br/>riesgo personas jurídicas]
    I --> I1[Sistema evaluación<br/>riesgo contrapartes]

    %% Flujo de dependencias entre fases
    B -.-> C
    C -.-> D
    D -.-> E
    E -.-> F
    F -.-> G
    G -.-> H
    H -.-> I

    %% Estilos
    classDef phaseBox fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000
    classDef mainBox fill:#f3e5f5,stroke:#4a148c,stroke-width:3px,color:#000
    classDef taskBox fill:#f1f8e9,stroke:#33691e,stroke-width:1px,color:#000

    class A mainBox
    class B,C,D,E,F,G,H,I phaseBox
    class B1,B2,B3,C1,C2,C3,C4,C5,C6,C7,C8,D1,D2,D3,D4,E1,E2,E3,E4,E5,F1,G1,H1,I1 taskBox
```

# PROYECTO DEBIDA DILIGENCIA 
Diligence es una plataforma de software empresarial especializada en procesos de diligencia debida para transacciones corporativas complejas. La solución proporciona capacidades avanzadas de análisis de riesgo y evaluación de contrapartes, permitiendo a las organizaciones realizar evaluaciones comprehensivas de personas y entidades terceras antes de establecer relaciones comerciales estratégicas o completar operaciones de fusión y adquisición.

# FASE 1 : UNA LANDING PAGE
Es una página web independiente, diseñada con un objetivo específico en mente, usualmente dentro de una campaña de marketing. Su propósito principal es convertir a los visitantes en clientes potenciales o leads, guiándolos a través de una acción deseada, como rellenar un formulario, realizar una compra o descargar un recurso.


# FASE 2 : PROYECTO DEBIDA DILIGENCIA -> PEP (NATURALES)
- Análisis y diseño del sistema
- Login
- Registro de Coopac
- Alta de usuario contraseña de Coopac
- Dashboard con instrucciones de uso
- Buscar de personas DNI listas PEP, OFAC, ONU...
- Buscar de personas Nombres y Apellidos listas PEP, OFAC, ONU...
- Armar diseño de certificado que la(s) personas buscadas no se encuentren en la listas del sistema.

# FASE 3 : PROYECTO DEBIDA DILIGENCIA -> PEP  (JURÍDICOS)
- Cargar de Excel segun formato para carga masiva de socios naturales
- Buscar de empresas RUC listas PEP, OFAC, ONU...
- Buscar de empresas Razon social listas PEP, OFAC, ONU...
- Armar diseño de certificado que la(s) personas buscadas no se encuentren en la listas del sistema.

# FASE 4 : PROYECTO DEBIDA DILIGENCIA -> IA (OFICIAL DE CUMPLIMIENTO)
- Crear IA en plataforma de sevicios
- Evalucación de costos
- Plan de entrenamiento de la IA
- Integrar chatBot IA con el proyecto.
- Pruebas de integración

# FASE 5 : PROYECTO DEBIDA DILIGENCIA -> GENERAR EVALUACIÓN  DE RIESGO DE COOPAC
# FASE 6 : PROYECTO DEBIDA DILIGENCIA -> GENERAR EVALUACIÓN  DE RIESGO DE SOCIO NATURAL
# FASE 7 : PROYECTO DEBIDA DILIGENCIA -> GENERAR EVALUACIÓN  DE RIESGO DE SOCIO JURÍDICO
# FASE 8 : PROYECTO DEBIDA DILIGENCIA -> GENERAR EVALUACIÓN  DE RIESGO DE CONTRAPARTES
