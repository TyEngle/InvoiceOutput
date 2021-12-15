# Sprint-Final-TylerEngle
QAP 5 assignment along with OSICDef.dat and Policies.dat datafile.
OSICDef.dat holds all the default values for the constants used in the program.
Policies.dat will store the information from the policies that have been input by the user. 
Program for One Stop Insurance Company-a car rental business which offers different insurance types on their vehicles.
The program first reads the values from the OSICDefaults data file and asks for the user to input the customer's info.
The program then prints out the customer's reciept based on the information the user has input into the program.
At this point the program will overwrite the values in the OSICDefaults data file(Usually just the next policy number to be used, uness the user changes any of the constants) and append the customer's info into the next line of the Policies datafile.
The program will display a message stating that the information has been saved.
The program then asks if the user wants to continue using program, basically asking if they want to do out another policy.
When the user says no to continuing use, the program will then print out two reports based on any policies that were created for that date(currentdate).
First report is based on all insurance policies created today.
Second report is based on all insurance policies in which the customer has chosen to pay via monthly payments.
