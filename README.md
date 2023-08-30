<!-- this -->
shows the button that triggered the function
Eg. colsole.log(this.innerHTML); --- shows the inner HTML of that button when clicked.

<!-- ADDING AUDIO W JS--- -->
var varNameHere = new Audio('filePathHere');
varNameHere.play();

<!-- ADDING EVENT LISTNERS--- -->
selector.addEventListener("type", functionHere);

<!-- Keyboard Inputs -->
- "keypress" event listner: provides the detailed info of the key pressed
- Add this event listner to the whole document
- "keypress" when console logged gives many properties including "key"
<!-- KeyboardEvent {isTrusted: true, key: 't', code: 'KeyT', location: 0, ctrlKey: false, …} -->
- functionName.key: gives the key value alone
- Check it with SWITCH statement to find the right sound of the key pressed and play the corresponding sound

<!-- Adding animation to the buttons -->
- create a class in CSS to change the button color to show a shadow
- add that class to the button with JS by classList.add(---)
<!-- For returning back to the normal form -->
- add a setTimeout with a function that removes the class w animation to return to the normal form after a few seconds