# DiscountComputation

package hii;
import java.io.*;
import java.util.Scanner;

public class DiscountComputation {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		float p, r,t,mi,si;
		Scanner sc=new Scanner(System.in);
		System.out.println("enter principal amount");
		p=sc.nextFloat();
		System.out.println("enter interest");
		r=sc.nextFloat();
		System.out.println("enter time");
		t=sc.nextFloat();
		mi=p/t;
		/*Amount to Invested=principalAmount(p)/Time(t)*/
		si=(p*t*r)/100;
		/*simple Interest(si)=principalAmount(p)*Time(t)*rate Of Interest(r)/100*/
	   System.out.println(mi);
	   System.out.println(si);
		

	}

}
