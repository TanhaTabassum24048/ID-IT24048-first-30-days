Date-19 April 2026
Day-01
Topic-Creating Class and Object
Video num-03
Video link- https://youtu.be/lWFzm8qIR1c?si=O1mSzbbyW3buRrSQ
Example 1:
public class Animal{
    String sound;
    String color;
    int legs;
//
void chararcter(){
    System.out.println("Animal sound:" + sound) ;
    System.out.println("Animal color:" + color) ;
    System.out.println("Animal number of legs:" + legs) ;

} 
}

public class Main {
public static void main(String[] args) {
        Animal a = new Animal();    //object
        a.sound = "Bark";
        a.color = "Brown";
        a.legs = 4;
        a.chararcter();    //method call
    }
}


Example 2-
public class Student {
    String ID;
    String dept ;
    String faculty;

void stuInfo(){
    System.out.println("Student ID:" + ID);
    System.out.println("Student dept:" + dept);
    System.out.println("Student faculty:" + faculty);

}
}

import java.util.Scanner;

public class Main{
    public static void main(String[] args){
    Scanner sc = new Scanner(System.in);

    Student s1 = new Student();

    System.out.print("Enter ID:");
    s1.ID = sc.nextLine();

    System.out.print("Enter dept:");
    s1.dept = sc.nextLine();

    System.out.print("Enter faculty:");
    s1.faculty = sc.nextLine();

    s1.stuInfo();
    sc.close();
    
    }
}


