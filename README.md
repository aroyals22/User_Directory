# User_Directory
Employee list sorter 
This was a "gimmie" hw since we were given solution. I did examine code and mostly understood the logic but i did come up with a few questions:
1. Header.js, why was this made into a class component? Why would it make more sense being a functional component, it does nothing dynamically?
2. Inside Main.js, inside return they have an empty "<> </>". Code doesnt work without it, i've never seen this before in any other examples, seems to act as a div?
3. Object.values in DataArea.js: this looks like a native JS method? not sure what it does here. 
4. I got lost in the transition from Nav.js->SearchBox.js.  The "e" in searchbox is the event correct? so pass the event into handleSearchChange function.  This function is a prop handed down from Nav.js, but Nav.js was handed this down as a argument variable from DataArea correct? In dataarea we are changing the state dependent on what happened all the way down searchbox.js and the event inside that, correct?

