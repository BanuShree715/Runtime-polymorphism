# Runtime-polymorphism
package runtimepolymorphysm;
class Animal
{
   public void move()
   {
      System.out.println("Animals can move");
   }
}
class Dog extends Animal {
   public void move() {
      System.out.println("Dogs can walk and run");
   }
}
public class Runtimepolymorphysm 
{
    public static void main(String[] args) 
    {
        Animal a = new Animal(); 
      Animal b = new Dog(); 
      a.move(); 
      b.move();
    }
    
}

Animals can move
Dogs can walk and run
