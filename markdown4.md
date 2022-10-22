# Summary of Project and Degree

![alt text](https://cdn.nrf.com/sites/default/files/styles/crop_1440_700/public/2021-03/shutterstock_658847998.jpg?itok=S6aLTAcl)

To conclude the **Information Technology** degree offered at Mizzou is a lot more than what it sounds like at a surface level. When I heard IT in the past my mind went to a person sitting in an office at a school offering help to teachers with projector problems but its so much more. The degree gives students the tools required to create anything they can think of when it comes to software. Here are just some of the possible things a student could create through the _Mizzou IT program_.
- Websites
- Graphics
- IOS applications
- Android applications
- Software development
- Projects like this
- and more!

On top of the multiple possible outlets to utilize the skills learned in school, almost every career in the above categories comes with a starting salary of at least **$60,000**. Not only will you enjoy what you do, you'll get payed well to do it! The best place to find information related to the degree is [Mizzou IT Info site](https://catalog.missouri.edu/collegeofengineering/informationtechnology/). [Markdown1](https://github.com/jakesimpkins/midtermProject/blob/main/markdown1.md), [Markdown2](https://github.com/jakesimpkins/midtermProject/blob/main/markdown2.md), and [Markdown3](https://github.com/jakesimpkins/midtermProject/blob/main/markdown3.md) also give good information about the degree as whole and the focuses within it. Below is an image that shows the core required classes for any student looking to major in IT at Mizzou as well as an example code of one of my favorite projects we have done so far.

![alt text](https://user-images.githubusercontent.com/112040527/197308164-1db1b525-a65c-4f7e-9fb7-dbc75faec309.png)

```
givenList = [6, 5, 3, 8, 4, 2, 5, 4, 11, 43, 1, 17, 27, 90, 77, 62, 51, 47, 82, 86, 20]

totalNumbers = len(givenList)

listPosition = 0
listTotal = 0

for i in range(len(givenList)):
    listTotal += givenList[listPosition]
    listPosition += 1

listAve = listTotal/len(givenList)

print("There are ", totalNumbers, " total numbers in the list.", '\n')
print("The total of all of the numbers in the list is: ", listTotal, '\n')
print("The average of the list is: ", listAve, '\n')

print('Printing every list items place and value:')
txt = "List item {}:"
listPosition = 0
while listPosition < len(givenList):
    print(txt.format(listPosition), givenList[listPosition])
    listPosition += 1

print('\n')
print('Printing every other list items place and value:')
listPlace = 0
for i in range(11):
    print(txt.format(listPlace), givenList[listPlace])
    listPlace += 2

print('\n')
print('Bonus: Printing whether each number is even or odd:')
evenTxt = "{} is even"
oddTxt = "{} is odd"
listSpot = 0
for i in range(len(givenList)):
    if givenList[listSpot] % 2 == 0:
        print(evenTxt.format(givenList[listSpot]))
    else:
        print(oddTxt.format(givenList[listSpot]))
    listSpot += 1
```
