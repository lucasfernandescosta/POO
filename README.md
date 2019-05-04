# Exercícios POO

**1-O que é um objeto?**<br />
R:É uma coisa, entidade, qualquer coisa que possa imaginar e que tenha uma identidade, qualquer coisa que podemos dar um nome.

**2-Identifique 3 características e 3 comportamentos de um carro.**<br />
R:3 características: Cor vermelha, pesa 1000kg, 1,5 metros de altura
  3 comportamentos: parado, em movimento, trancado
  
**3- No contexto de Orientação a Objetos, as características e comportamentos são chamados respectivamente de?**<br />
R: Atributos e métodos

**4- Qual é o objetivo da programação orientada à objetos?**<br />
R: A programação orientada a objetos tem como principais objetivos reduzir a complexidade no desenvolvimento de software e aumentar sua produtividade e a ideia fundamental é tentar simular o mundo real dentro do computador

**5- O que é abstração? Cite um exemplo.**<br />
R: É um processo pelo qual se isolam características de um objeto, considerando os que tenham em comum certos grupos de objetos, a abstração mostra que não devemos nos preocupar com características menos importantes, apenas nos aspectos essenciais, facilitando com um contexto inicial modelar necessidades especificas. Um exemplo de abstração é se uma fabrica de cadeiras fosse representar os produtos que ela já fabrica ou que fabricará, ela pode pensar inicialmente em uma cadeira de forma mais básica (abstrata), com isso seu processo de produção seria facilitado, pois, a partir dessa forma poderia ser fabricado formas especificas (cadeira de praia, cadeira de avião, etc.).

**6- O que é classe?**<br />
R: Uma classe descreve os serviços oferecidos por seus objetos e quais informações eles podem armazenar. Ou seja, o objetivo de uma classe é definir, servir de base, para o que futuramente será o objeto. É através dela que criamos o "molde" aos quais os objetos deverão seguir. Este "molde" definirá quais informações serão trabalhadas e como elas serão manipuladas. 

**7- Qual é o padrão utilizado para nomear as classes? Cite um exemplo.**<br />
R: Toda classe deve começar com uma letra maiúscula, não pode conter letras não ASCII, caso composto por mais de uma palavra, a primeira letra de cada palavra deve ser maiúscula, O nome da classe deve fazer referência total ao seu objeto. Exemplo: ImpostoDeRenda.

**8- Qual opção apresenta corretamente o nome da classe carro elétrico?**<br />
1. carroeletrico <br />
2. carroEletrico  <br />
3. Carroeletrico  <br />
4. CarroEletrico <br />
5. carro eletrico <br />
R:4

**9.	Qual é o padrão utilizado para nomear os atributos? Cite um exemplo.**<br />
R: Devem iniciar com minúscula. Palavras internas começam com letras maiúsculas. Não deve começar com underline ou $, mesmo que ambos sejam permitidos. Exemplo: quantPatas

**10.	Qual opção apresenta corretamente o nome do atributo cor de fundo?**<br />
1. CordeFundo<br /> 
2. CorDeFundo <br />
3. corDeFundo <br />
4. _cor_de_fundo <br />
5. _corDeFundo <br />
6. mCorDeFundo<br />
R:3

**11.	Qual é o padrão utilizado para nomear os métodos? Cite um exemplo.**<br />
R:Métodos devem ser verbos, com a letra minúscula em primeiro lugar, com a primeira letra de cada palavra interna em maiúscula. Exemplo: calcularAlgo()

**12.	Qual opção apresenta corretamente o nome do método está vazio? **<br />
1. estaVazio  <br />
2. estaVazio <br />
3. estavazio <br />
4. EstaVazio <br />
5. Estavazio <br />
6. Esta vazio<br />
R:1
<br />

