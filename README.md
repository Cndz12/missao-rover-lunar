# Rover

## Descrição do Projeto

O **Rover** é um projeto desenvolvido em **Java** que simula a inicialização dos sistemas de um veículo explorador.

Ao executar o programa, são exibidas no console informações sobre o status dos principais sistemas do Rover, como os **painéis solares** e o **nível da bateria**.

O projeto tem como objetivo praticar conceitos básicos de programação em Java, como **classes, métodos e o método `main`**.

## Funcionalidades

-  Inicialização dos sistemas do Rover
-  Verificação dos painéis solares
-  Exibição do nível da bateria
-  Exibição das informações no console

## Código

```java
public class Rover {

    public static void inicializarRover() {
        System.out.println("Sistemas do Rover iniciados!");
        System.out.println("Painéis solares OK");
        System.out.println("Nível de bateria: 100%");
    }

    public static void main(String[] args) {
        inicializarRover();
    }

}
