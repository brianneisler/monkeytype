# monkeytype
Monkey typing for javascript. A typing system that does the work for you.


## Overview
Monkey typing is a typing system that learns the types of your code based upon
actual runtime execution values. This is achieved by importing a library into
your javascript that automatically wraps your javascript imports/requires and
injects Proxies into your modules. Using this approach we can automatically
monitor the values being sent to functions and derive an understanding of what
the expected types are. 

This enables an effortless approach to type protection that does not require a
developer to explicitly define their types. 


## Why
* Maintaining types creates significant overhead. 
* Loosely typed languages like Javascript provide significant flexibility and can be faster to
  work with.
* However, the benefits of type protection are HUGE!
* We wanted an approach that gave us the best of both worlds.

## How

* We wrap your code and analyze the values that are passed around at runtime to
different functions and accessed from different objects.
* On your device, we analyze the patterns of the values.
* These patterns are pushed to our monkey type services (not the actual data)
* We then use machine learning to derive the expected types
* This enables the learnings from any developer's machine to be shared with
  EVERYONE. Meaning the system gets better every time it is used. Which makes
  development easier for ALL OF US.

