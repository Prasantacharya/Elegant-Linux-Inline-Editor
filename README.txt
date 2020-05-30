ELI text editor: Elegant Linux Inline text editor
This text editor is a minimilist text editor that allows the user to have multiple windows for extra functionality, like code compeltion, utf character search, spell checker, etc
Road Map:
> baseline text editor with vim keys
	> hjkl, opening, quiting, saving, quiting, etc.
> ability to slit windows for extra key/letters
	ex:

		+===================================+============================+
text --- > 	|				    |: < search for emoji >      |  <---+
		|				    |----------------------------|      |
		|				    |> 😀                        |      |
		|				    |> 👹                        |      |
		|				    |> 🍿                        |      |
		|				    |> ✈️                         |      |
		|				    |============================+      |
		|				    |: < search for common word >|  <---+----alternate windows
		|				    |----------------------------|     
		|				    |> hello                     |
		|				    |> and                       |
		|				    |> vim                       |
		|				    |                            |
		|				    |                            |
		|				    |                            |
		+===================================+============================+
		|: <enter command>                                               | < - command entering
		|[:q!]  [:w]  [:!]  [:help]  [:o]                                | < - suggested commands
		+===================================+============================+
	> these extra windows can contain common words, objects with their functions, etc.
		> features to be added: UTF-8 character search
		> common word in document/dictionary search
		> OOP object/struct function and variable search/suggesting
		> files in directory
	> windows should be resizable
> tabs for the text editor windows, and auxiliary windows
> custom scripting language for the editor, for extensibility for the extra windows
