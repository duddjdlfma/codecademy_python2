import java.util.Scanner;

public class Ascii_Change {
    public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
		
	System.out.println("숫자를 입력해주세요");
	int alpa = sc.nextInt();
	char calpa = (char)alpa;
		
	System.out.println(calpa);
    }
}
