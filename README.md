[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source-150x25.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class Student:

    def __init__(self):
        self.name = "Kabelan G K"
        self.role = "Student"
        self.location = "தமிழ்நாடு, India"
        
        self.languages_spoken = ["ta_IN", "en_US"]

        self.positions = {
            "Tech Society": "Joint Secretary(Intelligent Systems Community)"
        }

        self.skills = {
            "coding": ["Python", "C", "Solidity", "JavaScript"],
            "frameworks": ["ROS", "Django"],
            "frontend": ["React", "Vue"],
            "tools": ["Docker", "Git", "AWS"]
        }
        
        self.interests = ["AI", "ML", "IoT", "Cybersecurity", "Web3"]

        self.currently_learning = "Embedded systems"

        self.contact = {
            "linkedin": "https://www.linkedin.com/in/kabelan-gk",
            "youtube": "https://www.youtube.com/@Kabe-Innovates" 
        }

    def greet(self):
        print("Nandri..! Meendum Varuga.. (See you back soon!)✨")


me = Student()
me.greet()
```
