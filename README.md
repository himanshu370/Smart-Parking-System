# SmartParkingSystem
Intelligent parking system that aims to simplify the parking experience by allowing users to pre-book parking spaces at specific times.The system is designed to suit multiple cities and parking lots, providing a flexible and efficient solution for users looking for a parking space.

The scheme is based on the concept of web-based parking. Each parking space is divided into a grid of slots, and each slot can be uniquely marked with x and y coordinates.

There are 3 tables first is the useres table. It stores information about users, including their unique identity, name, contact information, and any relevant resources they may have.

The other parking lot table contains information about parking locations in various cities. Each parking lot is associated with the city and represented as parking lots in the system. The table stores information such as unique parking ID, location (city), total number of parking spaces, and other relevant information. The third is the reservation table, which stores the booking infornation.

When the user wants to book a parking spot, he enters his credentials into the system. They can then search the system database for available parking spaces based on the city they are interested in. Once they have selected a parking space, they can specify their preferred start time and end time. The system will then show them which slots are available at that time.

Once the slot is selected, the user is directed to the payment gateway. Then after successful payment, the booking is added to the bookings table and receipt is generated for the user.
