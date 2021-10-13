![Screen Shot 2021-10-07 at 12 50 17 PM](https://user-images.githubusercontent.com/10773482/136432896-def73172-8cb3-44e0-abcd-28e403a44cc3.png)

## Questions 1 - 5 are worth 10 points eachwhile question 6 is worth 50 points

## ShopLifters is a Class NOT Abstract

Question 1 
- Write a method that returns the remainder of the following equation:  118 ÷ 31

Question 2 
- Create an array with these numbers  inside main  [10, 3, 4, 67]
- Create a static method outside main that grabs the second and third elements in the array then add them together. Finally multiply the result of adding the numbers together by the first element in the array. Make sure to invoke/call your function to ensure it works.

Question 3 
- Use a for loop to print each value in this array [4,5,6]  except the last element in the array.
- Use while loop to square every element in the same array [4,5,6] 
-  Write a test case for the second bullet point

Question 4 
- Create an ArrayList with the names of all the students in the class then use a loop to print out all their names. 
- Create a Person class with two private instance variables name and age
- Now modify your previous arraylist that contained just student names to now contain Students (Student Objects). Then modify the loop to print each student’s name and age


Question 5 
- Write a program that keeps asking (prompting) a user to enter their name. If the name the user enter’s is “Hakeem” then print out “Welcome Hakeem” or If the name the user enter’s is “Aliyah” then print out “Welcome Aliyah”. However, if the name the user entered is NOT Hakeem or Aliyah..then keep asking(prompting) the user to enter a name until they enter either hakeem or Aliyah. One more thing...It should not matter if  the user enters either Hakeem or Aliyah in lower, Upper or camel case letters. Eg: hAkeEm is still valid as Hakeem. 




Question 6
- Use the UML to answer the following questions


   ## Leverage the 3 Clothing objects sample data below

        Clothing jeans = new Clothing("Blue Jeans", 20.0, Size.M);
        Clothing tShirt = new Clothing("White T Shirt", 5.0,Size.S);
        Clothing buttonUp = new Clothing("Button Up Shirt", 30.0, Size.L);
      

  - Create a managerCart array which contains all three clothing objects.

  - Create a manager object and Give manage a size of Small.

  - Create an hourlyEmployeeCart array which contains all three clothing objects

  - Create an hourly employee object and Give manage a size of Large.

  - Use the Shop App to Check and print the total of your manager's cart

  - Check if the jeans fits the hourly Employee

  - Print the hourlyEmployee's price after discounts on a clothing item of your choice.

  - Print the manager's price after discounts on the same clothing item you discounted for the hourly employee

  - Create an studentCart array which contains all three clothing objects

  - Create a student object with an id 0f 001, and a size of Medium the student's price
     
  - Print Just the student's discount off the same clothing item
    
  - Invoke the printCustomerName method on each Customer object to print out their names, one at a time.
  - Create an arraylist of clothing items
  - Use the sortAndPrintClothingItemsByPrice to sort them by price
  - Invoke the printDiscountAmountOff method to print out the discount amount off a pair of Button Up Shirt for every type of person that gets a discount even if the discount is zero!!!





### Sample Expected outcome for ShopApp
<pre>
55.0
false
4.5
4.25
0.25
James
Mike
Lewis
Clothing{description='White T Shirt', price=5.0, size=S}
Clothing{description='Blue Jeans', price=20.0, size=M}
Clothing{description='Button Up Shirt', price=30.0, size=L}
1.5
3.0
4.500000000000001
0.0
</pre>

