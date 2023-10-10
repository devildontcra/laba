goots = []
shops = ["Ашан" , "Карусель" , "Хз"]
posts = []
isTrue = True
while isTrue == True:
   z = input(f"Введите название товара \n")
   if z != '':
     goots.append(z)
   else:
    isTrue = False


for goos in goots:
  goots_posts = []
  for shop in shops:
    prise = int(input(f"Введите цену на товар {goos} в магазине {shop}\n"))
    goots_posts.append(prise)
  posts.append(goots_posts)
bascet = []
for count , value in enumerate(shops):
  total = 0
  for idx , prodact in enumerate(goots):
    total+= posts[idx][count]
  print(f"стоимость корзины в магазине {value}: {total}")
  bascet.append(total)
min_dx = 0
min_value = None
for idx , value in enumerate(bascet):
  if min_value == None  or value < min_value:
    min_dx = idx
    min_value = value
print(f"минимальная цена в магазине {shops[min_dx]}")
