# __proto__

   js创建所有的对象都有__proto__内置属性，而这个内置属性所指向的就是该对象的原型对象，而该原型对象就是由构造该对象的

类函数的prototype属性组成的（xxx.prototype）

   一个对象里面有原型对象（__proto__），而这个原型对象里面还有原型对象（__proto__），一直到顶端的Object.prototype.
   
而__proto__就是真正的原型链的实际指针。

   由附件图片可以清晰看出__proto__和prototype的关系
