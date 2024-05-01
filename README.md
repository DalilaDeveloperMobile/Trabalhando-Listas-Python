![Captura de tela 2024-04-17 123206](https://github.com/DalilaDeveloperMobile/Conhecendo-Linguagem-Python/assets/29806802/83eba503-c094-4431-b85f-e7b4cc9d92de)
### Passos Iniciais Realizados Nesse Bootcamp Python AI Backend Developer. [dio_me](https://www.dio.me/)
### ✅Trabalhando com Listas em Python.

### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Declarando Listas:

```
frutas = ["laranja", "maca", "uva"]
print(frutas)

frutas = []
print(frutas)

letras = list("python")
print(letras)

numeros = list(range(10))
print(numeros)

carro = ["Ferrari", "F8", 4200000, 2020, 2900, "São Paulo", True]
print(carro)
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Acesso Direto:

```
frutas = ["maçã", "laranja", "uva", "pera"]

print(frutas[0])  # maçã
print(frutas[2])  # uva
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Indices Negativos:
```
frutas = ["maçã", "laranja", "uva", "pera"]

print(frutas[-1])  # pera
print(frutas[-3])  # laranja
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Matriz:
```
matriz = [
    [1, "a", 2],
    ["b", 3, 4],
    [6, 5, "c"]
]

print(matriz[0])  # [1, "a", 2]
print(matriz[0][0])  # 1
print(matriz[0][-1])  # 2
print(matriz[-1][-1])  # "c"
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Fatiamento:
```
lista = ["p", "y", "t", "h", "o", "n"]

print(lista[2:])  # ["t", "h", "o", "n"]
print(lista[:2])  # ["p", "y"]
print(lista[1:3])  # ["y", "t"]
print(lista[0:3:2])  # ["p", "t"]
print(lista[::])  # ["p", "y", "t", "h", "o", "n"]
print(lista[::-1])  # ["n", "o", "h", "t", "y", "p"]
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Iterar Listas:
```
carros = ["gol", "celta", "palio"]

for carro in carros:
    print(carro)


for indice, carro in enumerate(carros):
    print(f"{indice}: {carro}")
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Compreensao De Listas:
```
# Filtrar lista
numeros = [1, 30, 21, 2, 9, 65, 34]
pares = [numero for numero in numeros if numero % 2 == 0]
print(pares)

# Modificar valores
numeros = [1, 30, 21, 2, 9, 65, 34]
quadrado = [numero**2 for numero in numeros]
print(quadrado)
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Append:
```
lista = []

lista.append(1)
lista.append("Python")
lista.append([40, 30, 20])

print(lista)  # [1, "Python", [40, 30, 20]]
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Clear:
```
lista = [1, "Python", [40, 30, 20]]

print(lista)  # [1, "Python", [40, 30, 20]]

lista.clear()

print(lista)  # []
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Copy:
```
lista = [1, "Python", [40, 30, 20]]

lista.copy()

print(lista)  # [1, "Python", [40, 30, 20]]
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Count:
```
cores = ["vermelho", "azul", "verde", "azul"]

print(cores.count("vermelho"))  # 1
print(cores.count("azul"))  # 2
print(cores.count("verde"))  # 1
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Extend:
```
linguagens = ["python", "js", "c"]

print(linguagens)  # ["python", "js", "c"]

linguagens.extend(["java", "csharp"])

print(linguagens)  # ["python", "js", "c", "java", "csharp"]
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Index:
```
linguagens = ["python", "js", "c", "java", "csharp"]

print(linguagens.index("java"))  # 3
print(linguagens.index("python"))  # 0
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Pop:
```
linguagens = ["python", "js", "c", "java", "csharp"]

print(linguagens.pop())  # csharp
print(linguagens.pop())  # java
print(linguagens.pop())  # c
print(linguagens.pop(0))  # python
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Remove:
```
linguagens = ["python", "js", "c", "java", "csharp"]

linguagens.remove("c")

print(linguagens)  # ["python", "js", "java", "csharp"]
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Reverse:
```
linguagens = ["python", "js", "c", "java", "csharp"]

linguagens.reverse()

print(linguagens)  # ["csharp", "java", "c", "js", "python"]
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Sort:
```
linguagens = ["python", "js", "c", "java", "csharp"]
linguagens.sort()  # ["c", "csharp", "java", "js", "python"]
print(linguagens)

linguagens = ["python", "js", "c", "java", "csharp"]
linguagens.sort(reverse=True)  # ["python", "js", "java", "csharp", "c"]
print(linguagens)

linguagens = ["python", "js", "c", "java", "csharp"]
linguagens.sort(key=lambda x: len(x))  # ["c", "js", "java", "python", "csharp"]
print(linguagens)

linguagens = ["python", "js", "c", "java", "csharp"]
linguagens.sort(key=lambda x: len(x), reverse=True)  # ["python", "csharp", "java", "js", "c"]
print(linguagens)
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Len:
```
linguagens = ["python", "js", "c", "java", "csharp"]

print(len(linguagens))  # 5
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Sorted:
```
linguagens = ["python", "js", "c", "java", "csharp"]

print(sorted(linguagens, key=lambda x: len(x)))  # ["c", "js", "java", "python", "csharp"]
print(sorted(linguagens, key=lambda x: len(x), reverse=True))  # ["python", "csharp", "java", "js", "c"]
```
<h3 align="center"> Made with <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> by Dalila...</h3>
<div align="center"  style="display: inline-block">
  <a href="https://www.linkedin.com/in/dalila-cust%C3%B3dio-046076181/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href = "mailto:dalila.dalila70@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/dalila.dalila70" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a target="_blank" href="https://api.whatsapp.com/send?phone=5588997138541"><img  alt="Whatsapp" width="117px" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a> 
</div>










