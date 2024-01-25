---
banner: "![[computerscience.jpg]]"
---
# Systems Design

> [!Info] Designing a GUI
> ![[Untitled 1.png]]

> [!Info] Option #1: Forms
> 1.  There are field names, names next to a place where information must be entered. The places where information should be entered in by the operator are known as 'response fields'.
> 2.  Other types of response fields include radio buttons and drop-down selectors.
> 3.  The cursor 'tabs' automatically from one response field to the next. This guides the user logically through the form, ensuring that all the information needed is gathered.
> 4.  As data is entered, it is 'validated'. Validation attempts to ensure that only sensible data is entered into the system and data that is not sensible is rejected. Validation helps ensure that data entered into any system maintains its 'consistency'. This means that any data stored is only of the format expected in a particular field. Data can be validated using a range of methods. (These are discussed in more detail later in this chapter). The methods include: A range check.  
> 5. 
> -   A character length check.
> -   A data input mask
> -   A presence check.
> -   Getting the user to select from a list using combo boxes or look-up tables 
> -   Using check digits.
>   
> 6. Input can be changed/cancelled if necessary.
> 7.  Data is finally entered into the system only when an 'OK' button, ENTER or something similar is pressed.
> 8.  There is some kind of HELP facility.
> 9.  Some options are not displayed on the main screen, to avoid cluttering up the form. Access to less commonly needed facilities is via a selection button that links to a separate screen.

> [!info] Option #2: Menus 
> - Menu-based systems are ideal for situations where the user's IT skills cannot be guaranteed or in situations which require selections to be made from a very wide range of options or in situations which require very fast selection. 
> - The user of a system that uses a menu-based interface will be presented with a limited number of options on the screen. 
> - Once a selection has been made, the user is presented with a sub-menu. This gives them further options. They make another selection and may be presented with a further sub-menu. 
> - This continues until the user is able to select exactly what they want from the choices finally displayed on the screen. Here is an example of a menu-based screen that might be found at a tourist office.
> ---
> - A tourist, who may not have any IT skills, could be presented with a screen with 9 buttons on it, perhaps including theatres, cinemas, pubs and trains, for example. They would touch the touch screen in the area of one of the buttons to make a selection. 
> - If they selected 'Cinemas', for example, they would then be presented with a sub-menu. This might look like another menu-based screen with six buttons on it, for example, one for each cinema in the area. 
> - If they then selected one of those, they would be presented with the films that are currently showing and the times they are on. This type of user interface is about as simple as you can get. You do not need any computer skills to access the wealth of information on a system like this.

> [!Info] Option #3: CLI (Command User Interface)
>- A command line interface requires a user to type in commands from a list of allowable commands. Suppose you want to back-up a file called donkey.doc to a folder (directory) called animals on your floppy disk. 
>- In a GUI, you would open your file manager, click on the file you want to save and drag it to the folder called animals on the floppy disk. 
>- If you wanted to do the equivalent in DOS, for example, which has a command line interface, you would have to know how to construct the command to copy a file from one place to another.
>---
>- This type of interface can take a long time to learn and is not intuitive. For inexperienced users it can be a frustrating type of interface whilst for experienced users it can be very powerful. 
>- This is because command line interfaces provide commands that can get a user very close to the workings of the components of a computer system. 
>- There are commands that can manipulate the hardware and software in a computer system in a way that simply cannot be done using a GUI. These tasks, you have to use a command line interface to carry them out. UNIX and DOS are good examples of operating systems that use this kind of interface.
>---
>- Typical users of command line interfaces are technicians and network managers. They need to perform many set-up tasks and system tasks. These tasks can only be done using this type of interface.

---

## Voice Input

> [!Info] Voice Input
> Typical Uses
> - Voice recognition software is a program that accepts your voice via a microphone to allow you to enter commands or to allow you to enter data. There are lots of different uses of voice input, such as personal assistants like Siri, or Alexa 
>- Many companies use a system where you are asked what your query is about, then you are taken through some security details and then you are transferred to the right operator. This system is often found in any company where you have an account, for example a utilities company or a bank.
> - Companies are increasingly using a technology that makes and keeps a 'voice print' of your voice as a security measure in the never-ending fight against crime. The next time you phone in, you simply speak your name and it is compared to the voice print the company has of you. Once you have been authorised, you are then put though to a person who can deal with your query.
> - It is often quicker, especially if you don't have typing training, to speak a letter or email rather than type it in. There is usually a learning process that you have to go through with the software, to reduce the chance of incorrect entries, but once this is done and you have learnt how to manipulate the voice recognition software, it can be very accurate. Even with strong accents or voice changes due to a cold, voice recognition software can be very powerful and improve productivity.

> [!Tip] Advantages of Voice Input 
> - Easy to use for the average user.
> - Natural way of interacting with an interface.
> - No expertise required.
> - Can be done while multi-tasking.

> [!Danger] Disadvantages of Voice Input 
> - Can be difficult for the system to pick up certain words.
> - System has to know context (night vs knight)
> - People could have a strong accent that prohibits the voice recognision software from picking the voice up.
> - Accuracy decreases if background noise is present (e.g. being outside or in a noisy area)
> - Although voice recognition systems can speed up work, you have to invest the time teaching the system and correcting errors. Many people find that this is a frustrating experience.
> - A good quality mic is needed.

---

