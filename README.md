# ClassExample.java
public class ClassExample {
    int horseAge;
    public ClassExample(String horseName) {
        System.out.println("name of horse : "+horseName);
    }

    public void setAge(int ageHorse) {
        horseAge=ageHorse;
    }

    public int getAge() {
        System.out.println("Horse Age is :"+horseAge);
        return horseAge;
    }
    public static void main(String[] args) {
        ClassExample c = new ClassExample("manu");/*Object 1*/
        c.setAge(54);
        System.out.println("Horse Age reference is :"+c.horseAge);

        ClassExample c2 = new ClassExample("manu kumar");/*Object 2*/
        c2.setAge(546);
        System.out.println("Horse Age reference is :"+c2.horseAge);

        ClassExample c3 = new ClassExample("manuRAM");
        c3.setAge(10);
        System.out.println("Horse Age reference is :"+c3.horseAge);
    }
}
