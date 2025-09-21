# -ROLLY-devJUNIOR

print("🤖 Olá, eu sou teu primeiro bot em Python!")
while True:
    mensagem = input("Tu: ")
    if mensagem.lower() in ["oi", "olá", "hello"]:
        print("Bot: Oi Rolly, tudo bem?")
    elif mensagem.lower() in ["tchau", "sair"]:
        print("Bot: Até logo!")
        break
    else:
        print("Bot: Não entendi, tenta outra coisa.")
