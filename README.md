## Atividades - Kotlin

### Atividade sobre IMC 🏋️

```
fun main(){
    
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    
    var imc = peso / (altura * altura)
    
    if(imc < 18.5){
        print("Abaixo do peso, seu imc é: " + imc)
    }else if(imc >= 18.5 && imc <= 24.9){
        print("Peso normal, seu imc é: " + imc)
    }else if(imc >= 25 && imc <= 29.9){
        print("Sobrepeso (acima do peso desejado), seu imc é: " + imc)
    }else{
        print("Obesidade, seu imc é: " + imc)
    }
    
    
}

```

### Atividade sobre a construtora 👷‍♂️

#### Questao A ⏹️:

```
fun main(){
    
    val comprimento = readln().toDouble()
    val largura = readln().toDouble()
    
    var area = largura * comprimento
    
    print("A area total é: " + area)
}
```

#### Questão B 👌:

```
fun main(){
    
    val comprimento = readln().toDouble()
    val largura = readln().toDouble()
    
    
    
    var area = largura * comprimento
    var servente = (area / 10) * 2
    var engenheiro = area / 100
    
    
    if(area >= 10 && area < 100){
        print("Voce precisa de 1 mestre de obra, sua area é de: " + area + "M². E voce precisa de " + servente + "serventes")
    }else if(area >= 100){
        print("Voce precisa de 1 mestre de obra, sua area é de: " + area + "M². Voce precisa de " + servente + "serventes e " + engenheiro + "engenheiro")
    }
    else{
        print("A empresa não realizara sua obra. Sua area é de: " + area + "M².")
    }
}
```

#### Questão C 👷‍♂️:

```
fun main(){
    
    val comprimento = readln().toDouble()
    val largura = readln().toDouble()
    
    
    
    var area = largura * comprimento
    var valor_area = (area / 10) * 4500
    var quarto_sem_suite = 12000
    var area_de_servico =  15000
    var piscina = 27550
    var quarto_com_suite = 17000
    var banheiro = 5000
    
    
    var valor_total = valor_area + quarto_sem_suite + area_de_servico + piscina + quarto_com_suite + banheiro
    print("o Valor total é: " + valor_total + ", Sua area total é de: " + area)
}
```

#### Questão D ➕:

```
fun main(){
   
    val comprimento = readln().toDouble()
    val largura = readln().toDouble()
   
   
   
    var area = largura * comprimento
    var mestre = 1
    var servente = (area / 10) * 2
    var engenheiro = area / 100
   
    var valor_mestre_de_obra = mestre * 3500
    var valor_servente = servente * 1900
    var valor_engenheiro = engenheiro * 11000
    var valor_trabalho = valor_engenheiro + valor_servente + valor_mestre_de_obra
    println("area da obra: " + area + "m²")
    println("Mestre de obra: " + mestre)
    println("serventes: " + servente)
    println("Engenheiro: " + engenheiro)
    println("Valor total da mao de obra: " + valor_trabalho)
   
   
}
```


#### Questão E 🤓:
```
fun main(){
    
    val comprimento = readln().toDouble()
    val largura = readln().toDouble()
    
    
    
    var area = largura * comprimento
    var mestre = 1
    var servente = (area / 10) * 2
    var engenheiro = area / 100
    
    
    var valor_area = (area / 10) * 4500
    var quarto_sem_suite = 12000
    var area_de_servico =  15000
    var piscina = 27550
    var quarto_com_suite = 17000
    var banheiro = 5000
    var valor_mestre_de_obra = mestre * 3500
    var valor_servente = servente * 1900
    var valor_engenheiro = engenheiro * 11000
    var valor_total = valor_area + quarto_sem_suite + area_de_servico + piscina + quarto_com_suite + banheiro
    var valor_trabalho = valor_engenheiro + valor_servente + valor_mestre_de_obra
    var lucro = (valor_total * 0.25) 
    println("area da obra: " + area + "m²")
    println("Mestre de obra: " + mestre)
    println("serventes: " + servente)
    println("Engenheiro: " + engenheiro)
    println("Valor total da mao de obra: " + valor_trabalho)
    println("o Valor total é: " + valor_total)
    println("O lucro para a empresa: " + lucro)
    

```
}
