# ListaJava1

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double nota;

        while (true) {
            System.out.print("Digite uma nota entre zero e dez: ");
            nota = scanner.nextDouble();

            if (nota >= 0 && nota <= 10) {
                System.out.println("Nota válida: " + nota);
                break;
            } else {
                System.out.println("Valor inválido! Por favor, digite uma nota entre zero e dez.");
            }
        }
    }
}
