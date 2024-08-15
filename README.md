# Rosana

# Link do video de explição: 

https://youtu.be/AC-XclBXmOI

# Código do video: 

```Bash 

import statistics

notas = [7.5, 8.0, 6.5, 9.0, 8.5]

def calcular_media(notas):
    return statistics.mean(notas)

print(f"Media inicial com os valores padroes: {calcular_media(notas)}")

def adicionar_nova_nota_e_recalcular(nota):
    notas.append(nota)
    print(f"Notas Atualizadas: { notas} ")
    return calcular_media(notas)

print(f"Nova media: {adicionar_nova_nota_e_recalcular(12)}")
```
