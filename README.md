# mill-test
scala mill test
examples: https://github.com/com-lihaoyi/mill/tree/main/example


## intellij support

* To generate IntelliJ IDEA project files into .idea/, run:  
```bash
mill mill.idea.GenIdea/idea
```

## mill commands
* all commands list  
```text
mill resolve __
```

* run
```
mill run --text Hi
```

* assembly
```text
mill assembly
mill show assembly
java -jar ./out/assembly.dest/out.jar --text hello
```
