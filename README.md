[![Stories in Ready](https://badge.waffle.io/kayasoftware/oss-parent.png?label=ready&title=Ready)](https://waffle.io/kayasoftware/oss-parent?utm_source=badge)
# Parent POM for Kaya Software's open source projects 

## About
This POM is used to provide a standard and consistent build for Maven-based Java projects.
It customizes the default behavior of Maven and supplies some organization-specific information to configure deployment settings and build profiles.

## Usage

Add the Kaya Software OSS POM as the parent to a project:

```xml
<parent>
  <groupId>kayasoftware.pom</groupId>
  <artifactId>oss-parent</artifactId>
  <version>1-SNAPSHOT</version>
</parent>
```
