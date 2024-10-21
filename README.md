# 📢 *Aprendizados de Técnicas de Programação e Algoritmos - ETEC 2024*

Este Componente Curricular tem como objetivo proporcionar um aprendizado profundo sobre Técnicas de Programação por meio da utilização de algoritmos e exemplos práticos, empregando a linguagem de programação estruturada em Portugol. 

Os principais conceitos abordados incluem:

- *Variáveis*: Compreensão e utilização de variáveis para armazenar dados.
- *Estruturas de Controle*: Análise das estruturas condicionais que permitem tomar decisões dentro dos algoritmos.
- *Estruturas de Repetição*: Estudo das estruturas que possibilitam a execução repetida de um bloco de comandos.
- *Vetores e Matrizes*: Manipulação de coleções de dados, permitindo o armazenamento e a organização eficiente das informações.

Adicionalmente, estes conhecimentos exploram a conversão de algoritmos escritos em Portugol para diversas linguagens de programação, incluindo Python, Java e PHP. Essa abordagem visa facilitar a transição do conhecimento teórico para a prática em diferentes ambientes de desenvolvimento.

# *Lógica de Programação*

É a técnica de desenvolver sequências lógicas para atingir um determinado objetivo.

Nada mais é que a organização coerente das instruções do programa, para que seu objetivo seja alcançado (algoritmo).

Algoritmo: É um fluxo computacional criado para resolver um problema (receita/roteiro).

- *Descrição narrativa*;
- *Fluxograma convencional*;
- *Linguagem estruturada ou Portugol*.

# *Primeiros Passos com Algoritmos*

O estudo de algoritmos representa o alicerce fundamental para a compreensão da programação. Nos primeiros passos, é essencial desenvolver a habilidade de pensar de forma lógica e estruturada, o que permite a formulação de soluções para problemas diversos. 

Inicia-se com a definição de um algoritmo como uma sequência finita de instruções que visa resolver uma determinada questão ou executar uma tarefa específica. Para isso, são utilizadas representações gráficas, como fluxogramas, e linguagens formais, como o Portugol, que auxiliam na visualização e organização do raciocínio.

Os conceitos básicos, como variáveis e estruturas de controle, são introduzidos de maneira prática, permitindo que o aprendiz compreenda a importância da lógica na programação. A experiência prática associada à teoria é fundamental para consolidar o aprendizado e fomentar a criatividade na resolução de problemas.

# *1- Introdução aos Algoritmos*

Algoritmos são sequências de passos ou instruções claras e finitas que visam resolver um problema específico ou realizar uma tarefa. Eles são fundamentais na programação e na ciência da computação, pois permitem que computadores executem operações de forma eficiente e sistemática. Um algoritmo pode ser expresso em diversas formas, como pseudocódigo, fluxogramas ou linguagens de programação. A eficácia de um algoritmo é avaliada pela sua clareza, eficiência e capacidade de resolver o problema proposto.

![image](https://github.com/user-attachments/assets/be60f6d2-bc77-4c89-9271-eba7e3bade37)

# *2- Estruturas Condicionais*

As estruturas condicionais em Algoritmos usando Portugol permitem que o programa tome decisões com base em condições específicas. As principais são:

## *Se (If)* 
Executa um bloco de código se uma condição for verdadeira.

   portugol
   
   se (condicao) {
   
       // código a ser executado
       
   }
   

## *Senão (Else)* 
Executa um bloco de código se a condição do "se" for falsa.

   portugol
   
   se (condicao) {
   
       // código se verdadeiro
       
   } senão {
   
       // código se falso
       
   }
   

## *Se-Senão Se (Else If)* 
Permite testar múltiplas condições.

   portugol
   
   se (condicao1) {
   
       // código para condicao1
       
   } senão se (condicao2) {
   
       // código para condicao2
       
   } senão {
   
       // código se nenhuma condição for verdadeira
       
   }
   

Essas estruturas ajudam a controlar o fluxo do programa, permitindo reações diferentes a diversas entradas ou situações.

![image](https://github.com/user-attachments/assets/d7be9307-dc08-4945-b399-afb30005efb9)

## *Escolha Caso*
A estrutura condicional *Escolha Caso* em Portugol é usada para selecionar uma entre várias opções com base no valor de uma variável. É uma forma mais organizada de lidar com múltiplas condições, evitando muitos "se" e "senão".

portugol

escolha (variavel) {

    caso valor1:
    
        // código para valor1
        
    caso valor2:
    
        // código para valor2
        
    ...
    
    caso outro:
    
        // código se nenhum valor corresponder
        
}

![image](https://github.com/user-attachments/assets/0cc43aa6-ad2d-42f8-a258-27ba7a648bbf)

# *3- Laços de Repetição (Loops)*
Os laços de repetição, ou *loops*, em Portugol permitem executar um bloco de código várias vezes, enquanto uma condição for verdadeira ou até que uma condição específica seja atendida.

## *Para*
O laço de repetição *Para (For)* em Portugol é utilizado quando se conhece o número exato de iterações que devem ser realizadas. Ele é muito útil para percorrer sequências ou realizar operações repetidas um número determinado de vezes.

portugol

para (variavel de inicio até fim passo passo) {

    // código a ser executado
    
}

![image](https://github.com/user-attachments/assets/95781305-aad6-4379-abfe-52196b37d6f4)

## *Enquanto*
O laço de repetição *Enquanto (While)* em Portugol é usado para executar um bloco de código enquanto uma condição específica for verdadeira. É ideal para situações em que não se sabe o número exato de iterações, mas se deseja continuar até que uma condição mude.

portugol

enquanto (condicao) {

    // código a ser executado
    
}

![image](https://github.com/user-attachments/assets/ecb04377-e5fb-44db-b65b-8bdfa82f8568)

## *Faça...enquanto*
O laço de repetição *Faça...enquanto* em Portugol executa um bloco de código pelo menos uma vez antes de verificar a condição. A estrutura básica é:

portugol

faça {

    // Código a ser executado
    
} enquanto (condição)

![image](https://github.com/user-attachments/assets/6c050a97-346a-4da2-a038-7cd3fc2830cf)

# *4- Vetores*
Os vetores em Portugol são estruturas que permitem armazenar uma coleção de múltiplos valores do mesmo tipo de forma sequencial. Eles oferecem uma maneira eficiente de organizar e manipular dados, possibilitando o acesso a cada elemento por meio de índices que começam em 0. Com os vetores, é possível realizar operações como iteração, busca e ordenação de forma simplificada e organizada.

Os vetores em Portugol são estruturas que permitem armazenar uma coleção de valores do mesmo tipo de forma sequencial. A estrutura básica é:

portugol
vetor nome[quantidade]: tipo


### Características:
- Os elementos são acessados por índices, começando em 0.
- Permitem armazenar e manipular múltiplos dados com uma única variável.
- Facilitam operações como iteração, busca e ordenação de maneira organizada.











# *Conclusão*

Ao final deste processo de aprendizado, espera-se que o estudante não apenas domine os conceitos fundamentais relacionados aos algoritmos, mas também desenvolva uma mentalidade crítica e analítica. A capacidade de converter ideias em soluções programáticas abre um leque de oportunidades no campo da tecnologia da informação. Assim, este projeto visa preparar os alunos para os desafios do mundo digital contemporâneo, equipando-os com as ferramentas necessárias para se tornarem programadores competentes e inovadores.
