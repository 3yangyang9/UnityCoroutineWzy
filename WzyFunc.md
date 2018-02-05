# UnityCoroutineWzy
 Use Coroutine in Unity，We Can use Bool on Coroutine,Simple Develop.协程拓展在Unity中，我们可以运用Bool值判断等待

使用方法 直接在Yeild return 后面 接上New WaitStruct<int>(wewr, 2)   能够进行所有Struct类型数值的判断，但是要经过一个带有这个返回值的方法传入：
Wewr就是这个方法  我用的Int类型举例，后面判断的值也是Int 类型  对比如果是True 就继续执行，False就等待
