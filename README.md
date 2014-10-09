# Gemini Snippets

A collection of Sublime Text snippets to speed up development with Gemini CSS and Gemini JS

## Rapid Development in Sublime Text

In the way that [Emmet IO](http://emmet.io/) offers keyword and selector tabbing to create code, this collection of namespaced Gemini Snippets allows developers to crank out the HTML markup for various Gemini Framework modules.

### Usage

Want to start creating a 3 column layout based on the 12 column Gemini grid? Simply type ``g-row444`` then hit tab - boom! You have your grid markup ready.

- Each Gemini namespaced file in this repo contains one snippet
- The shortcut ``g-help`` contains a listing of all the available Gemini Snippets as an inline reference

### Installation

This tool requires Sublime Text 2 or Sublime Text 3, and the [Carpages.ca](https://github.com/carpages) Gemini Framework.

To get started with using Gemini Snippets you'll need to copy the files from this repo into your Sublime Text ``Packages/Snippets`` directory (create the directory if it doesn't exist). You can learn more about [the default location of this directory here](http://docs.sublimetext.info/en/sublime-text-3/basic_concepts.html#the-data-directory) (though many developers sync this folder in Dropbox). Once the snippet files are in the folder they should instantly work in Sublime Text!

### Wish List
This version of Gemini Snippets is just the beginning of what will hopefully be a very valuable tool. There's much more we could do with this.

- One day these snippets may be generated and namespaced by a utility like Sass Doc. These were manually created.
- It would be nice if each module had its own ``help`` command to show the documentation doc block, modifyers, and custom extensions.
- Many other code editors have similar snippet features - it would be lovely if our build process could cater to other tools.
- It would be swell if you didn't have to manually copy files into Sublime Text working folders.
- When robots build this it would be nice to give the option of HTML / Haml / Jade for markup output.

## Credits
Gemini CSS started as a fork from [Inuit.css](https://github.com/csswizardry/inuit.css)
