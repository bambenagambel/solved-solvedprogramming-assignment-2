Download Link: https://assignmentchef.com/product/solved-solvedprogramming-assignment-2
<br>
ComputerProgramming I

COP 2210

Programming Assignment #2

(Usingan Existing Class: Creating Objects

andCalling Accessor and Mutator Methods)

I. The Assignment

This assignment is to write a “test” class (aka: a “driver” class or “client code”) that uses the class Balloon.java, available on the class web page.

To use the Balloon class, download it and store it in the src folder of your NetBeansproject. Make sure you save it as Balloon.java.The best way to learn how to use the Balloon class – or any other Java class – is to consult the documentation, Balloon.html (online). You can also read the javadoc comments that appear just above the class declaration and above eachmethod declaration, which explain what each method does, what the method’sparameters are, and what value – if any – is returned by the method. The html “help” pages are generated fromthese comments.Don’t worry if you don’t understand the code. It willall be covered later. It is not necessary to know how a methodworks as long as you know what it does and how to call it.FReview declaring variables, creating objects, calling methods thatreturn a value vs. “void” methods, and accessorand mutator methods before beginning.To receive credit for this assignment,you must not modify the Balloon class in any way!

II. Your BalloonTester ClassYour BalloonTester class will have only asingle method – main – and will perform each of the following operations, inthe exact order listed below. Eachoperation may be done in one or two statements.Make sure you follow directions faithfully, and note that once you havedone step 3, you can copy and paste it to do steps 6, 9, and 12.1. Create a Balloon object with a name of your own choosing and analtitude of 100 meters.2. Create a second Balloon object with a name of your own choosing, andspecify an initial altitude of -100 meters.3. Call the accessor methods ofthe Balloon class to get the name and altitude of each Balloon object. Printthe data, one object per line.4. Make the object you created in step 1 ascend to an altitude of 300meters.5. Call the adjustAltitudemethod to increase the altitude of the object you created in step 2 by 200meters.Call the accessor methods ofthe Balloon class to get the name and altitude of each object. Print the data,one object per line.7. Call the adjustAltitudemethod to decrease the altitude of the object you created in step 1 by 150meters.8. Make the object you created in step 2 descend to the same altitude asthe other object. You may assume thatthe other object is at a lower altitude.

To get credit for step 8., the statement(s) you writemust always work, regardless of the actual altitude of the second object. Itcannot depend on you knowing thealtitude of the second object, but must utilize the fact that the object knowsits own altitude. In other words, if you use a literal to set the altitude, it is not correct.9. Call the accessor methods to get the name and altitude of each object.Print the data, one object per line.

10. Move the object you created in step 1 to an altitude that is threetimes its current altitude. As in step 8,the statement(s) you write must work for anyaltitude and may not depend on you “figuring out” the new altitude beforehand.11. Attempt to move the object you created in step 2 to an altitude that is200 meters below its current altitude.12. Call the accessor methods to get the name and altitude of each object.Print the data, one object per line.III. What to Upload to MoodleUpload a zip filecontaining1. Your BalloonTester class2. The output generated when the program runs