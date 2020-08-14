# Test


```python
from manim import *

class TestScene(Scene):
    def construct(self):
        dot = Dot()
        self.add(dot)
        self.wait(1)
```
![](media/images/file0/TestScene.png)

and one more:

```python
from manim import *

class TestSceneXX(Scene):
    def construct(self):
        sq = Square()
        self.add(sq)
        self.wait(1)
```
![](media/images/file1/TestSceneXX.png)