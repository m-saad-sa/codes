# codes
practice codes
public class Main{
	public static int max(int num1 , int num2) {
		int result ;
		if(num1 > num2){
			result = num1 ;
			}
		else{
			result = num2 ;
		}
		return result ;
}

public static void main(String[] args){
	int a = 12 ;
	int b = 14 ;
	int z = max( a , b) ;
	System.out.println("maximum number = " + z);

} 
}
