#Assignment-

The objectives to evaluate are as described in the prior module (`lambdata`
package with at least 2 helper functions, published on test PyPI). If they meet
the requirements it is a 2, exceed is a 3, and don't meet is a 1.

Considerations to keep in mind while doing a code review:
- Can you follow the code flow/layout?
- Can you understand the logic/reasoning for what it is doing?
- Could you build with (`import` and use) or extend on it (as a developer adding
  more to the codebase)?

For comments and notes, focus on style and design. Find at least *2* things to
compliment and at least *1* constructive criticism. It's also great to learn
things from their code, and ask questions if there's something you don't
understand. Good code isn't clever - it's clear!

#Code Review-

__init__.py - looks good, but you should give yourself some blank lines between your import statements and your actual code.
Also, I'm not sure the from . import will work, but it might.
2

setup.py - Looks good. You might want to space out your ''' statements so that it reads more like a paragraph. 
Your supporting code also only uses numpy and pandas, so you're good there, but if you expand you'll want to add to those.
2

vehicle_class.py - I like the spacing and layout here. You might want to check your function; you ask for a price and then assign one.
2

nat_parks.py - Love the spacing and the clear notations.
3

Final note- I'm not sure if this is necessary, but at the top of my __init__ and other files, I have #!/usr/bin/env python which is absent here.

Total Score- 2
