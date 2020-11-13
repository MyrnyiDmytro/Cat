# Cat
public class Cat {
    String color;
    String breed;
    double weight;
    double age;

    public void speak(){
        System.out.println("Meow");
    }
    public void eat(){
        System.out.println("Cat is eating");
    }
    public void sleep(){
        System.out.println("Cat fall asleep");
    }
        public Cat(String color, String breed, double weight, double age){
        this.breed = breed;
        this.color = color;
        this.weight = weight;
        this.age = age;
        }

    public void tellAboutYourself(){
        System.out.println("Color: " + color);
        System.out.println("Breed: " + breed);
        System.out.println("Weight: " + weight);
        System.out.println("Cat's "+ age +" years old");
    }
}
