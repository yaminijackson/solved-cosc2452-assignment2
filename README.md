Download Link: https://assignmentchef.com/product/solved-cosc2452-assignment2
<br>
There is no book containing the music to every song that will be written. There is no book containing the answers to every mathematical calculation that we will need to perform. Similarly, there is no book, set of lecture slides, video, etc. that will give a programmer (you) the solutions to every programming problem. A programmer is able to take fundamental programming concepts and, with the experience they have gained from analysis, evaluation and problem solving, put them together to solve new problems.

A programmer is also a developer who can plan, minimise risks, iteratively develop, test and deliver programs to a “client”. As a part of this, a programmer should be able to show snapshots of the various stages of the development. The snapshot should be a runnable Java program that does not need to have all of the features that will be there in the final version of the program.

For this assignment, assume that you are a freelance programmer creating a small tool or a utility program of your own choosing to add to your portfolio of simple Java applications. With this project you aim to demonstrate to potential employers or clients how you can:

<ol>

 <li>Create a small tool or utility program using (exclusively) a limited set of fundamental code concepts</li>

 <li>You are able to analyse and evaluate your implementations against possible alternatives in your code documentation.</li>

</ol>

Note: You must not just “throw in the concepts” to your program just because they need to be there; it should be clear from the code why a certain concept should be there and you must further explain these through your comments. You will also need debug your code on your own and document any issues, etc.

If there are questions, you must ask via the Canvas→<a href="https://rmit.instructure.com/courses/56563/discussion_topics/552829">Discussions</a><a href="https://rmit.instructure.com/courses/70691/discussion_topics/959976">→</a><a href="https://rmit.instructure.com/courses/70691/discussion_topics/959976">Discussions→Assignment 2 discussion forums</a> in a general manner (replicate your problem in a different context in isolation before posting).

<ol start="2">

 <li>Assessment Criteria</li>

</ol>

This assessment will determine your ability to:

<ol>

 <li>Follow coding, convention and behavioral requirements provided in this document and in the lessons.</li>

 <li>Independently solve a problem by using programming concepts taught over the first several weeks of the course.</li>

 <li>Write and debug Java code independently.</li>

 <li>Document code.</li>

 <li>Ability to provide references where due.</li>

 <li>Meeting deadlines.</li>

 <li>Seeking clarification from your “supervisor” (instructor) when needed <u>via discussion forums</u>.</li>

 <li>Create a program by recalling concepts taught in class, understanding and applying concepts relevant to solution, analysing components of the problem, evaluating different approaches.</li>

</ol>

<ol start="3">

 <li>Learning Outcomes</li>

</ol>

This assessment is relevant to the following Learning Outcomes:

<ol>

 <li>Demonstrate knowledge of basic concepts, syntax and control structures in programming</li>

 <li>Devise solutions to simple computing problems under specific requirements</li>

 <li>Encode the devised solutions into computer programs and test the programs on a computer</li>

 <li>Demonstrate understanding of standard coding conventions and ethical considerations in programming.</li>

</ol>

<ol start="4">

 <li>Assessment details</li>

</ol>

Note: Please ensure that you have read sections 1-3 of this document before going further.

You must meet Functional Requirements (4.1), Code+Justification Requirements (4.2) and Documentation Requirements (4.3) to obtain the full mark for this assignment. You can also attempt the Bonus Requirements (4.4).

4.1) Functional Requirements:

Important: The functional requirements below must be implemented and justified by following the 4.2 Code+Justification requirements.

F1) Allows the user to store an arbitrary number of records of the same type. May store more than 1 type of record.

F2) Allows the user to add, remove and modify such records.

F3) Uses at least two separate windows (that can exist simultaneously): one for main menu or high-level operations and at least one more for more specialised operations (e.g. entering/editing details).

F4) Have information and operations organised within the windows using tables, text fields, buttons and presentation-related operations from weekly live lectures.

Tip: As you are not given marks for creativity or the usefulness of the program, do not spend too much time thinking of what is a

“good” program. What is good depends on how well the code is written, justified and documented (refer to sections 4.2 and 4.3).

