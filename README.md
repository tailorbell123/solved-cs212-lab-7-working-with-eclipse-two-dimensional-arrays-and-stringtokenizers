Download Link: https://assignmentchef.com/product/solved-cs212-lab-7-working-with-eclipse-two-dimensional-arrays-and-stringtokenizers
<br>
<span class="kksr-muted">Rate this product</span>

Working with Eclipse, Two-dimensional arrays and StringTokenizers.

<ol>

 <li>Open Eclipse, set up your private workspace on the H: drive, and create a Java Project for Lab7. Instructions are provided separately.</li>

 <li>A Java program (HelloWorld.java) has been provided on the public Z: drive under the folder Lab7. Import this program into your Lab7 project in Eclipse:

  <ol>

   <li>Right click on the src folder under Lab7 in your list of Eclipse projects.</li>

   <li>Choose Import, expand General by clicking on the + sign, choose File System</li>

   <li>Click on Next, then Browse and go to the Z: drive and select the folder Lab7 andclick OK. Click the box next to HelloWorld.java (the file you want to import) and click Finish.</li>

  </ol></li>

 <li>In Eclipse, double click the file HelloWorld.java. It should open the file in a tab. With the cursor somewhere inside the tab with the source code, right click and choose Run As Java Application. The program should run, and the output should appear at the bottom in the Console tab.</li>

 <li>Using the same procedure to import a file, bring the program TwoDimArray.java intoyour Lab7 project. Open the file and observe what it does, and run it. The output in theconsole should be:123 456 789</li>

 <li>Fill in the method PrintArrayEven with code that only prints the even numbers in thearray. Instead of the odd numbers, print an asterisk (“*”). The output should be:*2* 4*6 *8*</li>

 <li>Now let’s read the numbers for the array from a file. First, you will need to import the TextFileInput program from the Lab7 folder in the Z: drive to the src folder of your Lab7 Java project. Also, import the file twodimension.txt into the Lab7 folder from the Z: drive.Open the file twodimension.txt. The first two lines represent the number of rows and columns. The rest of the file contains the numbers to be put in the array row by row. Write a method a method:<pre>           public static int[][] fillArray(String myFile)</pre>that will read from the input file myFile and return a two dimension array of integers that are read from the file. The method should read the first two lines of the file and declare the array (which it will eventually return), then have a doubly-nested for loop to read all the numbers into the array. Remember to use Integer.parseInt() to convert each of the strings read in from the file to integer. Run the main program again, using the array returned by this method for printing.</li>