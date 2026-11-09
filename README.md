Propuesta de Proyecto: Spring Boot 3 (v2 -
LocalStack)
Sistema de Procesamiento Masivo Transaccional y Eventos (Fintech / Batching +
LocalStack SQS &amp; DynamoDB)

1. Objetivos del Proyecto
 Procesamiento Masivo por Lotes (Spring Batch): Simular una cámara de compensación
financiera procesando archivos CSV masivos en bloques transaccionales atómicos con
políticas de reintento y tolerancias a fallos.
 Streaming y Mensajería Cloud (LocalStack SQS/SNS): Publicar eventos transaccionales
hacia colas SQS/SNS emuladas localmente en LocalStack mediante Spring Cloud AWS /
Spring Integration.
 Almacenamiento NoSQL Auditable (LocalStack DynamoDB): Registrar la auditoría
transaccional de alta velocidad e historial de movimientos en una tabla de DynamoDB local.
 Resiliencia Empresarial: Implementar Circuit Breakers (Resilience4j) para proteger
conexiones externas y aislar transacciones en la JVM (@Transactional).
