1) Show stream graph. Link to here. http://bl.ocks.org/blockspring/5c0e800af05551349313. Look at how cool this is.

2) Make a new directory and create a new file called index.html. Copy and paste the code into index.html. Open index.html with your browser and voila! You have an incredible visualization on your computer. But now we want to make it our own.

3) BlockSpring lets you easily build an api for your code, and get your code used by non-engineers. Lets add the BlockSpring API to your block. Paste in:
    <!-- Blockspring Boilerplate CSS -->
    <link rel="stylesheet" href="//www.graf.ly/graph_templates/boilerplate.css">

    <!-- Blockspring Boilerplate JS -->
    <script src="//www.graf.ly/graph_templates/boilerplate.js"></script>

4) In your directory run: python -m SimpleHTTPServer (if you're on python 2.7). BIG NOTES HERE.

5) Next let's create a sample dataset. Copy and paste the following into a sample_data.csv file. Wrap your function into renderStream and call Block.ready(renderStream).

6) Now comes the BlockSpring-specific code. We'll develop an API for our code with a simple configs.json file. Paste in the following code and we'll explain what it does.

7) Update csv variable, headers variables, and unique series variables (showing 3 types of API use). Refresh and graph still works.

8) Now let's make this our first git commit. (INSTALL GIT IF NECESSARY).

9) Let's create a BlockSpring user account, create an ssh-key, a reponame.

10) Finally, let's push to BlockSpring. Now we can send a link to our friends and have them make our graph with their own data!

**Extra Credit.

11) Make colors editable in appearance options.

12) Add automatic dropdown capabilities with BlockSpring.