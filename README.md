# 💳 Controle de Gastos com Cartão de Crédito  

## 📖 Descrição do Projeto  
Este projeto em **Java** simula o uso básico de um cartão de crédito.  
O usuário define o limite do cartão e registra várias compras com descrição e valor.  
O sistema verifica se há saldo disponível antes de aprovar cada compra e, no final, exibe o histórico e o saldo restante.  

Este código é ideal para praticar conceitos de **Programação Orientada a Objetos (POO)**, controle de fluxo e manipulação de listas em Java.  

---

## ⚙️ Como Instalar e Executar  

**Pré-requisitos**  
- Java JDK 8 ou superior instalado  
- Terminal ou IDE (Eclipse, IntelliJ, VS Code) para executar o código  

**Passo a passo (via terminal)**  
```bash
# 1. Compile todos os arquivos .java
javac Principal.java Compra.java CartaoDeCredito.java

# 2. Execute o programa
java Principal
```

Se estiver usando uma IDE, basta criar um projeto Java, adicionar os arquivos e executar a classe `Principal`.  

---

## 💡 Exemplo de Uso  

**Entrada/saída esperada no terminal:**  
```txt
Digite o limite do cartão: 
1000
Digite a descrição da compra:
Supermercado
Digite o valor da compra:
200
Compra realizada!
Digite 0 para sair ou 1 para continuar
1
Digite a descrição da compra:
Gasolina
Digite o valor da compra:
150
Compra realizada!
Digite 0 para sair ou 1 para continuar
0
***********************
COMPRAS REALIZADAS:

Supermercado - 200.0
Gasolina - 150.0

***********************

Saldo do cartão: 650.0
```

---

## 🚀 Contribuições Futuras  
Possíveis melhorias para o projeto:  
- Ordenar as compras por valor ou por ordem alfabética.  
- Permitir entrada de descrições com mais de uma palavra (usando `nextLine()` ao invés de `next()`).  
- Implementar remoção ou edição de compras.  
- Adicionar persistência dos dados em arquivo ou banco de dados.  
- Criar uma interface gráfica para facilitar o uso.
