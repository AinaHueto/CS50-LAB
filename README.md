# CS50-LAB
Introduction to Computer Science

lab50:

  files:
    - !include foo.c
    - !include foo.h
    
   lab50:
  files:
    - !include foo/bar.c
    - !include foo/bar.h
    
    lab50:
  files:
    - !include foo/
    
    lab50:
  files:
    - !include "foo/*.c"
    - !include "foo/*.h"
    
    lab50:
  files:
    - !exclude "*"
    - !include "foo.*"
    
    lab50:
  cmd: python
  
  lab50:
  cmd: bash
  
  {% next %}
  
  {% next "Step 2" %}
  
  {% spoiler %}
The Answer to the Great Question... 
Of Life, the Universe and Everything...
Is...
Forty-two.
{% endspoiler %}

{% spoiler "Hint" %}
You're really not going to like it.
{% endspoiler %}

{% spoiler "Solution" %}
Forty-two.
{% endspoiler %}

{% video https://www.youtube.com/watch?v=oHg5SJYRHA0 %}
