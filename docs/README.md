# Hello World 🌎

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.ershakiransari/planets/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.ershakiransari/planets)
[![javadoc](https://javadoc.io/badge2/com.github.ershakiransari/hello-java/javadoc.svg)](https://javadoc.io/doc/com.github.ershakiransari/hello-java)

![GitHub repo size](https://img.shields.io/github/repo-size/ershakiransari/planets?color=g&label=Repo%20Size&logo=github)
[![mvn-clean-build](https://github.com/ErShakirAnsari/planets/actions/workflows/mvn-clean-build.yml/badge.svg)](https://github.com/ErShakirAnsari/planets/actions/workflows/mvn-clean-build.yml)
[![Maven Central Deployment On Tag PUSH](https://github.com/ErShakirAnsari/planets/actions/workflows/publish-to-maven-central-with-tag.yml/badge.svg)](https://github.com/ErShakirAnsari/planets/actions/workflows/publish-to-maven-central-with-tag.yml)
---

### Solar System (Parent pom)

```
<parent>
    <groupId>${project.groupId}</groupId>
    <artifactId>solar-system</artifactId>
    <version>${project.version}</version>
</parent>
```

### Mercury

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>mercury</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Venus

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>venus</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Earth

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>earth</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Mars

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>mars</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Jupiter

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>jupiter</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Saturn

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>saturn</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Uranus

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>uranus</artifactId>
    <version>${project.version}</version>
</dependency>
```

### Neptune

```
<dependency>
    <groupId>${project.groupId}</groupId>
    <artifactId>neptune</artifactId>
    <version>${project.version}</version>
</dependency>
```