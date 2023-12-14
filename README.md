# code-builder
Code compiler to create a single file to run on the server.

The idea is that the user will run build command of this project on their project folder. Then the program will go to each function of the code in the project and bring the code from the respective library into a new file. This file will have all the necessary function calls that are being used in the project. It will even have the funtions that are being used by the other functions. so all the node modules wont be required. The project size will remain small and only code actually required for the project will be in it.

Main aim of this project:
- save space occupied by node modules
- removing dependency hell.
- making the project easy to deploy since it will be just a single file which has all the code required by the project.


###### Please let me know if you have any other suggestions or ideas that can be included in this project. Thank you for stopping by.
