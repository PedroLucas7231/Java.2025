public class OperacoesMatematicas {
    public static void main(String[] args) {
        double som, sub, div, mul;

        som = 12 + 3;
        sub = 7 - 2;
        div = 2.0 / 2.0; // Uso de números decimais para divisão
        mul = 2 * 3;

        System.out.println("A soma de 12 + 3 é igual: " + som);
        System.out.println("A subtração de 7 - 2 é: " + sub);
        System.out.println("2 / 2 é: " + div);
        System.out.println("2 * 3 é: " + mul);
    }
}


// Programa que imprime números de 100 a 200 usando "while"
public class Contagem {
    public static void main(String[] args) {
        int cont = 101;
        while (cont > 100 && cont < 200) {
            System.out.println("Contagem: " + cont);
            cont++;
        }
    }
}

// Programa que lê dois números e exibe sua soma
import java.util.Scanner;

public class Soma {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o primeiro número: ");
        double num1 = scanner.nextDouble();
        System.out.print("Digite o segundo número: ");
        double num2 = scanner.nextDouble();
        
        double resultado = num1 + num2;
        System.out.println("A soma é: " + resultado);
        
        scanner.close();
    }
}

// Programa que demonstra operações matemáticas básicas
public class OperacoesMatematicas {
    public static void main(String[] args) {
        double som = 12 + 3;
        double sub = 7 - 2;
        double div = 2 / 2.0;
        double mul = 2 * 3;

        System.out.println("A soma de 12 + 3 é igual: " + som);
        System.out.println("A subtração de 7 - 2 é: " + sub);
        System.out.println("2 / 2 é = " + div);
        System.out.println("2 * 3 é: " + mul);
    }
}

// Programa que recebe quatro tipos de variáveis e exibe seus valores
public class TiposDeVariaveis {
    public static void main(String[] args) {
        int a = 7;
        double b = 5.23;
        String c = "Boa noite";
        boolean d = true;

        System.out.println("Este é meu número inteiro: " + a);
        System.out.println("Este é meu número real: " + b);
        System.out.println("Este é meu caractere: " + c);
        System.out.println("Este é meu booleano: " + d);
    }
}

// Programa que calcula a média de um aluno
import java.util.Scanner;

public class MediaAluno {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite seu nome: ");
        String nome = scanner.nextLine();
        System.out.print("Digite a nota 1: ");
        double nota1 = scanner.nextDouble();
        System.out.print("Digite a nota 2: ");
        double nota2 = scanner.nextDouble();
        System.out.print("Digite a nota 3: ");
        double nota3 = scanner.nextDouble();
        
        double media = (nota1 + nota2 + nota3) / 3;
        System.out.println("Aluno: " + nome);
        System.out.println("A média da sua nota é: " + media);
        
        scanner.close();
    }
}

// Programa que troca valores entre variáveis
import java.util.Scanner;

public class TrocaValores {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite um número inteiro para A: ");
        int A = scanner.nextInt();
        System.out.print("Digite um número inteiro para B: ");
        int B = scanner.nextInt();
        
        int invertidaA = B;
        int invertidaB = A;
        
        System.out.println("O número invertido de A: " + invertidaA);
        System.out.println("O número invertido de B: " + invertidaB);
        
        scanner.close();
    }
}

// Programa que calcula salário final de um vendedor
import java.util.Scanner;

public class SalarioVendedor {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite o nome do funcionário: ");
        String nome = scanner.nextLine();
        System.out.print("Digite o valor do salário: ");
        double salario = scanner.nextDouble();
        System.out.print("Digite o valor das vendas: ");
        double vendas = scanner.nextDouble();
        
        double salarioFinal = (vendas * 0.15) + salario;
        System.out.println("Funcionário: " + nome);
        System.out.println("Salário final é: " + salarioFinal);
        
        scanner.close();
    }
}
