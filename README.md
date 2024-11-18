# Análisis de Clientes y Préstamos Personales

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una entidad financiera X para desarrollar estrategias comerciales diferenciadas. Se emplean técnicas de análisis de componentes principales (PCA) y clustering para identificar segmentos de clientes y patrones clave en los datos. Se divide en dos problemas principales: **Análisis de Satisfacción de Clientes** y **Análisis de Préstamos Personales**.

---

## **Problema 1: Clientes de la Entidad Financiera**

### **Interpretación de Componentes Principales (PCA)**

1. **PC1**:  
   Captura una dimensión relacionada con confianza, beneficios, aspectos de servicio personalizado y productos financieros. Refleja una actitud general positiva hacia la relación con la empresa o el servicio.

2. **PC2**:  
   Está asociado con la edad de los clientes, mientras que otras características tienen una relación mínima con este componente.

3. **PC3**:  
   Relacionado con características de contacto con ejecutivos, relevancia de los productos y seguridad. Existe una relación inversa con variables como atención personalizada y productos personalizados, sugiriendo un enfoque en otros aspectos.

### **Interpretación de Clusters**

#### **Cluster 1: Clientes con alta satisfacción**  
- Alta percepción positiva sobre la calidad del servicio y productos ofrecidos.  
- Enfoque en confianza, rapidez, personalización y asesoría.  
- Valoran productos de crédito, seguridad, beneficios, información accesible y contacto directo con ejecutivos.

#### **Cluster 2: Clientes con baja satisfacción**  
- Bajas expectativas sobre la calidad de servicio, beneficios y productos.  
- Menor satisfacción con rapidez, personalización y atención.  
- Menor compromiso y satisfacción con la empresa.

#### **Cluster 3: Clientes con expectativas moderadas**  
- Percepción equilibrada de servicios y productos.  
- Enfoque en confianza, beneficios, rapidez y asesoría experta.  
- Valoración más neutra, indicando expectativas moderadas pero satisfacción relativa.

---

## **Problema 2: Caso Préstamos Personales**

### **Interpretación de Factores**

1. **Factor 1**:  
   Captura comportamiento financiero en términos de plazos de pago y monto de cuotas.  
   - Clientes con altos valores: mayor historia financiera y compromiso de pagos.

2. **Factor 2**:  
   Relacionado con capacidad de pago y solvencia.  
   - Clientes con altos valores: buena capacidad de pago y consistencia en pagos activos.

3. **Factor 3**:  
   Relacionado con problemas de pago, como días de atraso y cuotas vencidas.  
   - Clientes con altos valores: historial problemático o en mora.

### **Interpretación de Clusters**

#### **Segmento 1**  
- Valores negativos en casi todas las variables.  
- Representa clientes con menor actividad o riesgo más bajo.

#### **Segmento 2**  
- Valores positivos en **DurMes_media**, **ImpCuo_Sol_media** y **SalAct_Sol_media**.  
- Clientes con compromisos financieros grandes y alta capacidad de pago.  
- Tasa negativa (Tasa_media) indica condiciones favorables.

#### **Segmento 3**  
- Similar al Segmento 2, pero con menor intensidad.  
- Grupo intermedio.

#### **Segmento 4**  
- Valores altos en **CuoVen_media** y **CuoPen_media**.  
- Representa clientes con más transacciones o historial reciente de pagos.

---


