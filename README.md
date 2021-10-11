# Capstone: Restaurant Reservation System Rainer Fronz

 You have been hired as a full stack developer at _Periodic Tables_, a startup that is creating a reservation system for fine dining restaurants.
 The software is used only by restaurant personnel when a customer calls to request a reservation.
> At this point, the customers will not access the system online.

Endpoints /dashboard?date (shows reservations)<br>
/reservations (redirected to dashboard)<br>
GET /reservations?dates (redirected to dashboard)<br>
POST /reservations/new (create new reservations)<br>
POST /tables/new (assign table)<br>
POST /reservations/:reservation_id/seat (check available tables)<br>
PUT /tables/:table_id/seat (match reservation_id to table_id)<br>
PUT /reservations/:reservation_id/status (set status of table)<br>
/search GET /reservations?mobile (find reservations by mobile)<br>
PUT /reservations/:reservation_id/edit (edit reservation)<br>


Dashboard the home page
![perTableDash](https://user-images.githubusercontent.com/65880191/136815605-1a6f81f1-8db2-4a76-9a96-3e8262896df7.jpg)
Search Reservation
![pertableSearch](https://user-images.githubusercontent.com/65880191/136815609-129d17c2-f963-41ac-b35f-4fd4eb1b8f51.jpg)
New Reservation
![perTableNewREs](https://user-images.githubusercontent.com/65880191/136815602-5f5890c9-efc4-4b92-bf9c-cff887e5efcb.jpg)
New Table
![perTabNewTable](https://user-images.githubusercontent.com/65880191/136816120-4995b77f-6cf7-4044-a14b-6b474c8c8109.jpg)


 

Summary A tool for restaurant managers to create and edit reservations. Keep a record of all reservations made along with the date, time, name, mobile #, and any other information you may like to add. Easily manage tables by checking on their status whether they are occupied, free or finished. Reservations can be found quickly by using a customers mobile number. While creating reservations, validations are put into place so a customer can only make reservations based on the criteria.

Technology HTML, CSS, Javascript, React Node.js and Express installation run npm install in root folder run npm install in front-end and back-end subfolders run heroku open -a s-r-r-client Alt text

## Installation

1. Fork and clone this repository.
env` file unless you want to connect to a backend at a location other than `http://localhost:5000`.
1. Run `npm install` to install project dependencies.
1. Run `npm run start to start your server in development mode.




