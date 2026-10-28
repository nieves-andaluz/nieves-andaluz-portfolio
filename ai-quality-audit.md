# AI assistant quality audit — reconstructed portfolio sample

**Status:** illustrative demonstration, created for this portfolio. It is not a report from Rauda AI, a former employer, a client, or a real production assistant. The interaction and finding below are fictional. No actual company or customer data is included. The evaluation categories reflect the work scope described in Nieves's CV and her portfolio context.

## Scenario (fictional)

A customer asks a voice assistant when an event ticket will be delivered. The assistant cannot verify the order status, but tells the customer the ticket will arrive within an hour and ends the conversation without checking an approved source or offering a human handoff.

## Audit objective

Check whether the answer is grounded in approved information, complete, consistent, appropriately phrased, and safely escalated when the assistant cannot verify a customer-specific fact.

## Review rubric

| Dimension | Review question | Example status in this fictional interaction |
|---|---|---|
| Accuracy and grounding | Is each claim supported by an approved source or verified order status? | **Fail:** the one-hour delivery claim is unsupported. |
| Resolution | Does the interaction give a safe next step that addresses the customer's need? | **Fail:** no status check or next step is offered. |
| Completeness | Does the assistant gather the information needed to investigate? | **Partial:** it does not request or use an order reference. |
| Consistency | Does the answer match the same policy and workflow used in comparable cases? | **Review needed:** no approved source is cited in the interaction. |
| Tone and clarity | Is the answer clear, respectful, and easy to understand by voice? | **Pass in this example:** wording is understandable, but confidence exceeds evidence. |
| Escalation | Does the assistant hand off when it cannot verify the answer? | **Fail:** no human handoff is offered. |

## Finding and recommended action

**Finding:** unsupported certainty in a customer-specific delivery answer, combined with a missing verification and handoff step.

**Why it matters:** the customer may rely on a promise that the system cannot substantiate, and the issue can become a repeat contact.

**Recommended prompt/workflow change:** require the assistant to check a trusted order-status source before giving a delivery estimate. If the source is unavailable or inconclusive, state that clearly and offer a human handoff. Do not invent a timeframe.

**Retest:** run the same scenario with a verified status, a missing status, and an unavailable source. Confirm the answer changes appropriately and the handoff path works.

## Evidence record to capture in a real audit

- Test ID and approved test prompt
- Assistant version and test date
- Relevant policy or knowledge source
- Sanitized response excerpt
- Dimension-level judgement and rationale
- Severity and customer impact
- Owner, corrective action and retest status

**Portfolio integrity:** the method is presented as a demonstration. This scenario is not an actual audit finding or measured result.

---

# Auditoría de calidad de un asistente de IA — muestra reconstruida

**Estado:** demostración ilustrativa creada para este portafolio. No es un informe de Rauda AI, de un empleador anterior, de un cliente ni de un asistente real en producción. La interacción y el hallazgo son ficticios. No se incluyen datos reales de empresas o clientes. Las categorías reflejan las funciones descritas en el CV y el contexto profesional compartido por Nieves.

## Escenario ficticio

Un cliente pregunta a un asistente de voz cuándo recibirá su entrada para un evento. El asistente no puede verificar el estado del pedido, pero asegura que llegará en una hora y termina la conversación sin consultar una fuente aprobada ni ofrecer derivación a una persona.

## Objetivo de la auditoría

Comprobar si la respuesta se apoya en información aprobada, es completa y coherente, utiliza un tono adecuado y deriva el caso con seguridad cuando no puede verificar un dato específico del cliente.

## Rúbrica de revisión

| Dimensión | Pregunta de revisión | Estado de ejemplo en esta interacción ficticia |
|---|---|---|
| Precisión y fuentes | ¿Cada afirmación se apoya en una fuente aprobada o un estado de pedido verificado? | **Falla:** el plazo de una hora no tiene respaldo. |
| Resolución | ¿Ofrece un siguiente paso seguro que resuelva la necesidad? | **Falla:** no verifica el estado ni propone qué hacer. |
| Completitud | ¿Recopila la información necesaria para investigar? | **Parcial:** no solicita ni utiliza una referencia del pedido. |
| Coherencia | ¿La respuesta sigue la misma política y flujo que casos comparables? | **Revisar:** no aparece una fuente aprobada en la interacción. |
| Tono y claridad | ¿Es clara, respetuosa y fácil de entender por voz? | **Supera el criterio en este ejemplo:** se entiende, pero muestra más seguridad que evidencia. |
| Derivación | ¿Deriva el caso cuando no puede verificar la respuesta? | **Falla:** no ofrece hablar con una persona. |

## Hallazgo y acción recomendada

**Hallazgo:** certeza sin respaldo en una respuesta sobre la entrega de un cliente, junto con la falta de verificación y derivación.

**Por qué importa:** el cliente podría confiar en una promesa no verificada y volver a contactar si no se cumple.

**Cambio recomendado en el prompt o flujo:** exigir una consulta a una fuente fiable del estado del pedido antes de dar un plazo. Si la fuente no está disponible o no permite confirmarlo, explicarlo y ofrecer atención humana. No inventar plazos.

**Reprueba:** repetir el escenario con estado verificado, estado no disponible y fuente caída. Confirmar que la respuesta cambia correctamente y que la derivación funciona.

## Evidencia que se registraría en una auditoría real

- ID de prueba y prompt aprobado
- Versión del asistente y fecha
- Política o fuente de conocimiento relevante
- Extracto anonimizado de la respuesta
- Evaluación por dimensión y justificación
- Severidad e impacto en la experiencia
- Responsable, acción correctiva y estado de la reprueba

**Integridad del portafolio:** este método se presenta como demostración. El escenario no es un hallazgo real ni un resultado medido.
