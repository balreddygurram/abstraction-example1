# abstraction-example1
abstract class Bike{  
   Bike(){System.out.println("this is my bike");}  
   abstract void run();  
   void changeGear(){System.out.println("gear");}  
 }  
  
 class suzuki extends Bike{  
 void run(){System.out.println("running ");}  
 }  
 class TestAbstraction2{  
 public static void main(String args[]){  
  Bike b = new suzuki();  
  b.run();  
  b.changeGear();  
 }  
}  
