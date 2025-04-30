# Headers
This is for **Heading** 1.

## Heading 2
This is for *Heading* 2.

### Heading 3
This is for ***Heading*** 3.

# List

This is how you list items in markdown.
1. Member 1
    * Team Leader
        * Project Owner
2. Member 2
    * Hardware
3. Member 3
    * Software
3. Member 4
    * Cheerleader

# Inserting an Image

To insert an image, you will need to drag + hold shift + drop

![alt text](dog.jpg)
[Click here to link](https://www.google.com)

[Click here to jump to test.md](/test/test.md)

# Code Block

To highlight or insert a particular section of code, you can do the following

1. In raspberry pi, if you want to update you will `sudo apt update` in command prompt

2. In raspberry pi, if you want to install Python Imaging Library, you will execute
`pip install Pillow` in command prompt

3. In raspberry pi, if you want to install OpenCV, you will execute
`pip install opencv-python` in command prompt

4. In raspberry pi, if you want to install Python VLC Media Player, you will execute
`pip install python-vlc` in command prompt

5. In raspberry pi, if you want to install  VLC Media Player, you will search
`https://www.videolan.org/vlc` a web browser





```
from tkinter import *

main = Tk()

main.mainloop()
```

# Quotes

A famous quote by **Sir Isaac Newton**
> For every action, there will be a reaction

# Tables

This is how you insert tables

|Header A|Header B|Header C|
|-----:|----:|---:|
|Row 1|Data A|Data B|
|Row 2|Data C|Data D|

```
|------:|This is to justify right.
```

# Horizontal Rule

This is how to insert a section line

---

# Flowchart

This is how you make a flowchart

```mermaid
graph TD

A[Sensor 1] --GPIO 17-->B
B[Raspberry Pi]-->C[L-Acoustic K2 </br>Linear Line Array]
C --> A
A --> E --
E --> C

```

# Sequence Diagram

```mermaid
sequenceDiagram;

Alice ->> Bob: Hello, How are you?
Bob -->> Alice: I am good, thanks!
Alice ->> Charlie: Have you eaten??
Charlie -->> Alice: No I have not!

```
