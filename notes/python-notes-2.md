# Estruturas Condicionais

## `if`

Tradução: **Se**

```python
nota = 7.2

if nota > 7 :
  print('aprovado')
```

## `if-else`

Tradução: **Se-Senão**

```python
agua = True

if agua == True :
  print('consigo matar a sede')
else :
  print('vou ter que procurar outra coisa')
```

## `if-elif-else`

`elif` é uma abreviação de `else if`.

```python
nota = 7.2

if nota >= 7.0 : # a nota é maior que 7 ?
  print('aprovado')
elif nota >= 4.0 : # senão essa nota é maior que 4?
  print('recuperação')
else: # caso não seja nehuma das acima :
  print('reprovado')
```

## `and` + `or`

```python
agua = True
cafe = True

if agua and cafe :
  print('consigo fazer um cafezinho :)')
else 
  print('não consigo fazer cafe ;-;')
```

```python
agua = True
suco = False

if agua or suco :
  print('consigo matar a sede')
else:
  print('nao consigo')
```