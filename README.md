# 1011beecrowd
Beecrowd beginner problem 1011 solution with java code <br>
import java.util.Scanner; //<br>
import java.text.DecimalFormat; //<br>
public class bla {

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int r = s.nextInt();
        double volume = (4.0/3) * r*r*r * 3.14159;
        DecimalFormat f = new DecimalFormat("#.000");
        System.out.println("VOLUME = " + f.format(volume));
        s.close();
    }
}
