


`//Java ���ץꥱ�`�����λ�������
class HelloWorld{
     public static void main(String[] args) {
        System.out.println("Hello World!");
     }
 }`


 ### 1.class����
   ���`���ե������ڤˤϡ�һ�����Ϥ�class(���饹)���Ԥ���Ҫ�ˤʤ�ޤ���<br>
   **һ�ĤΥ��`���ե�������}���Υ��饹���x���뤳�ȤϿ��ܤǤ�����public classָ���Υ��饹��һ�ĥ��`���ե�����ˤĤ���
   һ�Ĥ���ӛ���Ǥ��ޤ���**<br/>
   **���饹��������ǤĤ��뤳�Ȥ��Ǥ��ޤ�����public class�����Ԥ�����Ϥϡ����`���ե��������ȥ��饹����ͬ���ǤϤʤ��ƤϤ����ޤ���**<br>

   #### OK����
   `//Test.java�Ǳ���
   class Foo{}
   class Bar{}
   `

   `//Foo.java�Ǳ���
   public class Foo{}
   class Bar{}
   `

   #### NG����
   `//Foo.java�Ǳ���
   public class Foo{}
   public class Bar{}
   `

   `//Bar.java�Ǳ���
   public class Foo{}
   class Bar{}
   `

