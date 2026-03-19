import java.util.Scanner;

public class VelocidadeMedia {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Digite a distância (km): ");
        double distancia = scanner.nextDouble();

        System.out.print("Digite o tempo (h): ");
        double tempo = scanner.nextDouble();

        if (tempo == 0) {
            System.out.println("Erro: o tempo não pode ser zero.");
        } else {
            double velocidade = distancia / tempo;
            System.out.println("Velocidade média: " + velocidade + " km/h");
        }

        scanner.close();
    }
}

https://github.com/EnzoOliveiraCiarcia/Enzo-USJT/blob/53b96aea3f8a89026dabeeee7ffe5934bec876ae/Captura%20de%20tela%202026-03-19%20200121.png
