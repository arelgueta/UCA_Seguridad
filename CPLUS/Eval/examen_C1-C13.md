# Examen integrador — Módulos 1 a 13

**Seguridad de la Información para Negocios Digitales**
Material de estudio: `SUPERCUADERNILLO.pdf`

30 preguntas · 10 Verdadero/Falso · 6 Unir conceptos · 14 Opción múltiple
Archivo de importación para Moodle: `examen_C1-C13.gift` (Banco de preguntas → Importar → formato GIFT)

---

## Parte A — Verdadero / Falso

1. En la demo descripta en el Módulo 1, una página web accedió a la cámara del celular sin un consentimiento consciente del usuario. Ese hecho constituye principalmente una violación de la confidencialidad.
2. Una función hash es reversible si se conoce la clave correcta, igual que el cifrado simétrico.
3. El objetivo de la gestión de riesgos en un negocio digital es alcanzar el "riesgo cero".
4. En un BIA bien diseñado, el RTO de un proceso debe ser menor o igual que su MTD.
5. Cuando una empresa contrata un servicio SaaS, la protección de sus datos y la gestión de identidades y accesos (IAM) pasan a ser responsabilidad del proveedor.
6. Un e-commerce argentino que realiza envíos a clientes en España debe cumplir el GDPR.
7. Las cookies de terceros (third-party) son las creadas por el mismo dominio que el usuario está visitando directamente.
8. Las técnicas que usan un White Hat y un Black Hat son esencialmente las mismas; lo que los distingue es la autorización del dueño del sistema.
9. Dentro de la pirámide documental, la política es el documento que describe los pasos operativos detallados para ejecutar una tarea.
10. Un BCP (Plan de Continuidad del Negocio) incluye al DRP, que se enfoca específicamente en recuperar los sistemas de información y tecnología.

## Parte B — Unir conceptos

**11. Cinco conceptos (e-commerce chico)**

| Elemento del caso | Concepto |
|---|---|
| Base de datos con 5.000 clientes y sus datos de tarjeta | Activo |
| Ataque de phishing dirigido a un empleado de atención al cliente | Amenaza |
| El empleado no fue capacitado y reutiliza su contraseña en sitios personales | Vulnerabilidad |
| Multa, pérdida de clientes y nota negativa en medios | Impacto |
| Combinación de la probabilidad del ataque y la gravedad de sus consecuencias | Riesgo |

**12. Amenazas**

| Amenaza | Descripción |
|---|---|
| Spear Phishing | Phishing dirigido e hiper-personalizado a una víctima concreta |
| Ransomware | Malware que cifra los datos y exige un rescate para liberarlos |
| BEC | Fraude mediante el correo comprometido o suplantado de un ejecutivo |
| Credential Stuffing | Ataque automatizado con contraseñas filtradas en otros sitios |
| Ingeniería social | Manipulación psicológica del factor humano |

**13. Las 4 T del tratamiento del riesgo**

| Estrategia | Ejemplo |
|---|---|
| Mitigar | Implementar MFA para reducir la probabilidad de robo de credenciales |
| Transferir | Contratar un seguro de ciber-riesgo |
| Aceptar | Tolerar 10 minutos de caída al año porque la redundancia cuesta más que la pérdida |
| Evitar | No almacenar datos de tarjetas y usar siempre una pasarela de pago externa |

**14. Continuidad y backups**

| Sigla / regla | Pregunta que responde |
|---|---|
| MTD | ¿Cuánto tiempo máximo puede estar caído el proceso antes de que el daño sea inaceptable? |
| RTO | ¿En cuánto tiempo nos proponemos volver a operar tras un incidente? |
| RPO | ¿Cuántos datos podemos permitirnos perder (cada cuánto se hace backup)? |
| Regla 3-2-1 | ¿Cuántas copias, en cuántos medios y cuántas fuera del sitio principal? |

**15. Derechos ARCO**

| Solicitud del usuario | Derecho |
|---|---|
| «Quiero saber qué datos tienen de mí y para qué los usan» | Acceso |
| «Tienen mal mi dirección, actualícenla» | Rectificación |
| «Ya no quiero ser cliente, bórrenme de su base de datos» | Cancelación (supresión) |
| «Pueden tenerme como cliente, pero no usen mis datos para publicidad» | Oposición |

**16. Marcos normativos**

| Norma / guía / organismo | Descripción |
|---|---|
| Ley 25.326 | Ley argentina de protección de datos personales |
| Ley 26.388 | Incorporó los delitos informáticos al Código Penal |
| GDPR | Reglamento europeo de protección de datos con aplicación extraterritorial |
| AAIP | Autoridad de control en materia de datos personales en Argentina |
| NIST SP 800-61 | Guía de referencia para el manejo de incidentes de seguridad |

> En Moodle las columnas de la derecha aparecen mezcladas como desplegables; acá se muestran ya emparejadas como clave.

## Parte C — Opción múltiple

