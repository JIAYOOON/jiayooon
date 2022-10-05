runfile('C:/Users/yoonj/OneDrive/바탕 화면/과제 제출/turtle_runaway.py', wdir='C:/Users/yoonj/OneDrive/바탕 화면/과제 제출')
Exception in Tkinter callback
Traceback (most recent call last):
  File "C:\Users\yoonj\anaconda3\lib\tkinter\__init__.py", line 1892, in __call__
    return self.func(*args)
  File "C:\Users\yoonj\anaconda3\lib\tkinter\__init__.py", line 814, in callit
    func(*args)
  File "C:\Users\yoonj\OneDrive\바탕 화면\과제 제출\turtle_runaway.py", line 89, in step
    self.drawer3.setpos(-300, 260)
  File "C:\Users\yoonj\anaconda3\lib\turtle.py", line 1777, in goto
    self._goto(Vec2D(x, y))
  File "C:\Users\yoonj\anaconda3\lib\turtle.py", line 3181, in _goto
    self._update()
  File "C:\Users\yoonj\anaconda3\lib\turtle.py", line 2661, in _update
    self._update_data()
  File "C:\Users\yoonj\anaconda3\lib\turtle.py", line 2647, in _update_data
    self.screen._incrementudc()
  File "C:\Users\yoonj\anaconda3\lib\turtle.py", line 1293, in _incrementudc
    raise Terminator
turtle.Terminator