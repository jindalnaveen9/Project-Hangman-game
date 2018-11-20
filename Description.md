# Project-Hangman-game
The	objective	of	this	project	is	to	make	the	Hangman	game.	Hangman	is	a	popular	word	game	where	
one	player	thinks	of	a	word	and	the	second	player	is	required	to	guess it.	The	second	player	guesses	
an	alphabet.	If	the	guessed	alphabet	is	in	the	word	then	it	is	displayed	in	position	otherwise	the	
number	of	chances	are	reduced.	Player	2	wins	the	game	if	the	complete	word	is	guessed	before	the	
chances	run	out.

Step 1 :
Take	the	word	from	Player	1
The	first	player	enters	the	word.	The	word	has	to	be	entered	in	uppercase.

Step 2 :
Set	up	the	game
The	word	to	be	guessed	is	displayed	as	empty	boxes. The	number	of	remaining	
chances	is	also	displayed.	The	alphabets	which	can	be	guessed	are	also	shown	
to	help	the	player.

Step	3 :
Guess-The	second	player	is	asked	to	guess.	The	guess	is	first	checked	whether	it	is	a	
valid	guess.	The	textfield	has	been	configured	to	take	an	input	of	length	1.	The	
input	is	checked	whether	it	is	an	uppercase	alphabet.
If	it	is	a	valid	guess,	it	is	checked	whether	it	was	guessed	earlier.
If	it	is	a	valid	guess	and	has	not	been	guessed	before,	the	guessed	alphabet	is	
checked	for	in	the	word.	If	it	is	found,	it	is	displayed	at	the	all	the	positions	in	
which	it	is	present	in	the	word	otherwise	the	number of	remaining	chances	is	
reduced by	1. Also,	in	the	table	of	alphabets	which	can	be	guessed,	that	
alphabet	is	removed.
After	handling	the	guess,	it	is	checked	whether	the	complete	word	has	been	
guessed.	If	yes,	display	the	appropriate	messages and	end	the	game..	It	is	also	
checked	whether	chances	are	remaining.	If	none	are	remaining,	display	the	
appropriate	messages	and	end	the	game.
Keep	on	asking	the	player	2	to	guess	till	the	game	is	not	over.