**17.** ¿Cómo se genera, conceptualmente, una firma digital?
a) Se cifra el documento completo con la clave pública del receptor
b) **Se calcula el hash del documento y se lo cifra con la clave privada del firmante** ✔
c) Se cifra el documento con una clave simétrica compartida entre ambas partes
d) Se agrega una imagen escaneada de la firma manuscrita al PDF

**18.** ¿Cuál es la forma correcta de almacenar las contraseñas de los usuarios de un e-commerce?
a) En texto plano dentro de una base de datos con acceso restringido
b) Hasheadas con MD5, porque es rápido y ampliamente usado
c) **Hasheadas con bcrypt o Argon2, con un salt único por usuario** ✔
d) Cifradas con AES-256 usando la misma clave para todos los usuarios

**19.** En el caso "FintechYa", un ransomware cifró la base de clientes y la empresa estuvo 5 días sin procesar transacciones. ¿Qué pilar CID se afectó principalmente?
a) Confidencialidad   b) Integridad   c) **Disponibilidad** ✔   d) Ninguno, porque los datos no fueron robados

**20.** Según el mapa de calor, un riesgo con probabilidad ALTA e impacto BAJO se clasifica como:
a) Bajo   b) **Medio** ✔   c) Alto   d) Crítico

**21.** Un sistema de monitoreo que alerta cuando detecta tráfico de salida inusual desde un servidor es un control:
a) Preventivo   b) Correctivo   c) **Detectivo** ✔   d) Legal / normativo

**22.** ¿Qué afirmación describe correctamente la relación entre ISO/IEC 27001 y 27002?
a) **La 27001 define los requisitos de un SGSI y es certificable; la 27002 es un catálogo de controles y buenas prácticas** ✔
b) La 27002 es la norma certificable y la 27001 es solo una guía optativa
c) Ambas son leyes argentinas de cumplimiento obligatorio
d) La 27001 aplica solo a la nube y la 27002 solo a centros de datos físicos

**23.** En el caso Capital One (2019), un rol IAM con permisos excesivos amplificó el daño. ¿Qué principio se incumplió?
a) Privacidad por diseño   b) **Menor privilegio** ✔   c) Regla 3-2-1   d) Defensa por oscuridad

**24.** Según el GDPR, ¿en qué plazo debe notificarse a la autoridad una brecha de datos una vez detectada?
a) 24 horas   b) **72 horas** ✔   c) 10 días hábiles   d) 30 días corridos

**25.** Un banner de cookies con un botón "Aceptar todo" enorme y la opción "Rechazar" escondida en un menú secundario es un ejemplo de:
a) Privacidad por defecto   b) Consentimiento informado válido   c) Cookie de sesión   d) **Dark pattern** ✔

**26.** Un empleado manipula la base de datos de un e-commerce para alterar precios y obtener un beneficio económico. Según la Ley 26.388, es:
a) Acceso indebido   b) **Fraude informático** ✔   c) Interceptación de comunicaciones   d) Daño informático

**27.** En un simulacro de phishing, ¿qué indicador conviene que sea lo más ALTO posible?
a) La tasa de clic (CTR)   b) La tasa de apertura   c) **La tasa de reporte** ✔   d) El tiempo hasta el primer reporte

**28.** ¿Quién aprueba la política, asigna el presupuesto y es el responsable último de la seguridad de la organización?
a) **La Dirección / CEO** ✔   b) El área de TI   c) El DPO   d) Cada empleado, por igual

**29.** En la Junta de Crisis de "DataShop", ¿qué rol evalúa si corresponde notificar a la AAIP y si aplica el GDPR?
a) Comunicaciones   b) TI / Seguridad   c) Gerencia General   d) **Legal / Cumplimiento** ✔

**30.** Una auditoría realizada por un organismo independiente para certificar ISO 27001 es una auditoría:
a) De primera parte (interna)   b) De segunda parte (cliente)   c) **De tercera parte (de certificación)** ✔   d) Forense

---

## Clave rápida

| Parte A | 1 V · 2 F · 3 F · 4 V · 5 F · 6 V · 7 F · 8 V · 9 F · 10 V |
|---|---|
| Parte B | Pares tal como figuran en las tablas 11–16 |
| Parte C | 17 b · 18 c · 19 c · 20 b · 21 c · 22 a · 23 b · 24 b · 25 d · 26 b · 27 c · 28 a · 29 d · 30 c |

## Cobertura por módulo

| Módulo | Preguntas |
|---|---|
| M1–M2 Fundamentos y CID | 1, 11 |
| M3 Amenazas | 12, 19 |
| M4 Criptografía | 2, 17, 18 |
| M5 Gestión de riesgos | 3, 13, 20 |
| M6 BIA, controles, ISO | 4, 14, 21, 22 |
| M7 Nube | 5, 14, 23 |
| M8 Datos personales | 6, 15, 16, 24 |
| M9 Cibercrimen, ética, cookies | 7, 16, 25, 26 |
| M10 Hacking ético y phishing | 8, 27 |
| M11 Gobierno y PSA | 9, 28 |
| M12 Factor humano e incidentes | 29 |
| M13 Continuidad y auditoría | 10, 16, 30 |
