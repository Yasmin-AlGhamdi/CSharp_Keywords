<p dir="RTL">
ال  outتجعل ال argument تتمرر بال  Reference.
</p>
<p dir="RTL">
يجب استعمال ال out  في الدالة وايضاً عند استدعاء الدالة.
</p>
<p dir="RTL">
ال  out تستعمل ايضاً لإرجاع اكثر من قيمة.
</p>
<p dir="RTL">
لكتابة ال out:
</p>

`int initializeInMethod;`

`OutArgExample(out initializeInMethod);`

`Console.WriteLine(initializeInMethod);  `

`void OutArgExample(out int number)`

`{`

`  number = 44;`

`}`
