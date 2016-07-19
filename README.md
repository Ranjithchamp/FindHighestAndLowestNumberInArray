# FindHighestAndLowestNumberInArray
import java.util.Arrays;
import java.util.Scanner;

public class HigestAndLowestNumberInArray {

	public static void main(String[] args) {
	
		Scanner get= new Scanner(System.in);
		System.out.println("Enter array Size");
		int n=get.nextInt();
		int array[]=new int[n];
		for(int i=0;i<array.length;i++)
		{
			array[i]=get.nextInt();
		}
		System.out.println("enter array values");
		Arrays.sort(array);
		System.out.println("Higest Number = "+array[array.length-1]);
		System.out.println("Lowest Number = "+array[0]);

	}

}
