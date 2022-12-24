# RibbitBoardGamePetImpl 
> Asp.Net Core exploration sandbox based on simple board game implementation

# Pages
* Main page
* Rules Page
* SignIn/Registration Page
* Playroom Managment Page
* Board Page

# Main Page, Rules, Registration 
> Regular pages

# Playroom
> Consists of 2 frames:
# [1 - List of available rooms]
* Search through rooms list (pagination needed)
* Create new group

# [2 - Current room managment]
* Manage group players role: (open / some player joined / bot / closed)
* "Start Game" button: (on click checks whether all open positions filled. if true starts new board)

# Board
> 1 - signs roles
> 2 - manages cards (each player should have 5 card each time)
> 3 - remembers turtles positions
> 4 - manages turns


<hr>
# Develper notes
* to generate new angular component: ng generate component component-name --skip-import 
* angular this proj nameing convention: 
> components named "this-way"
> folders on the other hand should fit "this_way"