import javax.swing.*;
public class whiled {
public static void main (String[]args){

int count, a=1,b=1, s1=0, s2=0;
count=Integer.parseInt(JOptionPane.showInputDialog("Введиет границу"));
String text="Сумма натуральных чисел от одного до "+count; // нужны ли скобки?
String str1="Оператор while";
String str2="Оператор do while";

while (a<=count){
s1+=a;
a++;
}
JOptionPane.showMessageDialog(null, text+str1);
}
}
