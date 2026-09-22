# Campos y reglas para contratos de personal

## Datos que pueden extraerse del carnet

Extraer únicamente los datos que estén claramente visibles:

- Nombres.
- Apellidos.
- Número de carnet de identidad.
- Complemento del carnet, cuando corresponda.
- Nacionalidad, cuando aparezca expresamente.
- Fecha de nacimiento, cuando el contrato la requiera.
- Lugar de nacimiento, cuando el contrato lo requiera.

No inferir información que no esté escrita o que no sea legible.

## Datos que no deben deducirse del carnet

No utilizar el carnet para determinar:

- Domicilio actual.
- Correo electrónico.
- Número de teléfono.
- Área.
- Cargo.
- Honorarios.
- Moneda.
- Cuenta bancaria.
- Fecha de inicio.
- Fecha efectiva del contrato.
- Registro tributario.
- Modalidad de pago.
- Duración.
- Preaviso.
- Condiciones especiales.

Estos datos deben ser proporcionados o confirmados por el usuario.

## Campos variables

| Campo | Fuente | Regla |
|---|---|---|
| Referencia contractual | Control interno | Solicitar o marcar como pendiente; no inventar una secuencia |
| Fecha efectiva | Usuario | Coordinar la fecha de firma y la fecha de inicio, salvo instrucción diferente |
| Nombre legal | Carnet | Copiar literalmente |
| Documento de identidad | Carnet | Copiar número y complemento visibles |
| Nacionalidad | Carnet o usuario | No inferir por el país de emisión |
| Domicilio | Usuario | No confundir con el lugar de nacimiento |
| Correo y teléfono | Usuario | Confirmar que sean vigentes |
| Registro de actividad | Usuario | Marcar pendiente u omitir si no corresponde |
| Área y cargo | Usuario | Confirmar antes de redactar el alcance |
| Alcance | Área y cargo | Redactar usando `alcances-por-area.md` y validar |
| Honorario y moneda | Usuario | No inferir de los contratos de otras personas |
| Modalidad de pago | Usuario | Aplicar el estándar únicamente con confirmación |
| Duración y preaviso | Usuario | No modificar silenciosamente |
| Cláusulas especiales | Usuario | Nunca heredarlas de otro contratista |

## Reglas de consistencia

- Mantener exactamente el mismo nombre en los tres documentos.
- Mantener el mismo documento de identidad.
- Mantener la misma fecha efectiva, salvo que el modelo exija una fecha diferente.
- Mantener coherente la descripción general del servicio.
- Traducir el cargo de manera consistente entre inglés y español.
- Identificar a la misma persona como contratista en el Independent Contractor Agreement.
- Identificar a la misma persona como receptor de la información en el NDA.
- Identificar a la misma persona como `Assignor` en el Technology Assignment Agreement.
- Eliminar cualquier dato perteneciente a la persona cuyo contrato haya sido usado como modelo.

## Condiciones estándar

No asumir automáticamente que las siguientes condiciones se aplican:

- Tarifa fija.
- Pago mensual.
- Plazo indefinido.
- Preaviso de 10 días.
- Dedicación completa.
- Horario específico.
- Exclusividad.
- Beneficios.
- Bonificaciones.
- Seguros.
- Comisiones.
- Porcentajes.
- Penalidades.

Preguntar o pedir confirmación antes de incorporar estas condiciones.

## Control final

Antes de entregar, buscar en los tres documentos:

- Nombres de contratistas anteriores.
- Documentos de identidad anteriores.
- Fechas de ejemplo.
- Montos históricos.
- Direcciones de terceros.
- Correos y teléfonos de otras personas.
- Cargos incorrectos.
- Cláusulas especiales heredadas.
- Comentarios internos.
- Control de cambios pendiente.
- Campos vacíos.
- Texto oculto.
- Marcadores sin completar.
- Diferencias entre los tres documentos.

Presentar todos los datos pendientes y las inconsistencias encontradas.
