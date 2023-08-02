### Welcome to my github

```python

import BestCountries
import Job

class MyBiography:
    def __init__(self):
        self.name = 'Marcos'
        self.lastName = 'Porteiro'
        self.job = Job('Software Developer', 'IBM')
        self.country = BestCountries.Uruguay
        self.contact = 'https://marcosporteiro.github.io/me/'
        self.skills = ['Python', 'Java', 'SQL', 'HTML', 'Jenkins', 'Openshift']
        self.frameworks = ['Spring Boot', 'Angular', 'Flutter', 'Flask']
        self.energy = 100

    def program(self):
        if self.energy < 10:
            self.drinkCofee()
        # Do amazing stuff
        self.energy -= 1
        self.program()

    def drinkCofee(self):
        self.energy = 100

```
