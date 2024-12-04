# UML Use Case Diagram for Ride-Hailing Application

## System Description
This UML Use Case Diagram represents a Ride-Hailing Application designed to connect passengers and drivers. The system enables passengers to book rides,
drivers to manage and complete rides, and administrators to oversee operations and handle escalations.

## Actors and Responsibilities
1. **Passenger**:
   - Book rides based on location and destination.
   - Cancel bookings when necessary.
   - Track ride progress in real-time.
   - Rate drivers after the ride.

2. **Driver**:
   - Accept ride requests and view trip details.
   - Update ride status (e.g., started, completed).
   - View earnings and manage trip history.

3. **Administrator**:
   - Monitor ride operations and resolve disputes.
   - Manage profiles of both passengers and drivers.
   - Handle complaints and feedback.

4. **System**:
   - Authenticate users during login and registration.
   - Process payments securely for completed rides.
   - Send notifications for ride updates and confirmations.

## Use Cases
1. **Book Ride**:
   - **Actor**: Passenger
   - **Description**: Passengers can request rides by providing their location and destination.

2. **Cancel Ride**:
   - **Actor**: Passenger, Driver
   - **Description**: Allows passengers or drivers to cancel a ride before it begins or during the waiting period.

3. **Track Ride**:
   - **Actor**: Passenger
   - **Description**: Enables passengers to view the driver's location and monitor the trip's progress in real time.

4. **Rate Driver**:
   - **Actor**: Passenger
   - **Description**: Passengers can provide feedback and rate drivers after completing a ride.

5. **Accept Ride**:
   - **Actor**: Driver
   - **Description**: Drivers can accept a passenger's ride request and receive trip details.

6. **Update Ride Status**:
   - **Actor**: Driver
   - **Description**: Drivers can mark the ride status as "started," "completed," or "canceled."

7. **View Earnings**:
   - **Actor**: Driver
   - **Description**: Drivers can review their earnings for completed rides and access their trip history.

8. **Manage Profiles**:
   - **Actor**: Administrator
   - **Description**: Administrators oversee the creation, editing, and deactivation of passenger and driver accounts.

9. **Handle Complaints**:
   - **Actor**: Administrator
   - **Description**: Administrators address issues raised by passengers or drivers to ensure smooth operations.

10. **Authenticate Users**:
    - **Actor**: System
    - **Description**: Validates user credentials during login and registration for security.

11. **Process Payments**:
    - **Actor**: System
    - **Description**: Handles payment transactions securely after the ride is completed.

12. **Notify Users**:
    - **Actor**: System
    - **Description**: Sends updates and confirmations for ride status and payments.
