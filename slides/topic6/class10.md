# Add method

```py
# a parent class
class Vehicle():
    def description(self):
        print("I'm a Vehicle")
# subclass
class Car(Vehicle):
    def description(self):
        print("I'm a car")
    def setSpeed(self, speed):
        print("Now traveling at", speed,"miles per hour")    
# create an object from each class
v = Vehicle()
c = Car()
c.setSpeed(25)
# Prints Now traveling at 25 miles per hour
v.setSpeed(25)
# Triggers AttributeError: 'Vehicle' object has no attribute 'setSpeed'
```