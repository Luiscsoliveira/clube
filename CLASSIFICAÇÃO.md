# clube
classificação baseada na média
import java.util.Scanner;

class pontuacao {

public static void main(String[] args){
        Scanner in = new Scanner(System.in);
        int pontuacao1, pontuacao2, pontuacao3, pontuacao4;
        String nome;
        System.out.println("Olá jogador");
        System.out.println("Qual o seu nome?");
        nome = in.nextLine();

        System.out.println("Digite sua primeira pontuação");
        pontuacao1 = in.nextInt();

        System.out.println("Digite sua segunda pontuação");
        pontuacao2 = in.nextInt();

        System.out.println("Digite sua terceira pontuação");
        pontuacao3 = in.nextInt();

        System.out.println("Digite sua quarta pontuação");
        pontuacao4 = in.nextInt();


        int media = (pontuacao1+pontuacao2+pontuacao3+pontuacao4)/4;
        if (media < 4) {
                System.out.println("Não se classificou, treine um pouco mais.");
        }
        else if (media >= 4) {System.out.println("Parabéns, você está na próxima fase!");
        }
                System.out.println(media);
        }

        public void pontuacao() {
        System.out.println("media");
        }
}
