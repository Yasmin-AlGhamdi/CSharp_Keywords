<p dir="RTL">
1. abstract:
</p>
<p dir="RTL">
هو معدل يمكن استعماله مع .classes, methods,  properties, indexers, and events
</p>
<p dir="RTL">
من الممكن للabstract class ان يحتوي على abstract methods.
</p>
<p dir="RTL">
اذا كانت ال method abstract  لا يسمح باستعمالها الا من class موروث.
</p>
<p dir="RTL">
لا يمكنك استعمال او صناعة object لabstract class.
</p>
<p dir="RTL">
لكتابة abstract class:
</p>

`  abstract class Shape`

<p dir="RTL">
لكتابة abstract method:
</p>

`public abstract void MyMethod();`
</p>

<p dir="RTL">
2. classes:
</p>
<p dir="RTL">
هو من نوع الReference Type مما يعني انه يحتوي على قيمة null حتى يقوم المستخدم بإعطائه قيمة باستعمال new او بصناعة object له.
</p>
<p dir="RTL">
لكتابة class:
</p>

`  public class Customer`
<p dir="RTL">
لصناعة object لل class:
</p>

`  MyClass mc = new MyClass();`

<p dir="RTL">
3. as:
</p>
<p dir="RTL">
هو عامل يقوم بالتحويل بين الReference types. ثم يقوم بإعادة الobject اذا كان التحويل ممكن واذا لم يتمكن من التحويل يقوم بإعادة null.
</p>
<p dir="RTL">
لكتابة عامل as:
</p>

`  string str = obj[j] as string;`

<p dir="RTL">
4. base:
</p>
<p dir="RTL">
هي كلمة تستعمل لاستدعاء بعض الخصائص من الclass المركزي.
</p>
<p dir="RTL">
يمكن استعمال كلمة الbase في ال constructor, instance method,او instance property accessor.
</p>
<p dir="RTL">
لا يمكن استعمال الbase في ال static method.
</p>
<p dir="RTL">
لكتابة الbase:
</p>

`  public DerivedClass() : base()`

<p dir="RTL">
5. goto:
</p>
<p dir="RTL">
هي بيان يسمح للبرنامج ان ينتقل الى مكان معين في البرنامج. وهي جداً مفيدة ان اردت ان تتفادى الnested loops.
</p>
<p dir="RTL">
لكتابة ال goto:
</p>

`Console.WriteLine($"The number {myNumber} was not found.");`

` goto Finish;`

`Finish:`

`  Console.WriteLine("End of search.");`

<p dir="RTL">
6. delegate:
</p>
<p dir="RTL">
هو نوع يعرض المراجع للmethods التي تمتلك نوع معين من العوامل ونوع معين من الاسترجاع.
</p>
<p dir="RTL">
عندما تقوم بأنشاء ال  delegate يمكنك ان تربط خصائصها مع أي دالة تملك نفس الخصائص.
</p>
<p dir="RTL">
ال  delegate مرنة فهي تسمح للstatic وال instance method بالتعامل معها.
</p>
<p dir="RTL">
لكتابة ال delegate:
</p>

`public delegate int PerformCalculation(int x, int y);`
