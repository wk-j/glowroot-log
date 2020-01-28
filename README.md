## Glowroot

```bash
mvn compile
java \
    -classpath target/classes  \
    -javaagent:./glowroot-logs/Mo-N-Flow/glowroot/glowroot.jar \
    wk.Program
```