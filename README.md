# Experiment-3
# AIM :
To write a java program to find the number of days in a month
# ALGORITHM :
1. Open a project in Intelij or any other online java program runner platform
2. Create a class
3. Declare a variable
4. Using scanner get the inputs 
5. Using for loop write the program to find the number of days in a month
6. Run and execute the program
# PROGRAM :
```
Developed by : K.Balaji
Register number : 212221230011
```
```
import java.util.Scanner;

public class Days {
    public static void main(String[] args)
    {
        int month;
        Scanner sc = new Scanner(System.in);
        sc = new Scanner(System.in);

        System.out.print(" Please Enter Month Number from 1 to 12 (1 = Jan, and 12 = Dec) : ");
        month = sc.nextInt();

        if (month == 1 || month == 3 || month == 5 || month == 7 || month == 8 || month == 10 || month == 12 )
        {
            System.out.println("\n 31 Days in this Month");
        }
        else if ( month == 4 || month == 6 || month == 9 || month == 11 )
        {
            System.out.println("\n 30 Days in this Month");
        }
        else if ( month == 2 )
        {
            System.out.println("\n Either 28 or 29 Days in this Month");
        }
        else
            System.out.println("\n Please enter Valid Number between 1 to 12");
    }
}
```
# OUTPUT:
![image](https://github.com/balaji-21005757/Experimennt-3/assets/94372294/21377bd1-7023-4653-9cfb-7c21bcaad488)
# RESULT:
Thus a java program to find the number of days in a month is executed successfully.
