Introduction to Visual C#
1. Objects
Object waa qayb ka mid ah program-ka oo:
kaydisa data
qabata operations.
Properties = data/information uu object-ku leeyahay.
Methods = actions/operations uu object-ku sameyn karo.
Tusaale:
Button → object
Text → property
Click → event/action
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
2. Controls
Controls waa objects-ka ka muuqda GUI-ga program-ka.
Examples:
Label
Button
TextBox
Waxaa sidoo kale jira objects aan muuqan sida:
Timer
OpenFileDialog
Class waa code qeexaya nooc gaar ah oo object ah. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
3. .NET
.NET waa collection of classes iyo code loo isticmaalo samaynta programs.
C# waa language ay taageerto .NET.
Controls-ka waxaa lagu qeexaa classes gaar ah oo .NET bixiso. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
4. Visual Studio
Visual Studio waa professional IDE (Integrated Development Environment).
Waxyaabaha muhiimka ah ee Visual Studio:
Designer Window
Solution Explorer
Properties Window
Toolbox
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
Toolbox
Toolbox waxaa laga doortaa controls-ka lagu darayo application-ka.
Examples:
Button
CheckBox
ComboBox
Label
ListBox
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
5. Projects and Solutions
Project
Project = hal application.
Project wuxuu ka kooban yahay files kala duwan sida:
Form1.cs
Program.cs
Solution
Solution = container qaadi kara hal ama dhowr projects.
Si fudud:
Solution → Projects → Files
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
6. Forms
Markaad bilowdo Windows Forms App, waxaa si automatic ah loo sameeyaa form la yiraahdo:
Form1
Form-ku waa meesha aad ku dhisto GUI-ga application-ka.
Form-ka waxaa lagu:
resize-gareyn karaa
controls lagu dari karaa
properties lagu beddeli karaa.
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
7. Properties Window
Properties Window waxay kuu oggolaanaysaa inaad beddesho appearance iyo behavior-ka object.
Markaad object doorato, properties-kiisa ayaa kasoo muuqda.
Waxaa jira laba columns:
Left: Property name
Right: Property value
Tusaale:
Text = My First Program
Size = 300, 300
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
8. Adding Controls
Control waxaad ku dari kartaa Form-ka adigoo:
Toolbox ka dooranaya control
Double-click sameynaya
ama
Control-ka drag gareynaya oo Form-ka saaraya.
Control-ka sidoo kale waad:
resize-gareyn kartaa
dhaqaaqin kartaa
properties-ka beddeli kartaa
delete-gareyn kartaa.
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
9. Naming Controls
Control kasta wuxuu leeyahay Name.
Naming rules:
Magacu wuxuu ku bilaaban karaa letter ama _
Characters kale waxay noqon karaan letters, numbers ama _
Spaces lama isticmaali karo.
Correct examples:
showDayButton
DisplayTotal
_ScoreLabel
C# programmers badanaa waxay isticmaalaan camelCase.
Example:
calculateButton
showResultLabel
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
10. Namespace, Class, Method
C# code waxaa inta badan loo habeeyaa:
Namespace
Container ay classes ku jiraan.
Class
Container ay methods ku jiraan.
Method
Group of programming statements oo qabta operation.
Namespace
   ↓
 Class
   ↓
 Method
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
11. Program.cs iyo Form1.cs
Marka project cusub la sameeyo waxaa si automatic ah loo sameeyaa source code files.
Program.cs
Waxay leedahay application start-up code.
Form1.cs
Waxay leedahay code la xiriira Form1.
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
12. Event-Driven Programming
GUI applications waa event-driven.
Macnaheedu waa program-ku wuxuu sugayaa user-ku inuu wax sameeyo, sida:
Button click
Key press
Mouse movement
Markaas program-ku wuxuu sameeyaa response.
Event Handler
Event handler waa method shaqeeya marka event gaar ah dhaco.
Tusaale:
private void myButton_Click(object sender, EventArgs e)
{
    // code
}
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
13. MessageBox
MessageBox waxaa loo isticmaalaa in fariin lagu soo bandhigo.
Syntax:
MessageBox.Show("Hello World");
Tusaale:
private void myButton_Click(object sender, EventArgs e)
{
    MessageBox.Show("Thanks for clicking the button!");
}
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
14. Label Control
Label wuxuu text ku soo bandhigaa Form-ka.
Important properties:
Text
Name
Font
BorderStyle
AutoSize
TextAlign
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
TextAlign
Waxay leedahay 9 positions:
TopLeft       TopCenter       TopRight

