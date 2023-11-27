# AutoHub

AutoHub is a Java-based application that centralizes workshops for users to interact with. The application is built using the JavaFX library for the front end and leverages the Google Maps API for location detection.

## Features

- **Workshop Centralization:** AutoHub provides a centralized platform for users to explore and interact with various workshops.

- **JavaFX Front End:** The user interface is developed using JavaFX, offering a rich and interactive experience.

- **Google Maps Integration:** AutoHub utilizes the Google Maps API to enable location detection, providing users with a seamless experience in finding workshops based on their geographical location.

## Prerequisites

Make sure you have the following installed before running the application:

- Java Development Kit (JDK)
- JavaFX
- Google Maps API Key (Instructions on obtaining one: [Google Maps Platform Documentation](https://developers.google.com/maps/gmp-get-started))

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/AutoHub.git
    ```

2. Navigate to the project directory:

    ```bash
    cd AutoHub
    ```

3. Build and run the application:

    ```bash
    ./gradlew run
    ```

4. Enter your Google Maps API Key when prompted.

## Usage

- Upon launching the application, users can explore available workshops and interact with the interface to find relevant information.

- Make sure to allow location access for accurate workshop suggestions based on the user's location.
#### General features 
Implemented Features
- `make appointments`
- `search based on services needed`
- `search based on parts needed`
- `appointment history`
- `show nearest workshops`
- `get realtime location using Google API`
- `real time navigation to the workshop from the user`
- `workshops can maintain a detailed service history`

Future planned Features
- `home delivery service`
- `emergency service`
- `review and rating`


## Demonstration

#### Sign up as user 
<img width="505" alt="Screenshot 2023-11-27 162818" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/d6bca107-6938-45ac-8590-919b2faa9274">
<img width="453" alt="Screenshot 2023-11-27 162556" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/563e6ede-5f96-434b-8c5a-938c557355cb">


#### Sign up as workshop
<img width="452" alt="Screenshot 2023-11-27 162629" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/99950af1-bb85-49d0-917a-d8a5348203c0">
<img width="454" alt="Screenshot 2023-11-27 162614" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/1e2cd698-dd3d-49a4-9125-39953f0456d2">

**The workshop can set their location in 2 ways:**
 1. `Automatically using real time location`
 2. `Manually set by the workshop admin`
<img width="454" alt="Screenshot 2023-11-27 162446" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/8a185a84-c6b1-4e00-add0-e292995f9471">

#### Adding parts and services by workshop
<img width="462" alt="Screenshot 2023-11-27 162733" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/9000d619-d8f5-439d-b46b-7d54ccf91ead">
<img width="451" alt="Screenshot 2023-11-27 162748" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/1dce8176-d89b-4bf2-abcb-b34a884a9111">


#### Creating Appointments
1. **From the listed nearby workshops appointments can be made**
2. They can see their real time location on the map
3. Real time route(cycling,driving etc) can be seen of the nearest workshop

<img width="452" alt="Screenshot 2023-11-27 162837" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/1487ac33-99f9-42a7-a9b9-11e9f82c8039">
<img width="452" alt="Screenshot 2023-11-27 162533" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/0713618f-f12a-4e7f-a005-fff0e2870347">


#### Accepting appointments

Marking the appointment as completed which was done in the previous portion. The starting and the ending time was updated here.

<img width="150" alt="Screenshot 2023-11-28 003815" src="https://github.com/ahmedshihab809/Auto-Doctors-JAVAFX/assets/57572719/56ace7b0-dae0-4420-afc6-b321ff3de11b">



## Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- [JavaFX Documentation](https://openjfx.io/)
- [Google Maps Platform Documentation](https://developers.google.com/maps/documentation)

---
