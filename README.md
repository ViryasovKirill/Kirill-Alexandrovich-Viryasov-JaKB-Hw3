
import java.util.Scanner;

public class Game {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int x = scan.nextInt();
        int x1 = (int) Math.pow(x,3);
        int z =x1/10;
        int q = z % 7;
        System.out.println(q);
    }
}
