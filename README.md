# Smart-Home

A Java-based project demonstrating Object-Oriented Programming (OOP) principles and JUnit testing skills through the implementation of a smart home system. The project features three smart devices and comprehensive test cases to ensure reliability and functionality.

## Features

- **Smart Devices:** Integrates three smart devices within a simulated smart home environment: SmartTV, SmartThermostat, and SmartSpeakers.
- **Interfaces:** Implements key interfaces like `AudioControl`, `PowerControl`, `NetworkControl`, and `TemperatureControl` to demonstrate modularity and abstraction.
- **JUnit Testing:** Comprehensive test cases written using JUnit to validate functionality and ensure robustness.

## Project Structure

```
Smart-Home/
├── src/
│   ├── devices/
│   │   ├── SmartDevice.java
│   │   ├── SmartTV.java
│   │   ├── SmartThermostat.java
│   │   └── SmartSpeakers.java
│   ├── interfaces/
│   │   ├── AudioControl.java
│   │   ├── PowerControl.java
│   │   ├── NetworkControl.java
│   │   └── TemperatureControl.java
│   ├── Main.java
│   └── utils/
│       └── DeviceManager.java
├── test/
│   ├── devices/
│   │   ├── SmartTVTest.java
│   │   ├── SmartThermostatTest.java
│   │   └── SmartSpeakersTest.java
│   └── utils/
│       └── DeviceManagerTest.java
├── README.md
└── build/
```

## Key Components

- **`SmartDevice.java`:** Base class for all smart devices.
- **`SmartTV.java`, `SmartThermostat.java`, `SmartSpeakers.java`:** Individual implementations of smart devices.
- **Interfaces:**
  - **`AudioControl.java`:** Handles audio-related functionalities.
  - **`PowerControl.java`:** Manages power operations for devices.
  - **`NetworkControl.java`:** Provides network connectivity features.
  - **`TemperatureControl.java`:** Controls temperature settings for relevant devices.
- **`DeviceManager.java`:** Utility class to manage the devices.
- **`Main.java`:** Entry point for the application.
- **Test Classes:** Comprehensive unit tests for each device and the `DeviceManager`.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- JUnit 5
- IDE or text editor for Java development (e.g., IntelliJ IDEA, Eclipse, or Visual Studio Code)

### Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Open the project in your preferred IDE.

3. Build and run the project using your IDE or command line.

4. Execute tests with JUnit to verify functionality.

## Usage

1. Run `Main.java` to simulate the smart home system.
2. Manage and control smart devices using the console-based interface.
3. Run JUnit test cases to validate the implementation.

## OOP Principles Demonstrated

- **Encapsulation:** Secure device data and provide controlled access.
- **Inheritance:** Common properties and behaviors defined in the `SmartDevice` base class.
- **Polymorphism:** Device-specific functionality implemented in subclasses.

## Future Enhancements

- Add more smart devices (e.g., Smart Doorbell, Smart Vacuum Cleaner).
- Implement a GUI for better user interaction.
- Integrate with IoT platforms for real-world simulation.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the [MIT License](LICENSE).
