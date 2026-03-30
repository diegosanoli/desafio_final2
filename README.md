# 🎮 CODE - Missões de Estrutura de Dados em C#

Uma jornada gamificada para aprender Estruturas de Dados através de desafios práticos.

---

## 🛡️ Nível 1: Estruturas de Decisão (O Labirinto da Lógica)

### Conceito no Contexto de Estrutura de Dados
Estruturas de decisão (`if/else`, `switch`) são como as bifurcações em uma **Árvore de Decisão**. Elas permitem que o sistema avalie o estado atual de uma estrutura de dados (por exemplo, "esta lista está vazia?" ou "este nó é maior que o alvo?") e decida qual caminho o algoritmo deve seguir.

---

### 📜 Missão 1.1: A Porta do Inventário (10 XP)

**Descrição:** O jogador tem um Array que representa seu inventário de poções. Antes de usar uma poção de cura, ele precisa escrever uma condição que verifique se o tamanho do array é maior que zero. Se sim, ele "bebe a poção"; caso contrário, o sistema emite um alerta de "Inventário Vazio".

**Código Inicial:**
```csharp
using System;
class Program {
    static void Main() {
        string[] pocoes = { "Cura", "Mana" };
        
        // Verifique se pocoes.Length > 0
        // Se sim: Console.WriteLine("Poção consumida!");
        // Senão: Console.WriteLine("Inventário Vazio!");
    }
}
```

**Saída Esperada:**
```
Poção consumida!
```

---

### 📜 Missão 1.2: O Guardião da Fila (20 XP)

**Descrição:** Existe uma Fila (Queue) de prioridade para entrar na masmorra. O jogador deve criar uma estrutura de decisão que analise o nível do próximo jogador na fila. Se o nível for maior ou igual a 50, ele entra pela porta VIP; se for menor, vai para a porta de treinamento.

**Código Inicial:**
```csharp
using System;
class Program {
    static void Main() {
        int nivelJogador = 55;
        
        // Se nivelJogador >= 50: "Porta VIP liberada!"
        // Senão: "Vá para treinamento!"
    }
}
```

**Saída Esperada:**
```
Porta VIP liberada!
```

---

### 📜 Missão 1.3: Bifurcação na Árvore (30 XP)

**Descrição:** O aventureiro encontra uma Árvore Binária de busca. O baú do tesouro tem o valor 85. O jogador está no nó atual que vale 50. Ele deve escrever a regra de decisão: se o valor procurado é maior que o nó atual, vá para a direita; se for menor, vá para a esquerda.

**Código Inicial:**
```csharp
using System;
class Program {
    static void Main() {
        int noAtual = 50;
        int valorProcurado = 85;
        
        // Compare valorProcurado com noAtual
        // Maior: "Ir para DIREITA"
        // Menor: "Ir para ESQUERDA"
    }
}
```

**Saída Esperada:**
```
Ir para DIREITA
```

---



*Desenvolvido para a disciplina de Estrutura de Dados*
