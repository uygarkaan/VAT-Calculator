## VAT Calculator

## Project Overview

The VAT Calculator is a simple Java-based application that calculates the Value-Added Tax (VAT) for a given product price. 
This program prompts the user to input a price and the VAT rate, then computes the VAT amount and the total price including VAT.

## Features

- User Input: The program uses the Scanner class to accept user input for the price and VAT rate.
- Calculation: The VAT is calculated by multiplying the price by the VAT rate and then dividing by 100. The total price is calculated by adding the VAT amount to the original price.
- Output: The program displays the VAT amount and the total price on the console.

## Code Explanation

Here's a brief overview of the key components in the code:

- Variable Declarations: The price and VAT rate are stored in double variables.
- Input Gathering: The program asks the user to enter the product price and the VAT rate as a percentage.
- VAT Calculation: The program calculates the VAT amount by multiplying the price by the VAT rate and then dividing by 100. 
  The total price is calculated by adding the VAT to the original price.
- Output: The final VAT amount and total price are displayed to the user.

## Example Usage

Here's an example of how the program might work:

Enter the product price: 100
Enter the VAT rate (as a percentage): 18

VAT amount: 18.0 USD
Total price including VAT: 118.0 USD


import java.util.Scanner;

public class VATCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the product price
        System.out.print("Enter the product price: ");
        double price = scanner.nextDouble();

        // Prompt the user to enter the VAT rate (as a percentage)
        System.out.print("Enter the VAT rate (as a percentage): ");
        double vatRate = scanner.nextDouble();

        // Calculate the VAT amount
        double vatAmount = (price * vatRate) / 100;

        // Calculate the total price including VAT
        double totalPrice = price + vatAmount;

        // Display the results
        System.out.println("VAT amount: " + vatAmount + " USD");
        System.out.println("Total price including VAT: " + totalPrice + " USD");

        scanner.close();
    }
    }
    ## Follow Me

#### Hello! I'm **Uygarcode**, a passionate software developer constantly exploring new innovations in technology and coding. I would be thrilled to have you join me on my coding journey!

#### You can find my coding projects, tech news, and personal updates on my social media accounts. Stay updated with my latest projects and follow the latest trends in the tech world through the links below: 

- #### **GitHub:** [github.com/uygarcode](https://github.com/uygarcode) - Explore my code projects, open-source contributions, and development journey!
- #### **LinkedIn:** [linkedin.com/in/uygarkaan](https://linkedin.com/in/uygarkaan) - Connect with me professionally and follow my career development.
- #### **Instagram:** [instagram.com/uygarcode](https://instagram.com/uygarcode) - Check out my personal updates, tech news, and more!
- #### **Discord:** [discord.gg/8v6SW9gnEt](https://discord.gg/8v6SW9gnEt) - Join our software community and engage in coding discussions!

