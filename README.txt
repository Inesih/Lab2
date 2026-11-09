LAB 2 - SIMPLE WINDOWS FORMS APPLICATION

RUN
Extract the ZIP, open Lab2.sln in Visual Studio, and press F5.
The project targets .NET 10 for Windows, as in the earlier project.
Use a Visual Studio installation supporting .NET 10 with the .NET desktop
development workload installed.

LOGIN
Type ANY username and password, provided both contain something other than
spaces, then click Login or press Enter. Registration is not required.
This form checks required fields only; it does not authenticate an account.
No credentials are stored. There is no account file or password hashing.
The password is masked. Logout clears it and returns to Login.
Any account file made by the older version is ignored and is not deleted.

FORMS
Login > Choose > Bicycle Rental or Mushroom Identification.
Back on either activity returns to the existing Choose screen.
Logout returns to Login. Exit closes the entire application.
X on an activity returns to Choose. X on Choose returns to Login.
X on Login closes the application.

BICYCLE
The calculation uses the same start, end, total, validStart and validEnd
variables, for loop, and price conditions as the first console assignment.
Text boxes replace Console.ReadLine. MessageBox replaces error console output.
The starting hour is included and ending hour is excluded.
Whole numbers only; start 0-23; end 1-24; start must be before end.
Clear resets inputs/results. Changing either input clears the previous result.
Examples: 6-9=2500, 7-14=7000, 14-19=7500, 19-21=2000,
21-24=1500, and 0-24=21500 RWF.

MUSHROOM
Uses the same six mushrooms, string answers, Trim().ToLower(), yes/no checks
and decision rules as the original console assignment.
Questions appear one at a time. Submit Answer validates the text.
An invalid answer displays a message and leaves the current question unchanged.
The Windows form waits for the next button click, rather than using a console
while loop, which would block the interface. The stage variable remembers
which question to ask next; questionNumber counts valid questions answered.
Only two or three different questions are needed. Restart resets the attempt.

PATHS
Convex yes, forest no: Agaric Jaunissant.
Convex yes, forest yes, ring yes: Amanite tue-mouche.
Convex yes, forest yes, ring no: Pied bleu.
Convex no, gills no: Cepe de bordeau.
Convex no, gills yes, forest yes: Girolle.
Convex no, gills yes, forest no: Coprin chevelu.

CODE
Program.cs starts LoginForm.
Each Form.cs contains its constructor and event handlers.
Each Form.Designer.cs defines the layout, colors and controls.
All delivered C# source files contain no comments.
Colors and Back buttons are retained from the styled version.
Constructors and event handlers remain necessary for Windows Forms.

CHECKS
Calculation and mushroom logic checked programmatically; event connections,
comment removal and registration removal checked in source.
No C# build or Windows interface execution was possible in this environment.
Build and test on your Windows computer before submission.
