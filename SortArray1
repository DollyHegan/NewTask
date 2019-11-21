import java.util.Scanner;
public class SortArray1{
	public static void main(String[]args){
		Scanner sc=new Scanner(System.in);
		System.out.print("The length of the array: n = ");
		int n = sc.nextInt();
		while(n<0){
			System.out.println("Eror. Wrong data.");
			System.out.println();
			System.out.print("The length of the array: n = ");
			n = sc.nextInt();
		}

		int array[]= new int[n];
		System.out.println("Enter elements:");
		for (int i=0; i<n; i++){
			System.out.print("array["+i+"] = ");
			array[i] = sc.nextInt();
		}
		for (int imin = 0; imin<n-1; imin++) {
			int min = imin;
			for (int k = imin+1; k<n;k++){
		    	if (array[k]<array[min]) {
					min = k;
				}
			}
		    int t = array[imin];
		    array[imin]=array[min];
		    array[min]=t;   
		}
		System.out.println("The new order after sorting:");
		for (int i=0; i<n; i++){
			System.out.println("array["+i+"] = "+array[i]);
		}	
	}
}	
