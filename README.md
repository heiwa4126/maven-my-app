# maven-my-app

maven で hello world


```bash
mvn -B archetype:generate \
 -DgroupId=com.mycompany.app \
 -DartifactId=my-app \
 -DarchetypeArtifactId=maven-archetype-quickstart \
 -DarchetypeVersion=1.4
```

で作成したプロジェクトに exec-maven-plugin を追加したもの。

参照:
- [Maven – Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/#how-do-i-make-my-first-maven-project)
- [Exec Maven Plugin – Introduction](https://www.mojohaus.org/exec-maven-plugin/)

# build & run

```bash
mvn compile
mvn exec:java
# or
./run
```
