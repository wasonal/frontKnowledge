## 关于硬绑定函数的prototype
当用构造函数生成一个实例的之后，我们可以通过实例的proto和构造函数的prototype是否相同来判断他们之间有没有关系   
但是对于硬绑定函数(bind生成的函数)，**它是没有prototype属性的**，所以不能通过上面的方法来判断，且其生成的实例的constructor属性是执行被绑定函数的
