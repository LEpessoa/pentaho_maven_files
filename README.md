# Pentaho Data Integration .m2 files for Maven

I only had the files for a specific version and I share the dependency import snippet here:
```xml
<dependency>
  <groupId>org.pentaho.reporting.engine</groupId>
  <artifactId>classic-core</artifactId>
  <version>9.2.0.3-424</version>
</dependency>
```

## Installation
Get all the files under the `Pentaho` folder (`Pentaho`, with a **capital** P) and paste them inside your `.m2` folder.
The `Pentaho` folder is the only folder in the root of this repository.
The paste the dependency snippet above in the dependencies section of your project's `pom.xml`.
