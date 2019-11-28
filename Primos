import java.util.Scanner;

public class Numerosprimos {
	public static void main(String[]args) {
		Scanner sc = new Scanner(System.in);
		int n = 0;
		System.out.print("Digite um número: ");
		n = sc.nextInt();
		int c = 1;
		int p = n;
		String ser = "";
		
		while(c <= p) {
			n = c;
			if (n == 1) {
				ser = " é um número primo.";
						
				}
			if (n == 2) {
				ser = " é um número primo.";
				}
			for(int i = 2; i < n; i = i + 1) {
				float r = n % i;
				ser = " é um número primo.";
				
				if (r == 0) {
					ser = " não é um número primo.";
					break;
					}
			}
			System.out.println(c + ser);
			c = c + 1;
			
		}
	}
}
		
