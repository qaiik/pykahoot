# pykahoot
Python selenium kahoot wrapper.

Recently, KahootPY and Kahoot.JS-Updated were taken down by [https://repl.it/@theusaf](@theusaf).

Example:

```python
import pykahoot

handle = pykahoot.JoinHandle(3816226) #My game pin

handle.create_clients(12) #Note - these are actual tabs, so dont go TOO crazy

handle.join_clients('bot name') #auto increment

```

