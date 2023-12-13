# Registration-page-for-Educational-Institute-Events
        //Registration page for Educational Instituion Events

import java.io.*;
import java.util.*;
class Registration
{
    public static void main(String args[])

    {  
        System.out.println("----------------------------------------------");
        System.out.println("*****************REGISTRATION*****************"); 
        System.out.println("---------------------------------------------");
        System.out.println("Enter The following details for Registration");
        System.out.println("----------------------------------------------");
        Scanner scan = new Scanner(System.in);

        System.out.println("Enter your Roll number");
        String Rollnumber = scan.nextLine();

        System.out.println("Enter First name");
        String Firstname = scan.nextLine();

        System.out.println("Enter Last name");
        String Secondname = scan.nextLine();

        System.out.println("Enter your Year : (I/II/III/IV)");
        String Year = scan.nextLine();

        System.out.println("Enter your Sem : (I/II)");
        String Sem = scan.nextLine();
       
        System.out.println("Enter your Age:");
        int Age = scan.nextInt();

        scan.nextLine();

        System.out.println("Enter your Gender:");
        String Gender = scan.nextLine();

        System.out.println("Enter your Contact Number:");
        String Contactnumber = scan.nextLine();

        System.out.println("Enter your E.Manil Id:");
        String Email = scan.nextLine();

        System.out.println("Enter your Branch:");
        String Branch = scan.nextLine();

        System.out.println("Enter your College Name:");
        String Collegename = scan.nextLine();

        System.out.println("----------------------------");
        System.out.println("Your Details:");
        System.out.println("----------------------------");
        System.out.println("Roll Number: "+Rollnumber);
        System.out.println("Full Name: "+Firstname+" "+Secondname);
        System.out.println("Age: "+Age);
        System.out.println("Gender: "+Gender);
        System.out.println("Contact Number: "+Contactnumber);
        System.out.println("Email Id: "+Email);
        System.out.println("Class: "+Year+" Year "+Branch+" "+Sem+" Sem");
        System.out.println("Branch: "+Branch);
        System.out.println("College Name: "+Collegename);
        System.out.println("----------------------------");      
    }
}
