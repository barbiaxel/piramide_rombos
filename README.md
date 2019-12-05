# piramide_rombos
Dibuja pirámide con rombos
public class piramide_rombos {
	public static void main (String[] args) {
		int i, j, k;
		for (i = 1; i <= 3; i++) {//bucle que cuenta hasta 10
			for (k = 1; k <= 3-i; k++) {
				System.out.print( " ");
			}
			for (j = 1; j <= 2 * (i-1)+ 1; j++) {
				System.out.print( "*");
			}
			System.out.println( "");
		}
	}	
}
