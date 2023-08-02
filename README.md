while True:
    resposta = input("Digite 'sim' para continuar: ").strip().lower()
    if resposta == "sim":
        print("Continuando...")
        break
    else:
        print("Resposta inválida. Tente novamente.")
