

class Pat:
    def __init__(me, name, age, address, gender, date_of_birth, moto_in_life):
        me.name = name
        me.age = age
        me.address = address
        me.gender = gender
        me.date_of_birth = date_of_birth
        me.moto_in_life = moto_in_life

    def __str__(me):
        return (f"Personal Data\n"
                f"Name: {me.name}\n"
                f"Age: {me.age}\n"
                f"Address: {me.address}\n"
                f"Gender: {me.gender}\n"
                f"Date of Birth: {me.date_of_birth}\n"
                f"MOTO IN LIFE: {me.moto_in_life}")


if __name__ == "__main__":
    tao= Pat("Patrick Luis T. Nebres", 21, "Bacoor Cavite", "Male", "08/30/2002", "KUNG KERI NILA EDI SILA GUMAWA")
    print(tao)
    