<table width="688">

 <tbody>

  <tr>

   <td colspan="3" width="688">4.2) Code+Justification Requirements (15 marks):To receive marks for Code+Justification requirements, you must use the following code concepts to make a functionally cohesive program that also meets the functional requirements. You must only use concepts explained and demonstrated in the weekly live lectures held by Gayan (typically held on Monday nights).  If you require the use of some additional concepts, please seek clarification through the Canvas→Assignments→Assignment 2 forum. Your work cannot be simply a renamed version of an example shown in class. Code without justification in the required format would attract no more than 50% of the mark allocated for that component. Comments without code will not attract any marks.An important note on Java code validity: A program with even one red dot (compilation error) cannot be tested and therefore will attract 0 marks for this section.</td>

  </tr>

  <tr>

   <td width="102"><strong>Code concept</strong></td>

   <td colspan="2" width="587"><strong>Requirements (15 marks when justified as required) – No partial marks for dot points</strong></td>

  </tr>

  <tr>

   <td width="102">CJ1) Single-class object oriented code using provided template with… 1×3=3 marks</td>

   <td colspan="2" width="587">•                    Appropriate name for java file (must not use names like Assignment2.java); Follows conventions shown in IIE solution lectures, other standard class materials and common ones in the Java API. The main method should have only one line to create an object of the main application class (refer to startup code and week 6+ weekly live lecture examples).•                    Consistent code and comments formatting, with comments start on the line before the documented block/statement (e.g. not on lines with code). Only relevant, reachable code+comments included.•                    No uses of return in middle of methods, break, continue, System.exit or similar branching (spaghetti code) anywhere in the code.</td>

  </tr>

  <tr>

   <td width="102">CJ2) Variables…0.5×2=1 mark</td>

   <td colspan="2" width="587">• Some of which are object member variables (may include arrays). These are explicitly private, non-static and there should be no = signs near declarations. Every reference to an object member variable from a method starts with this. (i.e.</td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td colspan="2" width="587">“this dot”, e.g. this.gt). Descriptive variable names used and does not use vague names (e.g. numRecords)• Used in place of duplicated literals. Demonstrates understanding of primitive data types vs. class types where relevant.</td>

  </tr>

  <tr>

   <td width="102">CJ3) Constructor 1×1=1 mark</td>

   <td colspan="2" width="587">• The class has only one constructor and all object member variables, arrays, etc. declarations are explicitly initialised in this constructor before any other operations.</td>

  </tr>

  <tr>

   <td width="102">CJ4) Methods 1×2=2 marks</td>

   <td colspan="2" width="587">•              All methods are explicitly public and non-static. Methods are created when absolutely necessary or when it reduces duplication of code.•              One or more methods created by student must take parameters and one or more methods created by student must return values. Both could be demonstrated using the same method.</td>

  </tr>

  <tr>

   <td width="102">CJ5) Multi window user interface using GTerm…1×3=3 marks</td>

   <td colspan="2" width="587">•              Uses GTerm exclusively for inputs. Most, if not all, user inputs must be taken via either text fields or text areas (vs.getInputString). May use password fields and dialogue boxes.•              Uses GTerm exclusively for outputs. Must use tables with headings and columns. Minimal use of .show…Dialog methods to display outputs. Uses GTerm’s methods setXY, addImageIcon, setFontSize, etc. to improve presentation.•              Uses GTerm buttons. Performs operations on rows selected from tables.</td>

  </tr>

  <tr>

   <td width="102">CJ6) Conditional execution and repetition 1×2=2 marks</td>

   <td colspan="2" width="587">•              Uses if/else/else if appropriately and exclusively for non-repeating conditional execution and at least one reachable else if statement. Conditions do not include tautologies. Every code block in every if/else/else if/while structure is reachable.•              Uses while-loops appropriately and exclusively for repetition. Loop condition describes all situations under which the loop will repeat and condition fails eventually. Conditions do not include tautologies. Pathways are not redundant.</td>

  </tr>

  <tr>

   <td width="102">CJ7) Arrays 1×3=3 marks</td>

   <td colspan="2" width="587">• Uses multiple arrays of primitive or shown Java API classes to maintain records. Only standard Java arrays used. (e.g.does not use ArrayLists, etc.)• Array lengths are determined at run-time (e.g. based on how many records the user wants to store).• All array manipulation performed by student using while-loops, if-statements, etc. without using other classes.</td>

  </tr>

  <tr>

   <td colspan="3" width="688"><strong>Justification Requirements</strong>Note: You will not receive full marks allocated for the CJ requirements above unless each occurrence is justified as required below.</td>

  </tr>

  <tr>

   <td colspan="2" width="192"><strong>Type of code</strong></td>

   <td width="496"><strong>Evaluate and justify your choice over other possible alternative…</strong></td>

  </tr>

  <tr>

   <td colspan="2" width="192">Declarations(also applies to method definitions)</td>

   <td width="496">Identifier names Data typesLocalities of declaration (why object-level vs. parameter-level vs. method-level vs. block-level, etc.).</td>

  </tr>

  <tr>

   <td colspan="2" width="192">Contents of code blocks</td>

   <td width="496">Formulations (is there a simpler way to meet requirements without creating this code block?)Inclusions (what you have added and why?)Sequences (why are these in this order?)Exclusions (what you haven’t added and why)</td>

  </tr>

  <tr>

   <td colspan="2" width="192">Conditions</td>

   <td width="496">Formations of the logic (e.g. “is glass half full” vs. “is glass half empty”, etc.)</td>

  </tr>

  <tr>

   <td colspan="3" width="688"><strong>Template/Start-up code</strong>In the most initial form, your code must take the following organisation:</td>

  </tr>

  <tr>

   <td colspan="3" width="688"><strong>public</strong> <strong>class</strong> Assignment2RenameThisClass {<strong>private</strong> GTerm gtMain; <strong>private</strong> GTerm gtSub;<strong>public</strong> Assignment2RenameThisClass() { <strong>this</strong>.gtMain = <strong>new</strong> GTerm(600, 400); <strong>this</strong>.gtSub = <strong>new</strong> GTerm(400, 600);}// The main method must only perform the included operation.// Do not add any other code to the main method.<strong>public</strong> <strong>static</strong> <strong>void</strong> main(String[] args) {Assignment2RenameThisClass a2obj = <strong>new</strong> Assignment2RenameThisClass();}}</td>

  </tr>

  <tr>

   <td colspan="3" width="688">You can rename identifiers to suit. You can create the second GTerm object later but it still must be initialised in the constructor.</td>

  </tr>

  <tr>

   <td width="102"></td>

   <td width="91"></td>

   <td width="496"></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Documentation Requirements (<strong>3 mark </strong><strong>penalty</strong><strong> if requirements below not met</strong>):</li>

</ul>

Important note: Documentation must match with testable, functional and justified code to attract marks.

D1. Create an illustrated PDF user guide (one file): Must be written to show a non-programmer how to make use of the functions of the application (based on functional requirements). Must include screenshots of sample inputs and relevant/corresponding outputs. Include instructions on what the user can and cannot do (e.g. what they can and can’t input). Do not refer to code in the written sections or show any code even in the screenshots.

<ul>

 <li>Bonus Requirements</li>

</ul>

Important note: The total mark of A1+A2+A3 is capped at 45 (for a full break-down, see Canvas→Assignments). To obtain any bonus marks for this assignment, you need to be able to get full marks for the non-bonus/standard requirements of this assignment.

B1: Submit at least 1 work-in-progress version of your assignment (minimum requirement is CJ1) and then submit your final version of assignment 2 one day before the deadline for +0.1 marks or 2 days before the deadline for +0.2 marks, etc.

<ol start="5">

 <li>Referencing guidelines</li>

</ol>

What: This is an individual assignment and all submitted contents must be your own. If you have used sources of information other than the contents directly under Canvas→Modules, you must give acknowledge the sources and give references using IEEE  style.

Where: Add a code comment near the work to be referenced and include the reference in the IEEE style.

How: To generate a valid IEEE style reference, please use the <a href="http://www.citethisforme.com/ieee/source-type">citethisforme tool</a> if unfamiliar with this style. Add the detailed reference before any relevant code (within code comments).