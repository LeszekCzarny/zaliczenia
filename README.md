import java.util.Scanner;

public class ScannerSystemIn {

    public static void main(String[] args) {

        String name = "Leszek";
        int nameLength = 0;
        int age = 0;
        int ageAsSecond = age * 365 * 24 * 60 * 60;
        String username = "Czarny";
        int usernameLength = 0;

        
        Scanner scan = new Scanner(System.in);


        System.out.println("Podaj swoje imię: ");
        int name  = scan.nextLine

        System.out.println("Podaj ile masz lat: ");
        int age = scan.next

        System.out.println("podaj swoje nazwisko: ")
        int username = scan.nextLine

        System.out.println("Cześć " + name + ", Twoje imie składa się z " + nameLength + " liter.");
        System.out.println("Masz " + age + " lat, w przeliczeniue na sekundy: " + ageAsSecond);
        System.out.println("A twoje nazwisko to " + username + " i składa się z " + usernameLength + " liter ")

    }

}
