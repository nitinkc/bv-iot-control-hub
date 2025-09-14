# Repository Scaffold – bv-iot-control-hub

```
bv-iot-control-hub/
  README.md
  ARCHITECTURE.md
  pom.xml
  services/
    device-registry/
    telemetry-service/
      mqtt/
    firmware-service/
      proto/firmware.proto
  docs/
    events/
      iot.telemetry.raw.v1.json
      iot.firmware.rollout.started.v1.json
  infra/pulumi/
  test-support/
    docker-compose.iot.yml
  bdd/features/
    telemetry_ingest.feature
  performance/
    load/TelemetryIngestSimulation.scala
```