> [!Info] Manual Methods 
> 1. Keyboards: 
>  The keyboard is managed by the keyboard's own processor. When you press any key, this closes a switch, which completes an electrical cicuit. When the keyboard's processor detects this, it works out what key has been pressed by comparing the circuit that has been completed with a table of character keys kept in its Read Only Memory. It can also detect special combinations of keys pressed, such as SHIFT G being a capital G. When it has worked out the key or special combination, it then sends this information to the computer.
>   1. Touch Screens:
>  This is another manual data input method. A touch screen enables a user to touch their VDU screen to make selections. A plastic cover that has fine wires running through it can be placed over a VDU's screen. A user makes a selection by touching the screen with their finger. The exact position can be calculated from the signals sent back by the wires. Touch screens allow very fast selections from choices. They could be used in places where people need to find out information but may have zero computer skills, for example, an information system in a library or a museum.
>  3. Optical Mice
>    An optical mouse is a pointing and selecting device used with graphical user interfaces (GUI). There are different kinds of mice around, each with their own advantages and disadvantages although they all broadly do they same thing: point and select things on the screen. Optical mice are the most common type of mouse now as they aren't prone to collecting fluff and dirt and so don't need cleaning. They are also very accurate, don't need a special surface to work on and are very reliable because there are fewer moving parts than an old style roller ball mouse.
>    4. Force Feedback (Haptics)
>    A vibrational feedback is useful to confirm you pressed a key on a touch screen. Has a physical response to a digital action.
>    5. Virtual Reality
>    Immersive experience in a virtual world playing games etc.
>   6. Augemented Reality 
>   Overlaying something digital onto the real world.

## Design Validation 

- Whenever we design something, especially where we are designing it for others to use, we need to check carefully that it really is fit for purpose.

- We all have our own backgrounds, education, experiences, our own formal and informal language, culture, ethics and way of doing things. Although designers of systems in general and user interfaces in particular always like to think they know best and can design things for others to use, that rarely is the case.

> [!Info] Design Reviews 
> Designs must always be checked and checked regularly. They can be checked before a product is built in a number of ways.
> - They can be checked by the designer themselves, checking that they have indeed covered all the points in a specification. 
> - The can be checked by doing a peer-review. This is where a designer asks other designers not associated with a design to cast a critical eye over it and give feedback.
> - They can be reviewed by the customer, the actual users and any other stakeholders, such as the managers who will look after the system or the technical people who will maintain it. This can be achieved by creating a mock-up of the design or a prototype, as customers may not be technical and may have trouble visualising a design as easily as the designers can.

> [!Info] Why is a prototype used?
> - A prototype may be used as a cheap and cost-effective way to create a mock up of what could be the final product.
> - It allows you to show off a demo of the product to gather feedback and criticisms.
> - By presenting something that looks like the final product, even if it is far from functional, you are including everyone in the review process, whatever their background.
> - Prototypes also help to reassure the customer that they are going to get what they need and are paying for and is a good way of ensuring excellent on-going relationships between the customer and supplier.

> [!Danger] What happens if issues are found?
> - If issues are found, then a new updated prototype will be made based on the feedback provided.
> - This could mean improved stability or a different design.
> - This can create a loop, allwing for continual improvement of the product.

> [!Tip] Checking the user interface 
> - One area that needs special consideration is the user interface. 
> 	- Is it fit for purpose? 
> 	- How do you know? 
> - Something may look perfect on paper but just doesn't work as well in practice. 
> - It is important to check with all relevant stakeholders that the user interface is fit for purpose. 
> - Again, prototypes can help here, but ultimately, the final product's interface must be tested.

> [!Abstract]- List of Questions to ask yourself
> -   Is the user interface easy to navigate around?
> -   Are the menus clear? 
> -   Is it intuitive?
> -   Is anything frustrating to use?
> -   When they get stuck, is it easy to get help?
> -   Does the system freeze or crash at any point?
> -   Is it easy to use over longer periods?
> -   Is the jargon easy to understand?
> -   Could the layout be improved?
> -   Are the fonts readable?
> -   Can users work quickly?

## Evaluation 

> [!Info] Evaluation 
> - When a system has been completed, the customer needs to be sure that they have got what they paid for. 
> - The company who made the system needs to be sure that they have delivered what they promised. 
> - Checking this is known as the 'system evaluation'. 
> - The purpose of evaluating a system is to check that the product meets the requirements as laid down in the Requirements Specification.

> [!Abstract] Evaluating a system and customer feedback 
> After the company has used the system for a while, feedback can be given to the designers of the system to improve:
> -   Are there any bugs in the system?
> -   Are the users finding it easy to use?
> - Do the users feel as though they got adequate training and retraining?
> - How are the Help facilities working?
> - Has the product started to make an impact on the company - is it saving time and money?
> - Have profits increased as a result of the product?

> [!Tip] Final Checklist
> - Requirements 
> 	 Have we hit every target in the RS? Not a success unless every one was met.
> - Performance
> 	 Does it respond quickly enough for the user? This would be defined in the RS with a target time to hit.
> - Robustness
> 	 Does it crash at all or too much?It depends on the criticalness of the software. (e.g. hospital software could mean life or death)
> - Cost 
> 	 Has the project gone over or under budget? Over budget is more of an issue.
> - Usability
> 	 Can the target end users successfully use the system? Having the right choice of interface for the right demographic, e.g. simple intuitive, graphical design for non-tech literate people or a CLI for power users.

