import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int p = sc.nextInt();
        int x = sc.nextInt();
        int y = sc.nextInt();

        int val = x*100 + y;
        float p1 = (float)p/100;
        float newValue = val + val * p1;
        System.out.println((int)newValue/100 + " " + (int)newValue % 100);
    }
}
