# --
设计模式的简单练习



1.简单工厂模式
      实例化对象的时候，不需要使用new一个相应的对象出来，而是根据实际的情况自动初始化一个类，而不用去管到底需要new哪个类，直接new一个基类。


2.策略模式
       一个对象有多种行为，而多种行为只有细微的差别，我们可以抽象出行为的基类和抽象方法，子类对过继承基类，来重写对应的行为。通过一个上下文管理器类去管理调用哪个子类的放啊，上下文管理器的一个属性是基类的对象，通过构造函数的传入不同的子类对象，上下文管理器的实现方法，也实现了调用父类的方法，通过上下文管理器的属性变现出来的属性行为，从而达到了调用不同的方法。
  
  
  
      简单工厂和策略模式：在第一次接触，觉得有一丝相同，简单工厂有一个工厂类，工厂类通过用户的行为来决定实例化哪个对象，策略模式中上下文管理器的父类属性，有点类似于工厂类实例化不同的对象，工厂类返回的是基类的对象，在实例化工厂类的时候，通过用户的输入来达到实例化不同的对象，然后调用相应的方法。而在策略模式中，返回的一定是上下文管理器对象，但是在上下文管理器类中，通过一个父类的属性和一个方法，来实现调用不同的方法。
                                                                                    2020-1-1：此时的见解。。
