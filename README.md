## Introduction
Can a robot play beer pong? 
For a human with decent hand-eye coordination, this game is simple enough to play while intoxicated. However, for a Baxter robot, it is more complicated. We can break down the game of beer pong into three main components. 

1. **Computer vision**, to recognize and locate red SOLO cups on a table.
2. **Path planning**, to aim Baxter's right arm according to the best trajectory.
3. **Custom end-effector hardware**, to allow Baxter to "throw" a ping-pong ball with consistency and accuracy.

CHAD's ultimate goal is to be able to play a turn based game against a human adversary. Did we succeed? Read on to find out!

### Real World Application
Besides saving the day when your beer pong partner is too drunk to play, CHAD has several useful applications in the robotics industry.
Our cup detection could be used in places such as laboratories or warehouses, where precise identification of containers and their orientation can help automate the process of moving objects from one place to another. For example, Amazon is greatly automating their fulfillment centers and relying on robots to do simple moving tasks. 
Our trajectory calculation of the ball makes use of a concept that can be applied to any weapons technology that involves projectiles. For example, a robot can determine if its current position is the best position to take a shot at a certain target, or if it should move itself to another location that allows for a better trajectory.


## Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/chad-bot/Beer-Pong/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
