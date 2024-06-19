import java.util.Scanner;//import scanner class for reading user input

public class SurnameAndAge {
String surname;
int age;
    public static void main(String[] args) {
Scanner scanner = new scanner(System.in) 
        // request the user to enter surname
        System.out.print("Enter your surname: ");
String surname = scanner.nextline();
        

        // request the user to enter age
        System.out.print("Enter your age: ");
int age = scanner.nextint();

        

        // Calculate number of characters in surname
        int surnameLength = surname.length();

        // Determine if age is even or odd
        String ageType = (age % 2 == 0) ? "even" : "odd";

        // Output the results
        System.out.println("Number of characters in your surname: " + surnameLength);
        System.out.println("Your age is " + ageType + ".");
        
    }
}
