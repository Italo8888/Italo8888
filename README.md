

```python
 casa de apostas

saldo = 1000  # Saldo inicial do usuário

def realizar_aposta(valor_aposta, odd):
    global saldo
    
    if saldo >= valor_aposta:
        saldo -= valor_aposta
        ganho_potencial = valor_aposta * odd
        
        if resultado_aposta():
            saldo += ganho_potencial
            print("Parabéns! Você ganhou a aposta e recebeu um lucro de", ganho_potencial)
        else:
            print("Que pena! Você perdeu a aposta.")
        
        print("Seu saldo atual é de", saldo)
    else:
        print("Saldo insuficiente para realizar a aposta.")

def resultado_aposta():
    # Lógica para determinar o resultado da aposta
    # Retorna True se o usuário ganhou a aposta, False caso contrário
    pass


realizar_aposta(100, 2.5)  # Realiza uma aposta com valor de 100 e odd de 2.5
```

- 👋 Hi, I’m @Italo8888
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Italo8888/Italo8888 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
