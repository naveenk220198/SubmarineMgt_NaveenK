# SubmarineMgt_NaveenK
# Technologies Used :
  1. VueJS Framework for UI
  2. Iview Library for UI components
  3. Bootstrap for styling and UI components
  4. Pubnub platform to send to & fro messages.

# Overview : 
The control room controls all the submarines. For this, it manages the location of all the ships and sends commands to hide itself during a war. 
When there is no threat (again sent by the control room), they come back again to the surface. Jack Sparrow (control room's head) decides when for the submarine to come back.

# Jack Sparrow Control Room : 
  1. The control room listens for submarines to register.
  2. It checks if the name is already taken while a submarine registers.
  3. The client should be sent an error to reregister with a proper name. Otherwise, it should be added to the list in control room.
  4. For each submarine registered, it should show hide button which when clicked will send a message to the submarine to hide.
  5. If a submarine hides, it should be disabled from the list.Navigate to Control Room in the navigation bar.

# Submarines
 1. Submarines (new web pages) can register with Jack Sparrow.
 2. The web page should take the name of the ship (as alphanumeric input with proper validation) and the register option.
 3. If the name is already registered with Jack Sparrow, Jack Sparrow sends an invalid signal. Submarine page should show an error.
 4. Show the status of the submarine (default is shown). When it receives a command from the server, it hides by updating the status.
 5. Submarines can also hide while it is undergoing maintenance. A button to hide should be shown. It will then be removed from Jack Sparrow's list.</li>
