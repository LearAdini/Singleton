# Singleton Clock 
A Singleton clock that will show an instance number increasing every 1 second.

# The Class
First I create a class called SingleTonClock and give it its properties.
The prop instance will be the class itself and will be used to get the iteration instance number, later.
The counter prop will return the instance number and when its created.
And in the constractor I set numOfInstance to 0.
![0](https://user-images.githubusercontent.com/80118008/129447564-5ff11f56-e7cb-454d-b521-3c8c75455826.PNG)

# Methods
**● GetInstance**

Starting with the first method I create GetInstance and say if instance is null start lock on instance which is the new instance of type SingleTonClock , and set numOfInstance++ to get increasing number for each iteration, return instanace number.
![4](https://user-images.githubusercontent.com/80118008/129447618-280c78aa-dde2-4e67-a378-c5fdb2366533.PNG)

**● tonClock**

Now I set the tonClock method which will run in a constant loop while (true) and give it a Thread.Sleep of one second.
So now I define a variable type of SingleTonClock and use GetInstance method.And write to the screen the Clock instance number wich will increase each second and will show us when it was created(Counter prop)
![1](https://user-images.githubusercontent.com/80118008/129447613-19005f70-d9c2-4a0d-99c9-ac72c71b3df3.PNG)
# Main
In main I define a variable called s1 which will be my Singleton clock and I will use the tonClock method
![2](https://user-images.githubusercontent.com/80118008/129447659-00ac876c-1a28-452b-bb86-c1088829d331.PNG)
# Result
![3](https://user-images.githubusercontent.com/80118008/129447667-3d1c19e8-8c8f-495c-842c-43c98b2ad915.PNG)
