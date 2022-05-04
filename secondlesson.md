# Object-Oriented Programming
In programming it is importand to work with data, so we have to make some structure to control it

In this case we will see an introduction to objects and classes, I hope you can enjoy it

Let's start creating an Array

```sh
let list = [2, 3, 5, 7, 11]
```
Once we create a list od number we can work with this list:
You can choose the one number inside the array

```sh
console.log(list[2])
```

Notice that if you execte the before code you will see in the ouput the numer "5"... That's weird isn't it?
What happen? We can see that the second place in the list is the number 3 not the number 5, this have a reason
In Every single list the first positon in not the number 1, instead the fist position is the number 0, so we start in 0
That's why we the second place in our list is the number 5

Let's see what happen if que print the position number 0 

```sh
console.log(list[0])
```
You will see in your bash the next ooutput 

```sh
2
```

Now we can can do some operation with our list, let's try this:

```sh
console.log(list[2 - 1])
```
This is pretty exeting but...
We have a problem, we can always represent our datas in arrays, that's why exist Object
The objects is a collection of propeties that we want to work

Let's create an object 

```sh
let student = {
    name : "Miguel",
    lastName: "Trujullo",
    Subjects: ["math", "machanics", "Biology", "Electronics"],
}
```
Notice something pretty interesthing, we are using an real object from the real world to medel the information, let's try another examples

```sh
let car = {
    color: "red",
    year: "2015",
    high: 1
}
```

Now that we create an object we can use for different porpuses

```sh
console.log(student.name)
console.log(student.lastName)
console.log(car.color)
```
Look that we can use o obtain diffent datas from our object
