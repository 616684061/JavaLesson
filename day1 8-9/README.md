?

## 1.コーディング

`//Java アプリケーションの基本構造<br/>
class HelloWorld{<br/>
     public static void main(String[] args) {<br/>
        System.out.println("Hello World!");<br/>
     }<br/>
 }<br/>`


### 1.class宣言
   ソースファイル内には、一つ以上のclass(クラス)宣言が必要になります。<br>
   **1.一つのソースファイルに複数のクラスを定義することは可能ですが、public class指定のクラスは一つソースファイルにつき、
   一つしか記述できません**<br/>
   **2.クラス名は任意でつけることができますが、public classを宣言する場合は、ソースファイル名とクラス名は同じではなくてはいけません**<br>

#### OKの例
   `//Test.javaで保存<br/>
   class Foo{}<br/>
   class Bar{}<br/>
   `

   `//Foo.javaで保存<br/>
   public class Foo{}<br/>
   class Bar{}<br/>
   `

#### NGの例
   `//Foo.javaで保存<br/>
   public class Foo{}<br/>
   public class Bar{}<br/>
   `

   `//Bar.javaで保存<br/>
   public class Foo{}<br/>
   class Bar{}<br/>
   `
#### main()メソッド
　　main()メソッドはJavaアプリケーションの特別のメソッドです。記述は必ず以下のとなります。<br/>
   `public static void main(String[] args){...}` <br/>
   `public static void main(String args[]){...}` <br/>

   *main()メソッドはプログラムの実行開始位置を表し、数千行のプログラムであっても、必ず<br/>
   main()メソッドから実行されます。*<br/>

#### System.out.println("......");
   プログラムを実行した際に出力画面(ここではコマンドプロンプト)に何かしら実行結果を表示したい場合<br/>
   記述するコードです。println()のカッコの中に記述した情報が画面へ表示されます。<br/>

   println()は出力(print)、行(ln)という意味があります。つまりprintlnを使用すると、情報の出力後に<br/>
   改行コードが追加されます。また、以下のメッソドも使いますが、ただ、情報を出力後に改行は行われません。<br/>
   `System.out.print("....."")`<br/>

   以下のコーディングを入力して実行してみてください。<br/>
   `System.out.print("Hello World");`<br/>
   `System.out.print("Thanks");`




## プログラムの具体の動作は、メソッド内に文あるいはブロックで記述します。

### 文
   文は、プログラムの最小構成単位で、一つの処理を記述したものです。文の最後には、<br/>
   「**;**」(`セミコロン`)を記述します。例:
   <br/>
   `System.out.println("Hello World");`

### ブロック
   ブロックは、文の並びを{}(ナミカッコ)で囲んで一つまとめたものです。単一の文が<br/>
   書ける場所ならどこでもブロックがかけます。メソッド、クラス本体も{}で囲んでブロック<br/>
   が使用されます。例:<br/>
   `{`<br/>
        `System.out.print("Hello World");`<br/>
        `System.out.print("Thanks");`<br/>
   `}`<br/>



## 2.コンパイル
   ソースファイルを保存した後、コンパイルします。コンパイルことで、ソースファイルからクラスファイル<br/>
   を生成されます。<br/>
   **コンパイルにはjavacコマンドを使用します。構文は以下となります。**<br/>
   `javac ソースファイル.java`  **←拡張子(.java)をつける**
   <br/>
   例:<br/>
   `javac HelloWorld.java`<br/>

   コンパイルを実行後、HelloWorld.classというクラスファイルを生成できます。

## 3.実行
   コンパイルに成功したら、クラスファイルを実行します。実行には、コマンドプロンプトでjavaコマンドを<br/>
   使用します。<br/>
   **javaコマンドの構文は以下となります。**<br/>
   `java クラスファイル名`　   **←拡張子(.class)をつけない**<br/>
    例:<br/>
    `java HelloWorld`<br/>










