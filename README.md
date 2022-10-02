The Solution in the Project has been provided for the problem at codeu.ai -> https://codu.ai/coding-problem/train

The Main class in the Project is TrainRoute.java.

Path -> /TrainStationsRoute/src/com/train/service/GeekTrust.java

The Model Class can be found in path -

/TrainStationsRoute/src/com/train/model/Train.java


The Input Output operation methods and their respective implementations can be found in the package -

src/com.train.io


The Constants used in the codes are defined under the package - 

src/com.train.constants






Input has to be read from a text file, and output prints to console.
The program  executes and takes location to the text file as parameter.
 
 Path to Input Test Cases Files in the project is ->
/TrainStationsRoute/resources/InputTestCase1.txt
/TrainStationsRoute/resources/InputTestCase2.txt
 
Procedure to Run the Program-

1. Compile the Program using CMD command after navigating to the src folder of the project -
   javac com/train/service/TrainRoute.java

   This creates a .CLASS file for TrainRoute.java by the name TrainRoute.CLASS, on successful compilation.

2. Run the Program now using the following command 

   java com/train/service/TrainRoute [full-file-location-on-your-system-where-text-files-are-stored]
   
   Example -> 
   				Compiling -> C:\[My_Folder]\[My_Workspace]\TrainStationsRoute\src> javac com/train/service/GeekTrust.java
   
				Running -> C:\[My_Folder]\[My_Workspace]\TrainStationsRoute\src> java com/train/service/GeekTrust C:\[My_Folder]\[My_Workspace]\TrainStationsRoute\resources\InputTestCase1.txt


INPUT -

TRAIN_A ENGINE SLM BLR KRN HYB SLM NGP ITJ

TRAIN_B ENGINE SSR MAO NJP PNE PTA

OUTPUT -

ARRIVAL TRAIN_A ENGINE HYB NGP ITJ

ARRIVAL TRAIN_B ENGINE NJP PTA

ARRIVAL TRAIN_AB ENGINE NJP PTA ITJ NGP
 