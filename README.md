# Luaujs
A Framework that transforms Luau's code in HTML code.

# Install
To install it use `npm install luaujs` if you installed NodeJs in your Computer!

# Usage
Luaujs comes with many commands and the framework, anything you will type will be similiar to this: `luaujs command_name arguments`

# Commands
Remember to write `luaujs ` followed by these commands:
- status: returns a sucess message if the framework is Installed Correctly, i suggest use `luaujs status` before using any other command, so you'll be sure the Framework is Available.
- help: shows the available comamnds.
- read: asks for 1 argument, the file you want to read or the path to it, if you write `luaujs read index.html` it will read the `index.html` file in your current folder you are in the terminal, if you write instead `luaujs read main/client.js` it will search for the client.js file in main Directory and then read it. Be careful with reverse paths, so like if you are searching for the Parent path of the current path you are in right now, use `cd ..` first and then use `luaujs read file_name/path`, because my Framework is not able to read the Parent Directory's Parent etc.
- create: here comes the actual power of my Framework, this command asks 1 argument (optional) which is the name so it will be `luaujs create dir_name`, this command will import a Framework Directory inside the current file the Terminal is pointing at, once downloaded you will see 3 files inside the folder: main.lua, index.html and module.lua, you will be working most of the time in main.lua, since that Script will let you can write the HTML for your web page, it will be only frontend for now.
- run: 

# Future Updates
- read will be able to read files backwords, so youll be able to write `../main/...`, `..` stands for 'search in the directory where i am inside' or the Parent of the current Directory.
