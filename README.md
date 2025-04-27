# AppDev_Lab-7_PHP
## Challenge 1 -> total of 20pts

1. Create a class called `BankTransaction` that has the following properties: (2pts)

- `bank_name`    note: example  BDO
- `transaction`  note: the value for this is 'D' for deposit or 'W' for withdraw
- `account_no`   note: example ACN0000001
- `amount`       note: the value for this is the amount to deposit or to withdraw
- `savings_amount` note: Balance amount money savings.

2. The `account_no` `amount` and savings_amount property should be `private`. And savings_amount  default is 10000. (2pts)

3. Create a constructor that takes in the bank_name,transaction,account_no and amount as arguments and sets the values of the properties. (3pts)

4. Create a method called `getInfo` that will show the following: (3pts)

   Bank Name: BDO
   Customer Account No: ACNO0000001
   Type of Transaction: W
   Current Balance: 10000
   Amount: 3000


5. Create a method called `newBalance` that returns the new balance after  deposit or withdraw (4pts)

6. Create 3 new instances/objects of the `BankTransaction` class and call the `getInfo`  and `newBalance` method (5pts)


**Sample Output:**
```
Object: customer1

Bank Name: BDO
Customer Account No: ACNO0000001
Type of Transaction: W
Current Balance: 10000
Amount: 3000
New Balance: 7000

Object customer2

Bank Name: BPI
Customer Account No: ACNO0000002
Type of Transaction: D
Current Balance: 10000
Amount: 3000
New Balance: 13000

Object customer3

Bank Name: METROBANK
Customer Account No: ACNO0000003
Type of Transaction: AB
Current Balance: 10000
Amount: 3000
Unable to process this transaction! Invalid Transaction type!
```

## Challenge 2 -> total of 15pts
1. Create a class called `StringUtility` that has the following static methods:

- `shout($string)` - Takes in a string and returns it in all uppercase letters with an exclamation mark added to the end. 3pts

- `whisper($string)` - Takes in a string and returns it in all lowercase letters with a period added to the end. 3pts

- `repeat($string, $times)` - Takes in a string and a number and returns the string repeated the specified number of times. Use a default value of `2` for the `$times` parameter. 4pts

2. Create a new instance of the `StringUtility` class and call each of the methods on it. 5pts

#### Hints

- You can use the `strtoupper` and `strtolower` functions to convert a string to uppercase or lowercase.
- You can use the `str_repeat` function to repeat a string a certain number of times.


ex.

shout('Hello World'); <br>
whisper('Hello World'); <br>
repeat('Hello World'); //default is 2x <br>
repeat('Hello World',5); <br>
     
**Sample output:**
```
HELLO WORLD
hello world
Hello World Hello World
Hello World Hello World Hello World Hello World Hello World
```
