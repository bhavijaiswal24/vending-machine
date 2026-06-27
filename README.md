# Vending Machine System

A console-based Vending Machine application developed in Java using Object-Oriented Programming (OOP) principles. The system simulates the functionality of a real-world vending machine, including item selection, coin insertion, inventory management, and product dispensing.

## Features

- Display available products
- Select and purchase items
- Accept multiple coin denominations
- Inventory management
- Dispense selected product
- Return change after purchase
- Handle insufficient balance and out-of-stock scenarios

## Technologies Used

- Java
- Object-Oriented Programming (OOP)

## Project Structure

```
vending-machine/
│
├── src/
│   ├── coin/              # Coin-related classes and denominations
│   ├── inventory/         # Inventory management classes
│   ├── item/              # Product/item classes
│   ├── vendingmachine/    # Core vending machine logic
│   ├── App.java           # Main entry point
```

## OOP Concepts Used

- Classes and Objects
- Encapsulation
- Abstraction
- Composition
- Modular Design

## Functionalities

- User can view all available products.
- User can select a product for purchase.
- System validates item availability.
- User can insert coins to make payment.
- System calculates and returns change.
- Inventory is updated automatically after a successful purchase.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/bhavijaiswal24/vending-machine.git
```

2. Navigate to the project directory:

```bash
cd vending-machine
```

3. Compile the Java files:

```bash
javac src/App.java
```

4. Run the application:

```bash
java src.App
```

## Learning Outcomes

- Gained hands-on experience in designing object-oriented systems.
- Improved understanding of Low-Level Design (LLD) concepts.
- Learned inventory management and transaction handling.
- Enhanced problem-solving skills through real-world system implementation.

## Future Enhancements

- Add support for multiple payment methods.
- Develop a graphical user interface (GUI).
- Store inventory data in a database.
- Add an admin panel for inventory updates.

## Author

**Bhavi Jaiswal**

GitHub: https://github.com/bhavijaiswal24