**13.	No contexto de orientação à objetos, o que é um objeto? Em que momento existe um objeto? Quando ele deixa de existir?**<br />
R: Um objeto é a representação de um conceito/entidade do mundo real, que pode ser física (bola, carro, árvore etc.) ou conceitual (viagem, estoque, compra etc.) e possui um significado bem definido para um determinado software. Para este conceito/entidade, deve ser definida inicialmente uma classe a partir da qual posteriormente serão instanciados objetos distintos. O objeto deixa de exixstir ou seja é destruido quando não é mais utilizado ou não necessário no contexto.

**14.	Qual é o objetivo do operador new?**<br />
R: new é utilizado para criar uma nova instância de uma determinada classe, o new faz com que a máquina virtual aloque memória para armazenar um novo objeto

**15.	O que é o construtor? Qual é o seu objetivo? Qual deve ser o seu nome? Cite um exemplo.**<br />
R: O construtor é um método especial. O construtor é responsável por criar objetos a partir da classe em questão, sempre que for necessário criar objetos de uma determinada classe, o construtor deverá ser utilizado. O nome deve ser igual ao da classe e sem retorno, pode ou não ter parâmetros. Exemplo: Carro () {//o que deseja na construção do objeto}

**16.	Caso o construtor da classe Aluno não for declarado, qual será o seu construtor?**<br />
R:O seu construtor vai ser o padrão do Java

**17.	Crie um exemplo de instanciação da classe Aluno. Utilize o construtor padrão.**<br />
R: Aluno aluno = new Aluno();

**18.	O que é encapsulamento?**<br />
R: Encapsulamento é a técnica que faz com que detalhes internos do funcionamento dos métodos de uma classe permaneçam ocultos para os objetos. Uma vantagem deste princípio é que as mudanças se tornam transparentes

**19.	Qual é o objetivo do modificador de acesso public?**<br />
R:Uma declaração com o modificador public pode ser acessada de qualquer lugar e por qualquer entidade que possa visualizar a classe a que ela pertence.

**20.	Qual é o objeto do modificador de acesso private?**<br />
R:Os membros da classe definidos como não podem ser acessados ou usados por nenhuma outra classe. Esses atributos e métodos também não podem ser visualizados pelas classes herdadas.

**21.	Como é aplicado o encapsulamento em uma classe? Considere a classe Aluno com o atributo matrícula.**<br />
R:public class Aluno {
  private long matricula;
}

**22.	Qual é o objetivo dos métodos getters? Crie um exemplo.**<br />
R: Os métodos getters tem como objetivo acessar e chamar o método private
  public String getNome() {
        return nome;
    }

**23.	Qual o objetivo dos métodos setters? Crie um exemplo.**<br />
R:Os métodos setters tem como objetivo acessar e altarar o métodos private
  public void setNome(String nome) {
        this.nome = nome;
    }
**24.	O diagrama de classe UML é composto por 3 partes. O que vai em cada parte?**<br />
R:Nome:Será informado o nome da classe
  Atributos:Será informado os atributos da classe
  Métodos:Será informado os métodos da classe
**25.	Qual é o padrão utilizado para representar um atributo no diagrama de classe UML? Crie um exemplo.**<br />
R:É utilizado o nome dos atributos e qual tipo de variável é esse atributo.
Exemplo:marca:String
        ano:Int
        placa:Int

**26.	Qual é o padrão utilizado para representar um método no diagrama de classe UML? Crie um exemplo.**<br />
R: +tipo(public,private,etc.) verbo () 
    +getPessoa()
**27.	Como o construtor de uma classe pode ser diferenciado no diagrama de classe UML? Crie um exemplo.**<br />
R: <<create>>, exemplo: Cliente(): <<create>>

**28.	Quais são os símbolos utilizados no diagrama de classe UML para representar os modificadores de acessos aos atributos e métodos? Crie um exemplo.**<br />
R: "+" public "-" private
ex: <<crete>> -Pessoa(nome:String, altura:Float):

**29.	Considere a classe Cliente, com os atributos nome, email e telefone com os respectivos métodos getters e setters. Desenvolva o diagrama de classe UML.**<br />
R:  
     Cliente<br />
    ---------------------------<br />
    -nome:String<br />
    -email:String<br />
    -telefone:long<br />
    ----------------------------<br />
    +getNome():String<br />
    +setNome(nome:String)<br />
    +getEmail():String<br />
    +setEmail(email:String)<br />
    +getTelefone():long<br />
    +setTelefone(telefone:long)<br />
    ----------------------------<br />
    

**30.	Considere a classe Cliente apresentada no Problema 29, e desenvolva o código Java correspondente.**<br />
R:  
```java
public class Cliente{
  private String nome;
  private String email;
  private long telefone;
  
  public Cliente(){
      this.nome="kaue";
      this.email="kaue@gmail.com";
      this.telefone=33334444;
  }
  public String getNome(){
    return nome;
  }
  public void setNome (String nome){
    this.nome = nome
  }
  public String getEmail(){
    return email;
  }
  public void setEmail (String email){
    this.email = email
  }
  public long getTelefone(){
    return telefone;
  }
  public void setTelefone (String telefone){
    this.telefone =telefone
  }
}
```
**31. Desenvolva o código java das classes do apresentadas no diagrama de classes
UML abaixo:**

R:
```java
public class Produto{
  private String nome;
  
  public Produto()
    this.nome="kaue";
  }
  public String getNome(){
    return nome;
  }
  public void setNome (String nome){
    this.nome = nome
  }
  
}
------------------------------------
public class Password{
  private String value;
 
  public Password(){
    this.value="kaue";
  }
  public boolean isEqual(Password p){
    return false;
  }
  
}
---------------------------------------
public class Animal{
  private boolean alive;
  
  public Animal(){
    this.alive= true;
  }
  public boolean isAlive(){
    return false;
    }
  <br />
    private void die(){
  }
  
  }
-------------------------------------
```
**32. Desenvolva o diagrama de classe dos códigos Java abaixo. **
R:

Livro<br />
-----------------------------<br />
-nome: String<br />
-----------------------------<br />
+getNome(nome): String<br />
+setNome(nome: String)<br />

ContaCorrente<br />
---------------------------<br />
-saldo: double<br />
----------------------------<br />
+sacar(double valor):0.0<br />
+depositar(valor)<br />
-recalcularSaldo()<br />
-----------------------------<br />

Par<br />
-----------------------------<br />
+chave: String<br />
+valor: String<br />
-----------------------------<br />
-----------------------------<br />

Impressora<br />
-----------------------------<br />
-----------------------------<br />
+imprimir()

**33.O que é o estado de um objeto? Cite um exemplo com a classe Aluno com
os atributos nome, idade, matrícula e curso. Utilize o diagrama de estado de
objeto.**
R:O que define o Estado são os valores atribuídos aos atributos de um objeto. Diferentemente do Comportamento que são os métodos da classe.
exemplo:
Inicio     Nome         Idade        Matrícula         curso        Fim
  o--------João----------20------------1001----------Matemática------o

**34.Qual é o estado do objeto da classe Dog quando é inicializado? Desenvolva o
diagrama de objetos.**
R:
Inicio     Nome         Idade          vivo      Fim
  o--------?--------------?--------------?--------o

**35.Qual é o estado do objeto dog no final da execução do método main? Desenvolva o diagrama de objetos.**
R:
Inicio     Nome         Idade          vivo      Fim
o----------Spike---------10------------True--------o

**36.Qual é o estado do objeto pug e buldog após a execução da linha 6? Desenvolva
o diagrama de objetos.**
R:
Inicio     Nome         Idade    Idade    Fim
   o-----Floquinho-------2---------1-------o
   
**37.Analise o código abaixo. Verifique se existem problemas, caso sim, indique o
problema e sugere as correções.**
R: Não encontrei problemas



















