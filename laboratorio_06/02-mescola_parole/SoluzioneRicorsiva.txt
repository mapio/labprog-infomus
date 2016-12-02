import java.util.Scanner;

public class SoluzioneRicorsiva {
    public static void stampa(String s, String t) {
        if (s.length() > 0) {
            System.out.print(s.charAt(0));
            s = s.substring(1);
        }
        if (t.length() > 0) {
            System.out.print(t.charAt(0));
            t = t.substring(1);
        }
        if (s.length() > 0 || t.length() > 0) stampa(s, t);
    }

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        String prima = s.next();
        String seconda = s.next();
        stampa(prima, seconda);
        System.out.println();
    }
}
