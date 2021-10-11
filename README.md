# Capstone: Restaurant Reservation System

 You have been hired as a full stack developer at _Periodic Tables_, a startup that is creating a reservation system for fine dining restaurants.
 The software is used only by restaurant personnel when a customer calls to request a reservation.
> At this point, the customers will not access the system online.

Endpoints /dashboard?date (shows reservations)
/reservations (redirected to dashboard)
GET /reservations?dates (redirected to dashboard)
POST /reservations/new (create new reservations)
POST /tables/new (assign table)
POST /reservations/:reservation_id/seat (check available tables)
PUT /tables/:table_id/seat (match reservation_id to table_id)
PUT /reservations/:reservation_id/status (set status of table)
/search GET /reservations?mobile (find reservations by mobile)
PUT /reservations/:reservation_id/edit (edit reservation)

Dashboard the home page

dashboard Dashboard with Reservation thedashandres New Reservation Create newReservation Reservation Search resnotfound Finish Seat Message withreservation

Summary A tool for restaurant managers to create and edit reservations. Keep a record of all reservations made along with the date, time, name, mobile #, and any other information you may like to add. Easily manage tables by checking on their status whether they are occupied, free or finished. Reservations can be found quickly by using a customers mobile number. While creating reservations, validations are put into place so a customer can only make reservations based on the criteria.

Technology HTML, CSS, Javascript, React Node.js and Express installation run npm install in root folder run npm install in front-end and back-end subfolders run heroku open -a s-r-r-client Alt text

## Installation

1. Fork and clone this repository.
env` file unless you want to connect to a backend at a location other than `http://localhost:5000`.
1. Run `npm install` to install project dependencies.
1. Run `npm run start to start your server in development mode.




