# Car Showroom GUI

This project is a Java Swing-based GUI application for a Car Showroom. The application allows users to view car details, book cars, view booking details, and book various services.

## Features

- **Car Details**:
  - Display information about available cars (make, model, engine, mileage, and price).
  - Allows users to book a car and save their booking details.

- **Booking Details**:
  - View all car booking details.
  - Displays car, customer name, and mobile number.

- **Services**:
  - Display available services such as car washing, engine service, spare parts, and oil change.
  - Allows users to book a service and save their booking details.

- **Service Details**:
  - View all service booking details.
  - Displays service, customer name, mobile number, and car.

## Prerequisites

- Java Development Kit (JDK) 8 or above
- Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or NetBeans (optional)

## Getting Started

### 1. Clone the Repository
Clone the project repository to your local machine:
```bash
git clone https://github.com/your-repo/car-showroom-gui.git
```

### 2. Compile the Code
Navigate to the project directory and compile the Java file:
```bash
javac CarShowroomGUI.java
```

### 3. Run the Application
Run the compiled Java file:
```bash
java CarShowroomGUI
```

## How to Use

1. **Car Details**:
   - Click on the "Show Car Details" button to view available cars.
   - Click the "Book" button for a car, enter your name and mobile number, and save the booking.

2. **Booking Details**:
   - Click on the "Show Booking Details" button to view all car bookings.

3. **Services**:
   - Click on the "Services" button to view available services.
   - Click the "Book Service" button, enter your name, mobile number, and car details, and save the booking.

4. **Service Details**:
   - Click on the "Show Service Details" button to view all service bookings.

## Project Structure

```
CarShowroomGUI.java    # Main Java file containing the GUI implementation
```

## Code Highlights

- **Swing Components**:
  - Used `JLabel`, `JButton`, `JTable`, `JPanel`, and `JScrollPane` for creating the GUI.
  - `ActionListener` is implemented for handling button actions.

- **Data Management**:
  - `ArrayList` is used to store booking details for cars and services.

- **Custom Dialogs**:
  - `JOptionPane` is used for collecting user input and displaying messages.

## Screenshots

### Main Window
![Main Window](https://example.com/screenshot-main.png)

### Car Details
![Car Details](https://example.com/screenshot-car-details.png)

### Services
![Services](https://example.com/screenshot-services.png)

## Future Enhancements

- Connect the application to a database for persistent data storage.
- Add authentication and user management features.
- Enhance the UI with modern design frameworks like JavaFX.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or suggestions, please contact:

- **Name**: Darshan Pradeepkumar Chouthayi
- **Email**: darshanchouthai@gmail.com
