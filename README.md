# Redis Executable

Compiled Redis binaries(x64) for Windows, Linux and Mac OS.

# Source

Mac OS and Linux binaries are compiled with gcc and stripped debug symbols. Redis source is download
from `http://download.redis.io/releases/redis-5.0.10.tar.gz`.

Windows binary is directly download from `https://github.com/tporadowski/redis/releases`

# Usage

Artifact homepage: https://search.maven.org/artifact/io.coney.testing/redis-executable

Declare the dependency with test scope according to your scenario 

For Apache Maven:

``` xml
<dependency>
  <groupId>io.coney.testing</groupId>
  <artifactId>redis-executable</artifactId>
  <version>5.0.10</version>
</dependency>
```

For Gradle:

``` groovy
implementation 'io.coney.testing:redis-executable:5.0.10'
```
