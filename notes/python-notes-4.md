# Estruturas de repetição

## `while` - *enquanto*

Ela roda o loop, **enquanto** a condição escrita for verdadeira. Deste modo, é necessário que essa condição também passe por uma atualização.

```python
1. Inicialização
2. Verificação
3. Atualização
```

```python
lancamento = False
numero = 1

while not lancamento :

  print(f'lança logo teamcherry #{numero}')
  numero += 1
  
  if numero == 40000 :
   lancamento = True

print("Finalmente lançou ...")
```

```python
numero = 10 # inicialização

while numero > 0 : # verificação
  print(numero) 
  numero -= 1 # atualização
```


