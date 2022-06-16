# FRESH Syntax 👨‍💻

> Designed for the programmer, this commenting syntax is designed to help you retain and regain where you are in long files. And remain sane.

These are little things that help me as a programmer. 

After growing + nurturing this syntax over the past few years, It's ready for the world the world. Take what you like, experiment, and share your ideas to improve as issues or PRs 🙏

# Section Headers 🏛

`// === Main Section Header === \\`


`// --- Secondary Section Header or Explainer --- \\`


# Long Comment ✍️

```javascript
/*/
Having symmetric comments makes things look a little nicer, and are easier to move around. 
/*/
```


# One Line Comments 🗯

> Adding lines helps eyes flow to important comments

// Regular Comment

// - Important Comment

// -- More Important Comment

// --- Most Important Comment

// !! But really this is needs to be adressed right now

// !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! - Brooo forreal 



Add readability to any comment in a small space.

```javascript
{// -- Send love to the homies 
  name: 'daps',
  interval: '1d',
  timeout: '300'
}
```

# Scope Terminator 🔭

Use `//END scope()` to keep yourself from getting lost in deep nesting

```javascript 
scoped_function(){
  ..
  nested_function(){
    
  }//END nested_function() 
  ..
}//END scoped_function() 
```

# Action Tags 🏷  

It's hip to keep tags in your bag for easy spotting of common things that need addressing. You can use any tags you like, as long as they are known and agreed upon per-team / -project. Ideally, you look back on them and address before production, but, you know.   

TODO - Something you need to circle back and finish coding  
CHECK - Code may not be needed, but functionality hasn't been confirmed  
WARN - Flag that code may have issues or need improvement in the future  
DEP / DEPRECIATED - Old code that for some reason is commented out in a section  
CRITICAL / URGENT / VITAL - Needs to be changed for sure before moving onto production or next phase
REMOVE - Code that shouldn't make it into production  

Here's more tags from [Wikipedia](https://en.wikipedia.org/wiki/Comment_(computer_programming\)) if you'd rather stick to the script  
BUG – a known bug that should be corrected.  
FIXME – should be corrected.  
HACK – a workaround.  
TODO – something to be done.  
NOTE – used to highlight especially notable gotchas.  
UNDONE – a reversal or "roll back" of previous code.  
XXX – warn other programmers of problematic or misguiding code  

> Format suggestion: I have found using tags like this "// CHECK : The code is working" is good for readability  


# Benefits 🍆🍑  
FRESH syntax improves readability for the programmer by   

- Horizontal lines [improve readability](I have no source apparently.md)  
- Scope termination so you don't get lost  
- Searchable FLAGS help quality control  
- Symmetric comments are pleasing to the eye  

*Welcome for improvements in issues / PRs.*  

👨‍💻☕️ Author: [Douglas Butner AKA Sir Douglas Fresh](https://douglas.life)
