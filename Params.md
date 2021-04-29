<p  dir="RTL">
Params:
</p>
<p  dir="RTL">
باستعمال ال params يمكنك تحديد معامل دالة تستعمل اكثر من argument. المعامل يجب ان يكون مصفوفة أحادية الابعاد. لا يسمح باستعمال أي معامل اخر بعد ال  paramsعند تعريف الدالة وايضاً فقط يسمح باستعمال params واحد في تعريف الدالة.
</p>
<p  dir="RTL">
لكتابة ال Params:
</p>

`  public void Show(params int[] val) `

`  {  `

`  for (int i=0; i<val.Length; i++)  `

`  {`

`  Console.WriteLine(val[i]);`

`  }`

`  }`

`  static void Main(string[] args)`

`  {`

`  Program program = new Program();`

` program.Show(2,4,6,8,10,12,14);`

` } `
