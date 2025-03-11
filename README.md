# Uri-online-judge-1049
Animal
# Read input as strings, not lists
word1 = input().strip()
word2 = input().strip()
word3 = input().strip()

# Decision structure based on the given classification
if word1 == "vertebrado":
    if word2 == "ave":
        if word3 == "carnivoro":
            print("aguia")
        elif word3 == "onivoro":
            print("pomba")  # Corrected from "minhoca"
    elif word2 == "mamifero":
        if word3 == "onivoro":
            print("homem")
        elif word3 == "herbivoro":
            print("vaca")
elif word1 == "invertebrado":
    if word2 == "inseto":
        if word3 == "hematofago":
            print("pulga")
        elif word3 == "herbivoro":
            print("lagarta")  # Corrected spelling
    elif word2 == "anelideo":
        if word3 == "hematofago":
            print("sanguessuga")
        elif word3 == "onivoro":
            print("minhoca")
