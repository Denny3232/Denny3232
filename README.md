class Author:
    def __init__(self, author_name, interests, learning, collaboration, reach_method, author_pronouns, fun_fact):
        self.author_name = author_name
        self.interests = interests
        self.learning = learning
        self.collaboration = collaboration
        self.reach_method = reach_method
        self.author_pronouns = author_pronouns
        self.fun_fact = fun_fact

    def display_info(self):
        return (f"Hi, I’m {self.author_name}\n"
                f"I’m interested in: {self.interests}\n"
                f"I’m currently learning: {self.learning}\n"
                f"I’m looking to collaborate on: {self.collaboration}\n"
                f"How to reach me: {self.reach_method}\n"
                f"Pronouns: {self.author_pronouns}\n"
                f"Fun fact: {self.fun_fact}")

my_README = Author("@Denny", "code", "code", "code", "dont", "decagon", "code")
print(my_README.display_info())
