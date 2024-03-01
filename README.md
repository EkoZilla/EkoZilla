class Person:
    def __init__(self, name, age, occupation):
        self.name = name
        self.age = age
        self.occupation = occupation

    def introduce(self):
        return f"Hi there, I'm {self.name}. I'm {self.age} years old and I'm a professional at Googling things."

EkoZilla = Person("EkoZilla", 24, "Googling things")
print(EkoZilla.introduce())
