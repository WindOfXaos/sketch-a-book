![image](./OO%20In%20the%20Eyes%20of%20an%20Architect.png)
<i>-OO In the Eyes of an Architect</i><br>

- OO has weakened the encapsulation we had before OO was introduced, even though it made it easier.
- The introduction of OO made data structure upcasting significantly more convenient (the old way of doing inheritance).
- While OO might not have given us something brand new, it did make polymorphism much safer and more convenient by eliminating the danger of using function pointers.

![image](./Where%20OO%20Shines.png)
<i>-Where OO Shines</i><br>

- Any of the source code dependencies can be turned around by inserting an interface in-between, this gives architects absolute control over the direction of all source code dependencies in the system.
- An example of **Dependecy Inversion** perks is that dependencies can be rearranged, so **UI** and **DB** depend on **business rules** not the other way around. As a result, the system can be compiled into separate components, and changes to low-level details have no effect on high-level policies, they become plugins to high-level policies that can be deployed and developed independently.