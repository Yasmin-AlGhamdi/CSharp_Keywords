<p  dir="RTL">
This:
</p>
<p  dir="RTL">
تأشر على الحالة الحالية للclass وهو ايضاً يستعمل لتعديل المعامل الأول من دالة ممتدة.
</p>
<p  dir="RTL">
لا يمكنك استعمال ال  Thisفي static class. لانه موجود في مستوى ال class وليس جزء من ال Object.
</p>
<p  dir="RTL">
لكتابة ال This:
</p>

`public class Employee`

`{`

`  private string alias;`

`  private string name;`

`  public Employee(string name, string alias)`

`  {`

`  this.name = name;`

`  this.alias = alias;`

`  }`

`}`
