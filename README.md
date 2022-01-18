# IOS-01

import UIKit

var greeting = "Hello, playground"
print("Hi",10,12.25)// Comma separated gives a space in the o/p
//String Interpolation
//\(variableName)
var name = "Murali"
var grade = 89.92;
print("Hello, \(name) your grade is \(grade)")

var proLan = "Swift";
print("I like the \(proLan) programming language")

var age = 23
print("You are \(age) years old and in another \(age) years, you will be \(age * 2)")

print("""
Hello
World!
Murali
pavan
""")
//carraige return
print ("Hello All,\rWelcome to Swift programming")

print("Welcome to Swift Programming")
print("Fall 2021")
print("*************")

print("Welcome to Swift Programming" , terminator : ":-" )//In order to get in a same line use terminator
print("Fall 2021")

print("The list of numbers are ", terminator:"=")
print(1,2,3,4,5,6)
print("The new pattern is ",terminator:"---")
print(1,2,3,4,5,6, separator: "-")//separates with -//if we don't specify separator the delimeter is space by default.
let  welcomeMessage = "Hello!"
  print(welcomeMessage , "All")

var mobileBrand = "Apple"
mobileBrand = "Samsung"
print(mobileBrand)

var age1 : Double = 23
age1 = age1 * 2
print(age1)

var aweMessage = "This is Superb!"
print(aweMessage)
print("aweMessage")

var course1 = "iOS"
var course2 = "Java"
print(course1,course2)
print(course1,"-",course2)

var httpError  = (errorCode : 404  , errorMessage : "Page Not Found")
print(httpError)
print(httpError.errorCode , terminator : ": ")
print(httpError.errorMessage )

var name1 = ("John","Smith")
var fName = name1.0
var lName = name1.1
print(fName , terminator : ",")
print(lName)

var origin = (x : 0 , y : 0)
var point = origin
print(point)

let city = (name : "Maryville" , population : "11,000")
let ( cityName ,cityPopulation ) = (city.0 , city.1)
print(cityName)
print(cityPopulation)

let groceries = ("bread","onions",40,40.0)
print(groceries.0)
print(groceries.1)
print(type(of: groceries))

var fname = "Joe"
var lname = "Root"
(fname , lname) = (lname , fname)
print("First Name is \(fname) and Last Name is \(lname)")
print()
var cricketKit = ("handGloves" ,"helmet",("bat","ball"))
print(cricketKit)
print(cricketKit.0)
print(cricketKit.1)
print(cricketKit.2.0)
print(cricketKit.2.1)
