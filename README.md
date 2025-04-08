# Hora-de-Codar-8
Exercicio
# 🐾 Virtual Pet Simulator em Kotlin  

Um simulador de animal de estimação virtual que ensina **Programação Orientada a Objetos (POO)** em Kotlin, onde você cuida de um pet com atributos dinâmicos e evita condições de game over.

## 🎯 Objetivo  
Manter seu pet vivo e feliz até ele completar **50 dias**, gerenciando atributos como fome, felicidade e cansaço.

## 🛠️ Funcionalidades  
### Atributos do Pet  
- `nome`, `idade`, `fome`, `felicidade`, `cansaço`, `vontadeBanheiro`, `sujeira`  

### Ações do Jogador  
- **Alimentar**: ↓ Fome, ↑ Vontade de Banheiro  
- **Brincar**: ↑ Felicidade, ↑ Cansaço, ↑ Sujeira  
- **Descansar**: ↓ Cansaço (baseado em horas)  
- **Ver Status**: Exibe todos os atributos  

### Regras  
- **Derrota se**:  
  - Fome ou cansaço ≥ 100  
  - Felicidade ≤ 0  
  - Vontade de Banheiro ou Sujeira ultrapassarem limites  
- **Vitória**: Idade ≥ 50 dias  

## 📥 Como Executar  
1. Clone o repositório:  
   ```bash  
   git clone [URL_DO_REPO]  
   ```  
2. Abra no Android Studio ou IDE Kotlin.  
3. Execute `main()` em `PetSimulator.kt`.  

## 💡 Tecnologias  
- **Kotlin** (JDK 11+)  
- Paradigma **Orientado a Objetos**  

## � Exemplo de Código  
```kotlin  
class Pet(val nome: String) {  
    var idade: Int = 0  
    var fome: Int = 30  
    // ... outros atributos  

    fun alimentar() {  
        fome -= 10  
        vontadeBanheiro += 15  
    }  
}  
```  

## 📌 Melhorias Futuras  
- Adicionar interface gráfica (Compose/Android)  
- Sistema de save/load com `SharedPreferences` ou arquivos JSON  

---
```  

### Principais Adaptações para Kotlin:  
1. **Sintaxe**: Uso de `class`, `var/val`, e funções Kotlin.  
2. **Extensibilidade**: Destaque para integração com Android (opcional).  
3. **Exemplo Prático**: Trecho de código Kotlin para ilustrar a classe `Pet`.  

