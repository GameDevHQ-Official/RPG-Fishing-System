# RPG Fishing System

## Objective

Create a text-based fishing system in C++ where players can catch fish from a predefined fishing table. The system will randomly select a fish, display it to the user, and add the fish name to the player's dynamically managed inventory.

## Requirements

### Fishing Table

- Define a fishing table with item IDs and corresponding fish names using two separate static arrays.
- Use `std::rand()` to randomly select a fish from the fishing table.

### Inventory Management

- Use `std::vector` to manage the player's inventory dynamically.
- Add the caught fish to the inventory.

### Fish Items Table

| Item ID | Fish Name    |
|---------|--------------|
| 317     | Shrimp       |
| 327     | Sardine      |
| 345     | Herring      |
| 321     | Anchovies    |
| 377     | Lobster      |
| 371     | Swordfish    |
| 359     | Tuna         |
| 383     | Shark        |

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<vector>`, `<string>`, `<cstdlib>`, `<ctime>`).

### 2. Define Fishing Table

- Create two static arrays: one for fish item IDs and one for fish names.

### 3. Implement Fishing Function

- Implement a function to randomly select a fish and display the caught fish to the user.

### 4. Implement Inventory System

- Implement a function to add the caught fish to the player's dynamically managed inventory and display the inventory.

## Example User Interaction

```plaintext
*****************************************************************
*                     RPG Fishing System                        *
*****************************************************************

Enter 'f' to fish, 'i' to display inventory, 'q' to quit: f
You caught a Shark!
Enter 'f' to fish, 'i' to display inventory, 'q' to quit: f
You caught a Lobster!
Enter 'f' to fish, 'i' to display inventory, 'q' to quit: f
You caught a Herring!
Enter 'f' to fish, 'i' to display inventory, 'q' to quit: i

Inventory:
- Shark
- Lobster
- Herring

Enter 'f' to fish, 'i' to display inventory, 'q' to quit: f
You caught a Tuna!
Enter 'f' to fish, 'i' to display inventory, 'q' to quit: f
You caught a Swordfish!
Enter 'f' to fish, 'i' to display inventory, 'q' to quit: i

Inventory:
- Shark
- Lobster
- Herring
- Tuna
- Swordfish

Enter 'f' to fish, 'i' to display inventory, 'q' to quit: q
*****************************************************************
*                      Thanks for playing!                      *
*****************************************************************
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
