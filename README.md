# Average-calculator-
import java.util.Scanner; // Scanner class for taking input
//Create class that's for all functions in the code 
public class ComputeAverage {
// create main method 
    public static void main(String[] args) {
        // Create a Scanner object
        Scanner input = new Scanner(System.in);

        // Ask the user to enter four numbers
        System.out.print("Enter four numbers: ");
        // Read inputs from the user 
        double number1 = input.nextDouble();
        double number2 = input.nextDouble();
        double number3 = input.nextDouble();
        double number4 = input.nextDouble();

        // Compute average
        double average = (number1 + number2 + number3 + number4) / 4;

        // Display results
        System.out.println("The average of the numbers is: " + average);

        input.close()
        }
          }
