

class Employee {
private String name;
private int age;


Employee() {}

public String getName() {
    return name;
}

public void setName(String name) {
    this.name = name;
}

public int getAge() {
    return age;
}

public void setAge(int age) {
    this.age = age;
}

public void displayDetails() {
    System.out.println("Name: " + name);
    System.out.println("Age: " + age);
}

}

public class Main {
public static void main(String[] args) {
Employee emp = new Employee();


emp.setName("John Doe");
    emp.setAge(30);

    System.out.println("Employee Details:");
    emp.displayDetails();

    System.out.println("\nName: " + emp.getName());
    System.out.println("Age: " + emp.getAge());
}

}

Output:

Employee Details:
Name: John Doe
Age: 30

Name: John Doe
Age: 30# Getting-and-setter-method-
