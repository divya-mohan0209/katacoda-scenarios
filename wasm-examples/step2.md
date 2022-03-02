There are files already generated for you in case you don't want to play around and directly want to view the result. 

If you want to change the operation being performed, you can do that in **addition.ts**.

Convert into WASM and WAT formats by executing the command below if you have changed the addition.ts file.

_P.S. You do not need to re-execute the command if you haven't changed anything_

```
cd webassembly-blog-examples
asc addition.ts -b addition.wasm -t addition.wat
```