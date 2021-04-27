<p dir="RTL">
عندما تستعمل ال ref في معامل الدالة فهذا يشير على ان القيمة تمر بال Reference  وليس بال Value .
</p>
<p dir="RTL">
يجب استعمال ال ref في الدالة وايضاً عند مناده الدالة.
</p>
<p dir="RTL">
لكتابة ال ref:
</p>

`void Method(ref int refArgument)`

`{`

`  refArgument = refArgument + 44;`

`}`

`int number = 1;`

`Method(ref number);`

`Console.WriteLine(number);`
