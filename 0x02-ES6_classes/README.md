0. You used to attend a place like this at some point
Implement a class named ClassRoom:

Prototype: export default class ClassRoom
It should accept one attribute named maxStudentsSize (Number) and assigned to _maxStudentsSize
1. Let's make some classrooms
Import the ClassRoom class from 0-classroom.js.

Implement a function named initializeRooms. It should return an array of 3 ClassRoom objects with the sizes 19, 20, and 34 (in this order).
.
.
.
10. Vroom
Implement a class named Car:

Constructor attributes:
brand (String)
motor (String)
color (String)
Each attribute must be stored in an “underscore” attribute version (ex: name is stored in _name)
Add a method named cloneCar. This method should return a new object of the class.
11. EVCar
Import Car from 10-car.js.

Implement a class named EVCar that extends the Car class:

Constructor attributes:
brand (String)
motor (String)
color (String)
range (String)
Each attribute must be stored in an “underscore” attribute version (ex: name is stored in _name)
For privacy reasons, when cloneCar is called on a EVCar object, the object returned should be an instance of Car instead of EVCar.
