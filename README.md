# Maze Agent Signifier XML

XML wall-following agent to navigate 2d mazes. This agent can also recognize "green" signifiers in the maze. The agent will automatically select and anvigate through any doorway marked with a "green" signifier. This can be used to lead the agent to the exist in fewer moves. If the agent does not find a green dot signifier, it will continue using the wall-following rule to reach the exit.

 * Download repo
 * Install dependencies (`$npm install`)
 * Run the agent (`$ node the-signifier-bot.js [maze-url]`)
 
Requires a running maze server. See (http://github.com/amee-project/maze-server). 

NOTE: to see a slow-speed maze runner, launch `$ node the-slow-bot.js [maze-url]` 

