# Command Line Arguments

This section will guide you through inserting command line parameters to your IDE. Program arguments are passed when you want to give specific information to your program during runtime. Environment variables are passed to set system-wide configuration or to store sensitive information.


Before you start, make sure that you have your project open.

## How to Add Program Arguments:
1. From the main menu, select **Run | Edit Configurations**.

![Edit Configurations](./images/command/edit_config.png){ width=700 }
<br>
2. In the Run/Debug Configurations dialog that appears, select which configuration you want to pass the arguments.
![Edit Configurations](./images/command/configurations.png){ width=700 }
<br>
3. In the **Parameters** or **Program arguments** textbox (depends on your configuration), add the arguments in question. (For ex: sample.txt).  

!!! warning
    If you have multiple arguments, separate them with spaces.

![Parameters](./images/command/23.png){ width=700 }
<br>
4. Click on "Apply".
<br>
5. Click on "OK".

!!! success
    If you are able to successfully pass the program arguments to your code, you should get output without any error messages.
    ![Parameters](./images/command/sum23.png){ width=700 }

!!! failure
    If you get error messages, it means that the program arguments were unable to be successfully passed to your code.
    ![Parameters](./images/command/error.png){ width=700 }

## How to Add Environment Variables:

1. From the main menu, select **Run | Edit Configurations**.

![Edit Configurations](./images/command/edit_config.png){ width=700 }
<br>
2. In the Run/Debug Configurations dialog that appears, select which configuration you want to add the environment variables.
![Edit Configurations](./images/command/configurations.png){ width=700 }
<br>
3. Scroll down until you see the **Environment Variables** textbox.
<br>
4. Enter the variable name and value: `<name>=<value>`. 
!!! warning
    If you have multiple variables, separate them with semicolons.

![Environment Variables](./images/command/env_variables.png){ width=700 }
<br>
4. Click on "Apply".
<br>
5. Click on "OK".




## Conclusion

At the end of this section, you should now know how to:

- [x] Add program arguments
- [x] Add environment variables

