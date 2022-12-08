# not-ortalamas-hesaplama-


import java.util.Scanner;

public class GradeAverage {

	public static void main(String[] args) {
 
  int mat, fizik, kimya, turkce, tarih, muzik
  
  
  Scanner inp = new Scanner(System.in);
  
  
  Systemoutprint("Matematik Notunuz: ");
		mat=inp.nextInt()
    Sytem.out.print(mat);
     Systemoutprint("Fizik Notunuz: ");
		fizik=inp.nextInt()
     Systemoutprint("Kimya Notunuz: ");
		kimyat=inp.nextInt()
     Systemoutprint("Türkçe Notunuz: ");
		turkce=inp.nextInt()
     Systemoutprint("Tarih Notunuz: ");
		tarih=inp.nextInt()
     Systemoutprint("Müzik Notunuz: ");
		muzik=inp.nextInt()
    int toplam = (mat + fizik + kimya + turkce + tarih + muzik)
    double sonuc = toplam/6;
    System.out.println("Ortalamanız:" +sonuc);
    
    if (sonuc >= 60) {
    System.out.println("Geçtiniz.")
    }
    else (sonuc < 60) {
    System.out.println("Kaldınız.")
    }
    
	
		
		
