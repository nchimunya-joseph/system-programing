# SYSTEM PROGRAMMING PRATICAL 2023 APRIL SPRING EXAM
- Write proper documation and clean code
- The use of best practies is highly adviced
- All classes should have a:
    - Default Constructor
    - Copy Constructor
    - Custom Constractor
    - Destractor
- All Classes Should have the header file `.h` and a `.cpp`
Create a reposotory

Then
    `git clone  http://ghp_7twaU3EbdqWxJAg7D6Rt9Nt0gBghZr2CPVg5@github.com/nchimunya-joseph/construction.git`

Inside write your programs/code

- Filename
    - `system-programming_2023`
### 1. Write a program to swap two numbers using:
- pointers
- Refernces
- `file name`
    -  `0x01-pointers.cpp`
    - `0x01B-refernces.cpp`
### 2. Write a program that replaces the string `Computer` in the String "`Diploma in Computer Engineering` with string `Information Technology`.
- `file name`
    -  `0x02-str.cpp`
### 3. Define classes to appropriately represent class hierarchy as shown in below figure.
- Use constructors for both classes and display Salary for a particular employee
<img src="./img/screenshot.png">

- `file name`
    -  `0x03-employee.cpp`
    - `0x03-salary.cpp`
### 4. Define a class named ‘Train’ representing following members:
- Data members:-
    - 	Train Number
    -	Train Name
    -	Source
    -	Destination
    -	Journey Date
    -	Capacity
- Member functions:
    -	Initialise members
    -	Input Train data
    -	Display data
- Write a C++ program t test the train class.
- `file name`
    -  `0x04-train.cpp`
    - `0x04-train.h`
### 5. create a function overloading of the two functions below
```c++
 /**
  * max - finds which number is maxium between the two variables
  * @a - int variable
  * @b - int variable
  * Return - a max number between @a and @b
 */
int max(const int* a, const int* b){
    std::cout << "max with cont int* called" << std::endl;
    return (*a > *b)? *a : *b;
}

 /**
  * min - finds which number is minium between the two variables
  * @a - int variable
  * @b - int variable
  * Return - a min number between @a and @b
 */
int min(const int* const a, const int* const b){
	std::cout << "&a : " << &a << std::endl;
	std::cout << "&b : " << &b << std::endl;
    return (*a < *b)? *a : *b;
}
```
- `file name`
    -  `0x05-max.cpp`
    - `0x05B-min.cpp`

### 6. Define a class named ‘Bank Account’ to represent following members:
- Data members :-
    -	Account Number
    -	Name of Depositor
    -	Account Type
    -	Balance Amount
- Member functions:
    -	Initialize members
    -	Deposit Amount
    -	Withdraw Amount
    -	Display Balance
- Write a program to test the Bank Account class for 10 customers.
- `file name`
    -  `0x06-bank.cpp`
    - `0x06-bank.h`
### 7. Write a program that will create data file containing the list of telephone numbers as:
    John 34567
    Hari 56788
- `file name`
    -  `0x07-telephone.cpp`
    -  `0x07-telephone.txt`
### 8. Write a program to copy contents of `story_never_told.txt` to  `your_secrets_are_told.txt`
- `file name`
    -  `0x08-stories_lies.cpp`

## submission:
    please not that you will submit all your files on your repo
    The other part you will submit printable pages of your work
        - font family/font face/font name: courier
        - font size: 11pt/px
        - font spacing: remove lines
---
## Author:
- **Nchimunya Joseph M**.
- [Bio](https://nchimunya.netlify.app/)
- [Class Site](https://melzaracs.netlify.app/)
