# Static-Keyword
class Static{
	static int a = 10;
	static int b = 20;

	
	static void name(){
		int c = 30;
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
	}
}
class Main1{
	public static void main(String [] args){
		Static.name();
	}
}
