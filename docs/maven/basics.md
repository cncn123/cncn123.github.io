---
layout: default
title: Basics
parent: Maven
---

{: .note }
> ref: [Maven Apache Tutorial]

1. POM
- `project` - root
- `modelVersion` - should be set to 4.0.0
- `groupId` - the id of the project's group.
- `artifactId` - the id of the artifact (project)
- `version` - the version of the artifact under the specified group

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0">
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.mycompany.app</groupId>
  <artifactId>my-module</artifactId>
  <version>1</version>
</project>
```


[Maven Apache Tutorial]: https://maven.apache.org/guides/introduction/introduction-to-the-pom.html