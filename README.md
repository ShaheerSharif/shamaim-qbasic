### QBasic Programs

To compile & run files in vscode:

```
Press Ctrl+Shift+P
Type 'Tasks: Run Build Task'
```

To compile and run file in terminal/shell:

```shell
# Compile
qb64 -c <file-name>.bas
# Compile and specify output file name and/or path
qb64 -c <file-name>.bas -o <out-name>.exe
# Compile and don't open separate window
qb64 -x <file-name>.bas -o <out-name>.exe

# Run binary
./<out-name>
```

Download [**qb64**](https://qb64.com/) from website. <br>
Installation instructions are at [**GitHub**](https://github.com/QB64Official/qb64) page.