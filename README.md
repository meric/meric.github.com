## What Can I Do For You?

- Web development in Python Django
- Android Application Development with Python Kivy
- Python or Lua Programming
- [Email me](mailto:meric.au+github@gmail.com)

## What Have I Built?
### Lisp to Lua compiler (has macros), compatible with Lua 5.2 or Lua JIT 2.0, starred by 40+ people on github: https://github.com/meric/l2l

Turns this (not so good example of a factorial function):

```lisp
; Example 1: Function declaration
(print "\n--- Example 1 ---\n")
(defun ! (n) 
  (cond ((== n 0) 1)
        ((== n 1) 1)
        (true (* n (! (- n 1))))))
(print (! 100))
```

into this:

```lua
local _9obj_call = print("\n--- Example 1 ---\n")
function __c33__(n)
  -- ::LINE_6_COLUMN_3::
  local _nqh3_cond
  do
    if (0 == n) then
      -- ::LINE_6_COLUMN_18::
      
      _nqh3_cond = 1
      goto _nqh3_cond
    end
    if (1 == n) then
      -- ::LINE_7_COLUMN_18::
      
      _nqh3_cond = 1
      goto _nqh3_cond
    end
    if true then
      -- ::LINE_8_COLUMN_15::
      local _3qps_call = __c33__((n - 1))
      _nqh3_cond = (n * _3qps_call)
      goto _nqh3_cond
    end
  ::_nqh3_cond::
  end
  return _nqh3_cond
end
local _4nxl_call = __c33__(100)
local _z9e4_call = print(_4nxl_call)
```


### Django website with paypal integration, built for a previous client: https://accounttracker.com

![AccountTracker.com](http://i.imgur.com/ofUnj2q.png)


### Scalable notification framework using redis, each notification having a different set of recipients: (on the right side of) http://gradconnection.com.au 

![Gradconnection notifications](http://i.imgur.com/HsTQw5A.png)

- I also helped Gradconnection reduced processing time on some of their most frequently visited pages by over 90% through optimizing their calls to the Django ORM.

## What Did I Study?
### Bachelor of Commerce and Software Engineering (Honours), 2008-2013
#### University of Sydney

- Software Engineering Units I have studied that involved programming:

```
    COMP  2007  Algorithms and Complexity
    COMP  2129  Operating Systems and Machine Principles  
    COMP  3308  Introduction to Artificial Intelligence
    COMP  3615  Software Development Project  
    COMP  5046  Statistical Natural Language Processing
    COMP  5348  Enterprise Scale Software Architecture
    ELEC  1601  Foundations of Computer Systems
    ELEC  3609  Internet Software Platforms
    ELEC  4712  Honours Thesis A
    ELEC  4713  Honours Thesis B
    ELEC  5619  Object Oriented Application Frameworks  
    INFO  1103  Introduction to Programming
    INFO  1105  Data Structures
    INFO  2120  Database Systems 1
    INFO  3220  Object Oriented Design
```

<p>
- The minimum grade I have achieved in the above courses was "Distinction".

## Where To Find Me?

- [HN](http://news.ycombinator.com/user?id=meric)
- [Github](http://github.com/meric)
- [Email me](mailto:meric.au+github@gmail.com)

