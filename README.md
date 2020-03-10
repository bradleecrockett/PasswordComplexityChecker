# PasswordComplexityChecker

![password strength](images/password_strength.png)

Your task is to create a program that tests to determine whether a password is complex or not.
A password is considered complex if it is **at least 8 characters long** and meets at least 3
of the next 5 requirements.

1) Contains a lowercase character
2) Contains an uppercase character
3) Contains a digit: 0 - 9
4) Contains a special character: !@#$%^&*()-=_+[]\{}|;'<>?,./
5) Is at least 14 characters long

## Program Requirements
The program should read in passwords one per line and print **Complex:** or **Not Complex:**, then the password that was evaluated.  
The last line of input will be a single . period. 
This can be done with a simple input() command.
The 

### Sample Inputs and Outputs
Input 1:

    password123
    letmein
    LetM3!nN0w
    CorrectHorseBatteryStaple
    .

Output 1:

    Not Complex: password123
    Not Complex: letmein
    Complex: LetM3!nN0w
    Complex: CorrectHorseBatteryStaple
    
    
Input 2:

    nope
    SlimyHamDogOrigami
    .

Output 2:

    Not Complex: nope
    Complex: SlimyHamDogOrigami
    
Input 3:
    
    P@ssw0rd123
    aA&4
    Tr'ckyN"ck
    1forthe$
    12345678
    .

Output 3:

    Complex: P@ssw0rd123
    Not Complex: aA&4
    Complex: Tr'ckyN"ck
    Complex: 1forthe$
    Not Complex: 12345678
    .