d3.js-Sublime-2-Snippets
========================

My personal collection of d3.js code snippets for Sublime 2 (Time Saver!!!!)


HOW TO INSTALL
==============
Browse to the following path on your UNIX system. Make sure you change the YOUR_USERNAME placeholder
with your current user.
```
cd /Users/YOUR_USERNAME/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/
```

If the folder 'JavaScript' doesn't exisits inside of this folder, create it:
```bash
mkdir JavaScript
```
Enter this folder:
```
cd JavaScript
```

I recommend to checkout the repository directly in this folder:

```
git clone git@github.com:roundrobin/d3.js-Sublime-2-Snippets.git .
```

Now you will see inside of the ./JavaScript folder, a bunch of .sublime-snippet files.
Feel free to add new ones.

Restart Sublime 2.

HOW TO USE
==============
After you've installed the snippets, you can trigger the insertion of a snippet by typing in one of 
the follwing commands inside of a .js file and pressing the TAB key afterwards.

The list of available snippets:
```
.a + TAB       ==> .attr("",)

.st + TAB      ==> .style("",)

circle + TAB  ==> append("svg:circle")...

rect + TAB    ==> append("svg:rect")...

text + TAB    ==> append('svg:text')...

line + TAB    ==> append('svg:line')...

path + TAB    ==> append('svg:path')....

polygon + TAB ==> append('svg:polygon')...

group + TAB   ==> append('svg:group')...
                    
xscale + TAB   ==> var xscale = d3.scale.linear().domain(...

yscale + TAB   ==> var yscale = d3.scale.linear().domain(...

randcol + TAB  ==> '#'+Math.floor(Math.random()*16777215).toString(16);

join + TAB     ==> .selectAll("").data().enter().append("")...

con + TAB      ==> console.log('LOG:','')

dfun + TAB     ==> function(d,i){ return ''} 
```




