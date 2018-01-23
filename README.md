# Reaktivity BOM (Java)

Defines a consistent set of compatible dependencies.

## Compatibility

Please add the following snippet to your Maven `pom.xml` to select compatible versions of the `reaktor` and `nukleus` implementations.

```xml
  <dependencyManagement>
    <dependencies>
      <dependency>
        <groupId>org.reaktivity</groupId>
        <artifactId>ry-bom</artifactId>
        <type>pom</type>
        <version>0.1</version>
        <scope>import</scope>
      </dependency>
    </dependencies>
  </dependencyManagement>
```
