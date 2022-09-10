
programa 1

_________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica1 {

    static String nombre;

    public static void main(String[] args) {

        nombre = JOptionPane.showInputDialog(null, "Programa #1. \n Impresión de tu nombre \n"+"Ingresa tu nombre: ");

        JOptionPane.showMessageDialog(null, "Mi nombre es; "+ nombre);
    
}

}

______________________________________________________________________________________________________________________________________________

programa 2

_______________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica2 {

    static int numero_1;
    static int numero_2;

 public static void main(String[] args) {

    numero_1 = Integer.parseInt(JOptionPane.showInputDialog(null, " programa #2. \n  Imprime los dos numeros entregados \n"+"Ingrese un primer numero"));
    numero_2 = Integer.parseInt(JOptionPane.showInputDialog(null, "Ingrese un segundo numero"));

    JOptionPane.showMessageDialog(null, "Los numeros enteros ingresados son: " + numero_1 +" y "+ numero_2);
    
}

}

____________________________________________________________________________________________________________________________________________________________

programa 3
___________________________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica3 {

    static double numero, doble , triple;

    public static void main(String[] args) {
        
        numero = Double.parseDouble(JOptionPane.showInputDialog(null, "programa #3. \n Ingresar un numero real lo duplique y triplique \n"+"Ingresa un numero real: "));

        doble = numero*2;
        triple = numero*3;

        JOptionPane.showMessageDialog(null, "El doble del numoero: "+doble+"\n"+
        "El triple del numero: "+triple);

    }

}

______________________________________________________________________________________________________________________________________________________________________

programa 4

_________________________________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica4 {

    static float grados_centigrados, grados_fahrenheit;  

    public static void main(String[] args) {

        grados_centigrados = Float.parseFloat(JOptionPane.showInputDialog(null, " programa #4. \n  Conversor de °c  a °F \n"+"Ingrese la temperatura en grados centigrados; "));

        grados_fahrenheit = 32 + (9*grados_centigrados/5);

        JOptionPane.showMessageDialog(null, "La conversion en grados centigrados es de: "+ grados_fahrenheit);

    }
    
}

_____________________________________________________________________________________________________________________________________________________________________

programa 5
______________________________________________________________________________________________________________________________________________________________________


import javax.swing.JOptionPane;

public class practica5 {

    static double radio,longitud,area;

    public static void main(String[] args) {
        
        radio = Double.parseDouble(JOptionPane.showInputDialog(null, "Programa  #5. \n Saca longitud y area de un circulo \n"+"Ingresa el radio del circulo"));

        longitud = 2*Math.PI*radio;
        area = Math.PI*Math.pow(radio, 2);

        JOptionPane.showMessageDialog(null,"La longitud del circulo es:  "+longitud+"\n"+
        "El area del circulo es: "+area);
    }

}
_________________________________________________________________________________________________________________________________________________________________
programa 6
______________________________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica6 {

    static double m_s, km_h,s; 
    
    public static void main(String[] args) {
        
        km_h = Double.parseDouble(JOptionPane.showInputDialog(null, "programa #6. \n Conversor de unidades km/h a m/s \n"+
        "Ingrese su trayectoria en km/h"));

        m_s = (km_h*1000)/3600;
        
        JOptionPane.showMessageDialog(null, "La conversion de km/h a m/s es de: "+m_s);
        
    }


}

____________________________________________________________________________________________________________________________________________________________________
programa 7 
__________________________________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica7 {

    static double cateto1,cateto2,hipotenusa;

    public static void main(String[] args) {

        cateto1 = Double.parseDouble(JOptionPane.showInputDialog(null,"Programa #7. \n  Saca la hipotenusa de un triangulo: \n" 
        +"Ingrese el primer cateto del triangulo"));
        cateto2 = Double.parseDouble(JOptionPane.showInputDialog(null,"Ingrese el segundo cateto del triangulo"));

        hipotenusa = Math.sqrt(Math.pow(cateto1, 2)+ Math.pow(cateto2, 2));

        JOptionPane.showMessageDialog(null, "La hipotenusa es igual a: "+ hipotenusa);
        
    }
    
}
_________________________________________________________________________________________________________________________________________________________________________
programa 8
_______________________________________________________________________________________________________________________________________________________________________

import javax.swing.JOptionPane;

public class practica8 {

    static double radio,volumen;

    public static void main(String[] args) {
        
        radio = Double.parseDouble(JOptionPane.showInputDialog(null,"Programa #8. \n  Calcula el volumen de una esfera \n"+ "ingresa el radio: "));
        volumen= (4*Math.PI)/3*Math.pow(radio, 3);

        JOptionPane.showMessageDialog(null, "El volumen de una esfera es de : "+volumen);
    }
    
}
______________________________________________________________________________________________________________________________________________________________________________
