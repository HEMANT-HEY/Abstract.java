# Abstract.java
// abstract.................
abstract class Animals1{
	abstract void Animal();

	public void Sound(){
		System.out.println("all animals have their sound");
	}
}
class Dog extends Abstract1{
	public void Sound(){
		System.out.println("Dogs are barking");
	}
}
class Cat extends Abstract1{
	 public void Sound(){
		System.out.println("cats are meauw");
	}
}
	public class  Abstract1{
		public static void main(String[] args){
			Dog D1=new Dog();
			D1.Sound();
			Cat C1=new Cat();
			C1.Sound();
	}
}
