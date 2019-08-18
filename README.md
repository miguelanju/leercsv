import pandas as pd

input("Pulsa una tecla para continuar...") 

datos=pd.read_csv('eancodes.csv',header=0)
#print (datos)
print (datos['Material 1'] , datos['TreceDig'])

input("Pulsa una tecla para continuar...hemos acabado") 
