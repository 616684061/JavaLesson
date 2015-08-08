


`//Java アプリケーションの基本構造
class HelloWorld{
     public static void main(String[] args) {
        System.out.println("Hello World!");
     }
 }`


 ### 1.class宣言
   ソースファイル内には、一つ以上のclass(クラス)宣言が必要になります。<br>
   **一つのソースファイルに複数のクラスを定義することは可能ですが、public class指定のクラスは一つソースファイルにつき、
   一つしか記述できません**<br/>
   **クラス名は任意でつけることができますが、public classを宣言する場合は、ソースファイル名とクラス名は同じではなくてはいけません**<br>

   #### OKの例
   `//Test.javaで保存
   class Foo{}
   class Bar{}
   `

   `//Foo.javaで保存
   public class Foo{}
   class Bar{}
   `

   #### NGの例
   `//Foo.javaで保存
   public class Foo{}
   public class Bar{}
   `

   `//Bar.javaで保存
   public class Foo{}
   class Bar{}
   `

