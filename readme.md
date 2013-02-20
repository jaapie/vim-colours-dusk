# Dusk Colour Scheme for Vim (GUI-only)

Those of you who use Xcode will possibly recognise this colour scheme. It is a
gui-only port of the awesome Dusk to Vim. It is the best available, as far as
I can tell. Some of the other ports are too bright. Dusk is meant to be
subdued and easy on the eyes, like the subdued and mellow light you get at
dusk.

## Installation and Usage

If you are using Pathogen to manage your Vim plugins, then all you have to do
is:

	cd ~/.vim/bundle 
	git clone git@github.com:jaapie/vim-colours-dusk vim-colors-dusk

If you have a dotfile repo and are using git and submodules like many other
sane people out there, then you probably know what to do and won&rsquo;t even read
this readme. WHich is cool, I wouldn&rsquo;t either.

Et Voila! Next time you start Vim just type `:colorscheme Dusk` and you should
be blessed with all the dark-backgrounded pinky goodness of Dusk. If you are
like me and do not want to type `:colorscheme Dusk` every time you start Vim,
just put this into your `~/.vimrc` file:


	if has("gui_running")
		colorscheme Dusk 
	endif

Since this is a GUI-only port of Dusk for Xcode if makes no sense to apply the
colourscheme when you run Vim in a termial. That&rsquo;s why the `colorscheme`
command is inside a conditional that tests if you have a GUI running.

## Credits

I want to thank the creator of the rdark colourscheme, Radu Dineiu, which is
available at http://ld.yi.org/vim/rdark/ and which I highly recommend becuase
unbeknownst the him, it enabled me in its simplicity, to create this colour
scheme file.

