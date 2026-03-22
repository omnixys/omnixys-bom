# Omnixys BOM

Central dependency management for Omnixys ecosystem.

## Usage

```xml
<dependencyManagement>
  <dependencies>
    <dependency>
      <groupId>com.omnixys</groupId>
      <artifactId>omnixys-bom</artifactId>
      <version>0.1.0</version>
      <type>pom</type>
      <scope>import</scope>
    </dependency>
  </dependencies>
</dependencyManagement>
````

## Managed Dependencies
* omnixys-observability
* omnixys-kafka
* omnixys-logger
* Spring Boot
* OpenTelemetry

---