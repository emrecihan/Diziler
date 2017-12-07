package diziler;

import java.util.Scanner;

public class dizilerornek1 {

	public static void main(String[] args) {
		//girilen değerleri atayıp yazan program.....
		
		Scanner input=new Scanner(System.in);
		int boyut=5;
		int boyut2;
		System.out.println("kaç sayı girilecek : ");
		boyut2=input.nextInt();
		
		int[]dizi1=new int[boyut2];
		
		for(int i=0; i<boyut2; i++)
		{
			System.out.println(i+"değerleri giriniz : ");
			dizi1[i]=input.nextInt();
		}
		for(int i=0; i<boyut2; i++)
		{
			System.out.println(i+1 +" = "+ dizi1[i]+ ", ");
		}
		
	}

}
