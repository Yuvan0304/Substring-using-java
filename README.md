# Substring-using-java

Program:

import java.util.*;
public class Main
{
  public static void main (String[]args)
  {
    Scanner sc=new Scanner(System.in);
	String s1 = new String();
	System.out.print("Eter your name :");
    s1 =sc.nextLine();
    System.out.println(s1.substring(2,5));
    System.out.println(s1.substring(2));
  }}
