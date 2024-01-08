# Showroom Management System

## Abstract & Introduction

Managing extensive information related to clients and cars in a showroom poses significant challenges. To overcome this difficulty, we have developed a program that allows users to effortlessly manage car records, make purchases, sell cars, or create accounts for special offers. The primary purpose of this program is to efficiently manage the functionalities of a showroom.

## Methodology

Upon running the program, clients are presented with an account registration interface offering three options: 
1. **Login [y]**
2. **Register [n]**
3. **Don’t Login [l]**

Clients must enter the corresponding letter of their choice, with invalid entries not accepted by the program. If clients already have an account, they can log in using two methods: 
1. **Email [y]**
2. **Contact No. [l]**

Both methods require valid credentials. After successful login, clients are allowed into the showroom; otherwise, they can try again, register, or proceed without logging in. 

If the client chooses to register, the program collects personal information and stores it in the accounts CSV. The newly registered client is logged in automatically.

After gaining access to the showroom, clients are provided with four options: 
1. **Car Purchase**
2. **Car Rent Service**
3. **Car Sale**
4. **Exit**

Invalid entries or choices are not accepted.

### (1) Car Purchase

Clients choosing to purchase a car are given options:
- For Urgent Delivery [d]
- For Normal Booking [b]

For urgent delivery, the program displays available cars and prompts the client to choose a search method. Once chosen, the program matches the input with CSV data, calculates the total amount to be paid, and displays it.

For normal booking, the program shows a booking table and follows similar steps, providing a delivery time and a less expensive total amount.

### (2) Car Rent

Clients choosing car rental have two options:
- For Rent [q]
- For Special Offer [w]

For rent, the program displays a rental table, asks for the preferred search method, and generates a bill based on the rental duration.

For special offers, the program checks if the client is registered, allowing them to choose from various travel and wedding packages with corresponding amounts.

### (3) Car Sell

Clients desiring to sell a car can view a table of cars the showroom is willing to purchase. After entering the car name and condition, the program calculates the purchase rate. If the condition is suitable, the client provides contact information for inspection.

### (4) Exit

The program ends with a "~ GOODBYE ~" message.

## Specifications

- **Data Storage**: Uses CSV files to store accounts, car records, and purchase details.
- **User Authentication**: Validates login credentials for access to showroom features.
- **Error Handling**: Provides error messages for invalid inputs and choices.
- **Special Offers**: Account holders can avail special travel and wedding packages.
- **Data Validation**: Checks for existing accounts, preventing duplicate registrations.

## Conclusion

This program efficiently manages showroom functionalities, including car purchases, rentals, and sales. The user-friendly interface, along with data validation and error handling, ensures smooth interactions for clients.
