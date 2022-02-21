# Contribs Module
## Published Artifacts

Group: `com.netflix.conductor`

| Published Artifact | Description |
| ----------- | ----------- | 
| conductor-contribs | conductor-contribs  |

## Modules
1. Workflow Status Listener
2. Archival of workflows based on TTL

## Backward Compatibility
Contrib module retains the backward compatibility with earlier versions published from core Conductor repository.
This is achieved by created a shaded jar that also includes the output of the following modules:
1. event-queue (AMQP and NATS)
   1. SQS queue support is now part of core conductor
2. Metrics
3. Kafka and JQ tasks