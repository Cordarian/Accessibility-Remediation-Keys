# Accessibility Remediation Keys (ARK)
So you know when you’re tagging a PDF and it’s super annoying that you have to click a button in the Reading Order window each time you want to tag something rather than just using a keyboard shortcut? And you know how I’m fueled entirely by spite? Well, turns out there *are* keyboard tagging shortcuts, but they aren’t implemented correctly, so I made a program that fixes them.

If you look closely at the Reading Order window, each button has an underlined character, e.g., the T in Table or the 1 in Heading 1. That underlined character sort of half works as a keyboard shortcut; Accessibility Remediation Keys makes it work the rest of the way.

![Adobe's Reading Order window. Each button has an underlined character if you look closely.](https://github.com/user-attachments/assets/d8408aea-c00c-47ba-9493-3f0a1c2c30ac)
 
## How do I use it?
1. Download Accessibility Remediation Keys.exe and run the program. An icon will appear down on the taskbar to show ARK is running.
   
![Windows taskbar showing the ARK icon and a pop-up describing how it's used.](https://github.com/user-attachments/assets/676fc47a-ddb4-4873-8e37-db982a48af6c)

2. Open the PDF you want to tag in Adobe, navigate to the Accessibility tab, and select Reading Order.
3. With ARK running on the taskbar, select what you want to tag, hold down the Alt key, and that underlined letter from the Reading Order window for the element you want to tag it as.
4. When you want to quit ARK, right-click that taskbar icon and select Exit.

That’s it! ARK tags what you’ve selected as that element. Below are the keyboard shortcuts I’ve been using most, since that underlining is hard to see:
-	Te<ins>x</ins>t/Paragraph: Alt+x
-	Heading <ins>1</ins>, <ins>2</ins>, etc.: Alt+1, 2, etc.
-	F<ins>i</ins>gure: Alt+i
-	<ins>T</ins>able: Alt+t
-	C<ins>e</ins>ll: Alt+e (Alt+c also works because that makes more sense to me)

There’s sadly no shortcut for creating a Header Cell, Table Row, etc.; only what’s in the Reading Order window.
