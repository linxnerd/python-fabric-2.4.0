# Python Fabric 2.4.0
Implementation of python fabric with SSH example.
Brief introduction; [_Presentation video_](https://linxnerd.wordpress.com/2018/10/10/python-fabric-2.4.0/) link.

## Installation

_`   sudo apt install fabric`_
_`   sudo apt install update`_

or the best way;

_`   pip install fabric`_
_`   pip install -U fabric`_   /// for update

For checking on-line reference manual;

_`man fab`_

After installation, create ***fabfile.py*** in your current directory and write your jobs/tasks there, and for execution:

_`    fab -l`_
_`    fab task1`_            
_`    fab task1 admin`_       
_`    fab task1 task2 ...`_   


## Note:
If your task has __Parameters__, please set it by **DEFAULT VALUES**, Because when you'll execute
multiple tasks, and anyone of it has parameters( which is __NOT__ set as DEFAULT VALUES), then the
coming task will become __STRING__ and use as parameter of this task. The results will not show as you
expected.
