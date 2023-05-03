# GCtesting

### 1.VS Code
 launch.json
 ```info
 {
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "type": "java",
            "name": "Current File",
            "request": "launch",
            "mainClass": "${file}"
        },
        {
            "type": "java",
            "name": "ServertestApplication",
            "request": "launch",
            "mainClass": "com.example.servertest.ServertestApplication",
            "projectName": "servertest",
            "vmArgs": "-XX:+UseSerialGC -Xms1024m -Xmx1024m -verbose:gc -XX:+PrintGCDetails"
        }
    ]
}
```

```shell
```

```git
```

```yaml
```
