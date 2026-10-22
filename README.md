# QUBIRA ODACL

**Oficina de Dirección de Asuntos Corporativos y Legales (ODACL)**
Plataforma oficial de gestión legal, gobierno societario, contratos corporativos, marco normativo peruano y compliance de **QUBIRA**

---

## 🏛️ Identidad Corporativa
- **Razón Social:** QUBIRA
- **RUC:** 10764275981
- **Condición:** ACTIVO / HABIDO
- **Representación Legal:** Melani A. Luyo R. & Abraham Aranda Cerna
- **Sede:** Lima, República del Perú
- **Correo Institucional:** qubirasac@gmail.com
- **Portal Web:** https://qubira.vercel.app

---

## ⚖️ Módulos y Funcionalidades
1. **Dashboard Legal & Métricas:** KPIs de contratos activos, índice de compliance normativo (100%), agenda de vencimientos SUNAT y MINJUS.
2. **Información Societaria:** Ficha registral completa, objeto social detallado (CIIU 6201), libros societarios legalizados y marcas registradas ante INDECOPI (Clase 42).
3. **Marco Normativo & Leyes del Perú:** Compendio interactivo de las 8 leyes clave aplicables a empresas de software:
   - Ley N° 29733 (Protección de Datos Personales y Derechos ARCO)
   - Decreto Legislativo N° 822 (Ley sobre el Derecho de Autor de Software)
   - Ley N° 26887 (Ley General de Sociedades - S.A.C.)
   - Ley N° 30096 (Delitos Informáticos y Ciberseguridad)
   - Código Tributario & R.S. 183-2004/SUNAT (Detracciones del 12% en servicios TI)
   - D.L. 728 & Ley 31572 (Régimen Laboral y Teletrabajo)
   - Ley N° 29783 (Seguridad y Salud en el Trabajo)
   - Ley N° 29571 (Código de Protección y Defensa del Consumidor)
4. **Gestión de Contratos Corporativos:** Catálogo de contratos y visualizador del **Modelo Oficial de 14 Cláusulas** de Qubira, con soporte de impresión oficial y copia rápida.
5. **Doc. Legal (Editor Microsoft Word con Medidas A4, Formato APA 7 & Nube Cloudinary):**
   - **Medidas Oficiales A4:** 210 mm × 297 mm en lienzo visual físico continuo con fondo gris profesional.
   - **Estándar Oficial APA 7 (7ma Edición):**
     - Márgenes estrictos de 1 pulgada (2.54 cm / 25.4 mm) en los 4 costados (superior, inferior, izquierdo, derecho).
     - Encabezado APA 7 a 12.7 mm (0.5 pulgada) del borde superior con título abreviado (*running head*) a la izquierda y número de página secuencial en la esquina superior derecha.
     - Tipografía estándar APA 7: Times New Roman 12 pt (predeterminada) o Arial 11 pt / Georgia.
     - Interlineado ajustable: Doble espacio (2.0 APA 7), 1.5 (Corporativo), 1.15 y simple (1.0).
     - Soporte para sangría de primera línea APA 7 (1.27 cm / 0.5 pulg).
   - **Motor de Salto Automático de Hoja (Auto-Pagination Engine):**
     - Detección en tiempo real del límite inferior imprimible (246.2 mm).
     - Salto automático continuo: al exceder el límite escribiendo o pegando texto, se crea instantáneamente la siguiente hoja A4 (`data-page="2"`, etc.) y el cursor se mantiene activo sin perder foco ni caracteres.
     - Absorción y fusión inversa al borrar texto con `Backspace` o `Delete`, eliminando hojas vacías excedentes.
     - Salto de página manual mediante botón en cinta y atajo rápido `Ctrl + Enter` / `Cmd + Enter`.
   - **Catálogo de 11 Plantillas Legales Precargadas:** Contrato Laboral D.L. 728, Contrato de Prestación de Servicios, Licenciamiento Software SaaS, Desarrollo de Software 14 Cláusulas, SLA 99.9%, Servicios Profesionales TI, Prácticas Pre Profesionales Ley 28518, Proveedores de Infraestructura Cloud, Acuerdo NDA, Políticas de Privacidad y Términos y Condiciones.
   - **Exportación & Sincronización:**
     - Exportación nativa a **Microsoft Word (.doc)** con medidas A4, márgenes 2.54 cm y saltos de página de Word (`page-break-before: always`).
     - Impresión y descarga a **PDF** optimizado para hojas A4 con `@media print`.
     - Guardado y respaldo en la nube en **Cloudinary** (`qubira/legal/documentos`) con control de versiones y base de datos PostgreSQL Neon.
6. **Asesoría Legal & Consultas:** Mesa de partes virtual para dictámenes jurídicos solicitados por OTI, ODN, RRHH, ADG y OPP.
7. **Compliance & Matriz de Riesgos:** Semáforo de riesgos legales, dimensionamiento y planes de mitigación continuos.
8. **Políticas Corporativas:** Términos y condiciones, política de privacidad y código de ética empresarial.

---

## 🚀 Despliegue y Puertos
- **Local:** `http://localhost:5519`
- **Producción:** `https://qubira-odacl.vercel.app`
- **Autenticación:** Traspaso centralizado con 2FA desde `qubira-login.vercel.app`
