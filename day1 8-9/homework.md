#問題1-1
Javaのリテラルとして正しくないものは次のどれですか。2つを選んでください。<br/>
*	A.10<br/>
*	B.3.12345L<br/>
*	C.0777
*	D.0xDeed
*	E.'ABCDE'

#問題1-2
識別子として使用できないものは次のどれですか。三つ選択してください。<br/>
*	A.java
*	B.goto
*	C.$100
*	D._$
*	E.NULL
*	F.num#
*	G.~val

#問題1-3
次のコードがあります。<br/>

	public class Test{
		public static void main(String args){
			float f=3.14f;
			String s="true";
			System.out.println(f+" "+s);
	}

*	A.3行目でコンパイルエラー
*	B.4行目でコンパイルエラー
*	C.実行エラー
*	D.3.14f true
*	E.3.14 true

エラーの場合は、このコードを正しく動くように修正してください。<br/>

#問題1-4
次のコードがあります。
	
	public class Test{
		public static void main(String args[]){
			String[] array=new String[3];
			array[1]="10";
			array[2]="20";
			array[3]="30";
			
			System.out.println(array[1]+array[2]+array[3]);
		}
	}
	
*	A.コンパイルエラー
*	B.実行時エラー
*	C.102030と出力される
*	D.60と出力される
*	E.何も出力されない

#問題1-5
次の配列式で正しくないものはどれですか。二つ選択してください。<br/>

*	A. int[] a=new int[]{1,2,3};
*	B. int[3] a=new int[];
*	C. int[] a={1.0};
*	D. int[] a={0};
*	E. int a[]=new int[1];

#問題1-6
次のコードがあります。
	
	 class Test{
		public static void main(String args[]){
			String[] array=new String[3];
			array[0]=10;
			array[1]=20;
			array[2]=30;
			
			System.out.println(array[0]+array[1]+array[2]);
		}
	}
	
*	A.コンパイルエラー
*	B.実行時エラー
*	C.102030と出力される
*	D.60と出力される
*	E.何も出力されない

#問題1-7
次のコードがあります。
	
	 class Test{
		public static void main(String args[]){
			int x=7;
			int y=6*x++;
			System.out.println("y="+y);
			int a=7;
			int b=6*++a;
			System.out.println("b="+b);

		}
	}

*	A. y=42
*	   b=48
*	B. y=48
*	   b=48
*	C. y=48
*      b=42
*	D. y=42
*	   b=42

#問題1-8
次のコードがあります。
	
	 class Test{
		public static void main(String args[]){
			byte x=3;
			byte y=2*x++;
			byte z=x*y;
			System.out.println("z="+z);

		}
	}
	
*	A.z:24
*	B.z:32
*	C.コンパイルエラー
*	D.実行エラー

#問題1-9
以下の問題について、コーディングを作成してください。<br/>

整数aとbを宣言し、任意の値を設定してください。<br/>
aとbを比較し大きい方の値を出力して下さい。aとbが同じ場合は「eq」と出力して下さい。<br/>

#問題1-10
以下の問題について、コーディングを作成してください。<br/>

[forを使って](day2%208-16/5-1.md)、整数配列の要素を加算する処理を作成してください。<br/>
例: int[] a={1,2,3,4,5};の場合は<br/>
出力：15<br/>





