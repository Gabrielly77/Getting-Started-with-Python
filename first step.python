def achar_elemento(elem, arr):
  achou = False

  for i in range(len(arr)):
    if(arr[i] == elem):
       achou = True
    if(achou == False):
      print("Não achamos o elemento " + elem)

    else:
      print("Achamos o nome: " + elem)

nome = ["Rafael", "Arthur", "Karen", "Julia"]

achar_elemento("Rafael", nome)

def achar_elemento(arr):
  achou = False
  frase= ""

  while(not achou):
    print("Qual o nome você deseja procurar?")
    elem = input()

    for i in range(len(arr)):
      if(arr[i] == elem):
        achou = True
        indice = i

    if(achou == False):
      frase = "Não achamos o nome: " + elem
      print(frase)
    else:
      frase = "Achamos o nome: " + elem + "no indice" + str(indice)
      print(frase)

  nomes = ["Rafael", "Arthur", "Karen", "Julia"]

  nomes.append(input("Qual nome deseja adicionar?"))

  print(nomes)

def adicionar_produtos(array):
    lista_produtos = array.copy()
    print("Lista atual: " + str(lista_produtos))

    novo_produto = input('Informe o produto a ser cadastrado: ')
    lista_produtos.append(novo_produto)

    print("Lista atualizada: " + str(lista_produtos))
    return lista_produtos
produtos = ['Feijão', 'Arroz', 'Macarrão']
produtos_atualizados = adicionar_produtos(produtos)

produtos = ["Feijão", "Macarrão", "Carne"]

while True:
    print("Lista:")
    print("1 Adicionar produto")
    print("2 Listar produtos")
    print("3 Sair")

    opcao = input("Escolha um produto: ")

    if opcao == '1':
        novo_produto = input("Nome do produto: ")
        produtos.append(novo_produto)
        print(f"'{novo_produto}' adicionado.")
    elif opcao == '2':
        print("Produtos:", ", ".join(produtos) if produtos else "Nenhum produto.")
    elif opcao == '3':
        break
    else:
        print("Opção inválida.")