MiddleLeft    MiddleCenter    MiddleRight

BottomLeft    BottomCenter    BottomRight
15. Assignment Operator =
= waxaa loo yaqaan assignment operator.
Value-ga la siinayo wuxuu ku yaalaa left side.
Example:
answerLabel.Text = "";
Tani waxay Label-ka ka dhigaysaa empty.
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
16. IntelliSense
IntelliSense waa feature-ka Visual Studio ee kaa caawiya qorista code-ka.
Waxay soo jeedisaa:
keywords
variables
methods
classes
properties
Markaad code qorayso, waxay kuu soo bandhigtaa options aad dooran karto. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
17. PictureBox
PictureBox waxaa loo isticmaalaa in image lagu soo bandhigo Form-ka.
Important properties:
Image → image-ka la soo bandhigayo
SizeMode → sida image-ka loo display-gareynayo
Visible → image-ka inuu muuqdo iyo in kale
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
18. Sequential Execution
Statements-ka program-ka waxay u shaqeeyaan sequence, yani order-ka ay u qoran yihiin.
Example:
cardBackPictureBox.Visible = true;
cardFacePictureBox.Visible = false;
First statement ayaa shaqaynaysa, kadib second statement.
Order khaldan wuxuu keeni karaa logic error. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
19. Comments
Comments waa notes lagu qoro source code-ka si loo sharaxo code-ka.
Single-line comment
// Make image visible.
Multi-line comment
/*
   Line one
   Line two
*/
Comments-ku ma aha code la execute-gareeyo. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
20. Indentation
Indentation iyo blank lines waxay code-ka ka dhigaan mid si fudud loo akhriyo.
Tusaale:
private void exitButton_Click(object sender, EventArgs e)
{
    this.Close();
}
�
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
21. Closing the Application
Si aad u xirto current Form:
this.Close();
Si aad u xirto whole application:
Application.Exit();
Farqiga:
this.Close() → current form ayuu xiraa.
Application.Exit() → application-ka oo dhan ayuu xirayaa. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
22. Syntax Errors
Syntax error waa qalad ku jira qaabka code-ka.
Visual Studio wuxuu error-ka ku tusaa red jagged line hoosta code-ka.
Tusaale haddii statement-ka si khaldan loo qoro, Visual Studio ayaa kuu tilmaamaya meesha error-ku jiro. �
Chapter_01_Gaddis_CSharp_6e_accessible.pptx
⭐ Waxyaabaha ugu muhiimsan ee aad imtixaanka xafidi karto
Object       = component that stores data and performs operations
Property     = data/setting of an object
Method       = operation an object can perform
Control      = visible object in GUI
Class        = code that describes a type of object
.NET         = collection of classes and code
Visual Studio= IDE for developing programs
Toolbox      = used to select controls
Project      = one application
Solution     = container for projects
Event        = user action
Event Handler= method that responds to an event
MessageBox   = displays a message
Label        = displays text
IntelliSense = helps complete code
PictureBox   = displays an image
Comment      = note in source code
this.Close() = closes current form
Application.Exit() = closes whole application

# C-Sharp

# Subject Outline

This subject is about C# programming. We learn how to create simple programs using Visual Studio and C#.

# Chapters / Topics

# Chapter 1

- Objects
- Properties
- Methods
- Controls
- Classes
- Visual Studio
- Toolbox
- Forms
- C# code
- Events
- MessageBox
- Label
- IntelliSense
- PictureBox
- Comments
- Syntax errors

# Course Objectives

The main objectives of this course are:

- To learn the basics of C#.
- To learn how to use Visual Studio.
- To create simple C# programs.
- To learn how to use Forms and Controls.

- # Week 1 Screenshots

## Screenshot 1 – Welcome to C#

This screenshot shows my C# program running.

When I run the program, it shows a small message box with "Welcome to C#".

I used a message box to display the message. This is one of the simple things I practiced in Week 1.

- To understand basic C# code.
- To learn how events work.
- To practice writing C# programs.
