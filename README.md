- 👋 Hi, I’m @enricomarotta
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
enricomarotta/enricomarotta is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class Personaggio:
    def __init__(self, nome, età, occupazione):
        self.nome = nome
        self.età = età
        self.occupazione = occupazione

    def presentati(self):
        return f"Ciao, sono {self.nome}, ho {self.età} anni e lavoro come {self.occupazione}."

# Esempio di utilizzo
ragazza_immaginaria = Personaggio(nome="Aria", età=25, occupazione="Inventrice")
print(ragazza_immaginaria.presentati())
