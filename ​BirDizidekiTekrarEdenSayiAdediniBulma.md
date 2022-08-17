```
package com.company;

public class Main {

    public static void main(String[] args) {


        int[] dizi = new int[]{10, 20, 10, 10, 20, 5, 20};

        int OnSayiAdedi = 0, YirmiSayiAdedi = 0, BesSayiAdedi = 0;
        for (int i = 0; i < dizi.length; i++) {
            if (dizi[i] == 10) {
                OnSayiAdedi++;
            } else if (dizi[i] == 20) {
                YirmiSayiAdedi++;
            } else if (dizi[i] == 5) {
                YirmiSayiAdedi++;
            }

        }
        System.out.println("10 sayisindan = " + OnSayiAdedi + " tane var ");
        System.out.println("20 sayisindan = " + YirmiSayiAdedi + " tane var ");
        System.out.println("5 sayisindan = " + BesSayiAdedi + " tane var ");

    }
}

```