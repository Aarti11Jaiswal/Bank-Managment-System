Bank Application
1. Login
    Take account number as an input 
    If account number exits in your data then take password as an input
    Match whether the password which users enter is same as in data
    If password get matched provide these options
        a. Credit
        b. Debit
            Balance --> 1000, debit --> 2000 (Insufficient Balance)
        c. Check Balance
        d. Change Password
            take old password as input from user
            check whether the password is correct or not
            if the old password is correct the ask for newpassword (update the oldpassword
            with password)
            else show the message that the password is wrong. 
        e. Show details
        f. Logout
            Show all above options till it logout
    Else show him that invalid password
2. Signup
    Register new user 
    Take the following as input from user and store it into the data  
        name
        password
        initial balance
            (initial balance should be atlease INR 1000)
        You have to generate an account number (in serial order) and make entry of that
        account number in the data 
        1005 --> (inform user its account number)

3. Forgot Password
        Take account number as a input 
        Take security question as input
        if accno and security question both are correct then change password
        else do not
4. Exit
    These 4 options should be present untill user does not exit...
