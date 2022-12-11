
Ad-soyad:şehed totah
öğrenci no:225541603
Şube:A Gece

Video Linki: https://www.youtube.com/watch?v=XpP7wyNALlY


package hello;

public class Hello {

	public static void main(String[] args) {
	   System.out.println("Merhaba Dünya");
}
}
--------------------------------------------------------
package hello;

public class Hello {

	public static void main(String[] args) {
	  int yas=16;
	  if(yas>=18) {
		  System.out.println("Ehliyet alabilirsin");
	  }
	  else {
		  System.out.println("Ehliyet alamaz");
	  }
}
}
--------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	 Scanner oku =new Scanner(System.in);
	 System.out.println("Bir sayı giriniz");
	 int sayi=oku.nextInt();
	 if(sayi%2==1) {
		 System.out.println("Tek");
	 }
	 else {
		 System.out.println("Çift");
	 }
}
}	
---------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	  for(int i=1;i<=9;i++) {
		  System.out.println(i);
	  }
}
}	

---------------------------------------------------------
package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	  Scanner oku=new Scanner(System.in);
	  System.out.println("Bir sayı giriniz");
	  int sayi=oku.nextInt();
	  int faktoriyel=1;
	  for(int i=1;i<=sayi;i++) {
		  faktoriyel=faktoriyel*i;
		  System.out.println("Sonuç"+faktoriyel);
	  }
}
}	
----------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	  int x=6;
	  int y=5;
	  System.out.println(x+y);
	  System.out.println(x-y);
}
}	
------------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	  int x=11;
	  int y=9;
	  if(x>y) {
		  System.out.println(x);
	  }
	  else {
		  System.out.println(y);
	  }
}
}	
--------------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	 String sayi1 ="Ahmet";
	 System.out.println(sayi1);
}
}	
---------------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	 float sayi3 =5.5f;
	 System.out.println(sayi3);
}
}	
-----------------------------------------------------------------

package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	  int [] sayilar= {10,20,30,40,50};
	  for(int i=0;i<5;i++) {
	  System.out.println(sayilar[i]);
	  }
}
}	



