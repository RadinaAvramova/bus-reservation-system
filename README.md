# Bus Reservation System
Welcome to the Bus Reservation System project! This C++ application is designed to manage bus reservations, including booking seats, tracking passenger information, and generating tickets. With this system, bus operators can efficiently manage their fleet, streamline the reservation process, and provide a seamless experience for passengers.

## Features
1. **Seat Reservation:** Allows passengers to reserve seats on available buses by selecting the desired date, time, origin, destination, and seat preference.

2. **Passenger Information:** Captures and stores passenger information such as name, contact details, and identification for each reservation, ensuring accurate record-keeping and communication.

3. **Ticket Generation:** Generates tickets for confirmed reservations, including ticket number, passenger details, seat number, bus details, and travel itinerary.

4. **Seat Availability Checking:** Checks seat availability on buses for specific dates, times, routes, and seat preferences, allowing passengers to make informed reservation decisions.

5. **Cancellation and Refunds:** Provides functionality for passengers to cancel reservations and process refunds according to predefined cancellation policies and procedures.

6. **Reporting and Analytics:** Generates reports and analytics on reservation trends, seat occupancy, revenue, and other key performance indicators (KPIs) to support decision-making and business analysis.

## Installation
To set up the Bus Reservation System:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/bus-reservation-system.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd bus-reservation-system

3. **Compile the Code:** Compile the C++ source files using a C++ compiler (e.g., g++, clang++):

g++ -o bus_reservation main.cpp bus.cpp reservation.cpp ticket.cpp

4. **Run the Application:** Execute the compiled executable file to start the application:

./bus_reservation

## Usage
1. **Search Buses:** Users can search for available buses by specifying the desired date, time, origin, destination, and seat preference.

2. **Select Seats:** Users can select available seats on buses and proceed with the reservation process by providing passenger information.

3. **Generate Tickets:** The system generates tickets for confirmed reservations, including ticket number, passenger details, seat number, bus details, and travel itinerary.

4. **Cancel Reservations:** Passengers can cancel reservations according to predefined cancellation policies and procedures, with options for refunds if applicable.

5. **Manage Passenger Information:** Users can manage passenger information such as name, contact details, and identification associated with each reservation.

## Customization
1. **Bus Routes and Schedules:** Customize the system to support different bus routes, schedules, and seat configurations, accommodating various service offerings and travel preferences.

2. **Reservation Policies:** Define reservation policies such as booking windows, cancellation deadlines, refund policies, and seat allocation rules to meet business requirements and regulatory standards.

3. **User Roles and Permissions:** Implement user roles and permissions to control access to certain features and data within the system, ensuring data security and privacy.
