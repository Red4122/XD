meme_dict = {"CRINGE": "Algo excepcionalmente raro o embarazoso",
            "LOL": "Una respuesta común a algo gracioso","ROFL": "una respuesta a modo de broma,"
            ,"SHEESH" "una muy pequeña y ligera desaprobacion",
            "CREEPY" "algo aterrador o siniestro",
            "AGGRO" "Ponerse agresivo o enojado"}
word = input("Escribe una palabra que no entiendas (¡con mayúsculas!): ")
if word in meme_dict.keys():
    # ¿Qué debemos hacer si se encuentra la palabra?
else:
    print("no se encontro la palabra")
