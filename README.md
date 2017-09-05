[![GitHub release](https://img.shields.io/github/release/javaercn/retrofit2-converter-jaxb.svg)]()
[![Maven Central](https://img.shields.io/maven-central/v/cn.javaer/retrofit2-converter-jaxb.svg)]()
[![Jitpack Release](https://jitpack.io/v/javaercn/retrofit2-converter-jaxb.svg)](https://jitpack.io/#javaercn/retrofit2-converter-jaxb)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Retrofit2 framework JAXB converter
==================================

## Use
Maven Central
```xml
<dependency>
    <groupId>cn.javaer</groupId>
    <artifactId>retrofit2-converter-jaxb</artifactId>
    <version>LATEST</version>
</dependency>
```

## Demo
```java
final Retrofit retrofit = new Retrofit.Builder()
    .baseUrl("http://demo.com")
    .addConverterFactory(JaxbConverterFactory.create())
    .build();
```
