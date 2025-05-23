Hello! Hope you are well today!

What the project has:
	The project has an inventory widget, along with items that can go into them and can be moved around in the inventory by holding the mouse button and releasing it on top of another inventory slot.
	It also includes a character to talk to and a viewport slot (non functioning)
Design decisions:
	With the inventory i wanted to be sure that, while making it only have 4, it can expand to be whatever i wanted by changing the inventory slots on the main character
	With picking up items I wanted it to be interchangable with 3D or 2D, as long as they have a mesh that can be referenced by the tracer on the player character.
	Made stackable items
	I included a number of items in a stack for stackable items
	Dialogue system is nice and quick though if I wanted I could take away player control to prevent the player from moving away, but did not find this needed for this test.

How to test:
	When you run the program/ hit play, the inventory is bound to the TAB key, you can close this by hitting the TAB key again, or the close button on the inventory widget.
	The viewport widget is opened by pressing the V key, and will open the inventory widget as well.
	Items in the map can be looked at to show an interaction message, and can be picked up with the E key as displayed. this will populate the inventory widget.
	Shields are stackable and swords are not, there is also a note plane in front of the player at the start.
	All these items can be dropped with Q and all in a stack can be dropped all at once by holding Q (current bug eats all items in the stack and drops only one.)
	You can drag and drop items between the slots in the inventory as well the viewport slot.
	There is a character on the map that can be interacted with by pressing T, pressing T repeatedly will move the dialogue forward, eventually ending it.
	After ending the first dialogue there is a question if the player presses T near the character again, and gives a different response based on player choice.

Current issues (23/5/2025 4am EST)
	Item stack doesnt drop all at once proper
	Character can move away from from dialogue and it doesn't end, most likely missing hook or 2
	Viewport function is called, currently haven't found a way to create a Widget to display the Item in an inspection mode.