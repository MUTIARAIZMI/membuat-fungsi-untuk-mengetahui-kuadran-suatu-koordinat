# Membuat fungsi untuk mengetahui kuadran suatu koordinatCoding program lengkap

Coding program lengkap

    #include <iostream>
    #include <stdio.h>
    #include <conio.h>

    using namespace std;
    int main ()
    {
    int x,y;

    cout<<"MENGETAHUI KUADRAN DARI INPUT KOORDINAT X DAN Y \n"<<endl;
    cout<<"Masukan nilai x =";cin>>x;
    cout<<"Masukan nilai y =";cin>>y;

    if (x>0&&y>0)
        printf("KUADRAN 1");
    if (x>0&&y<0)
        printf("KUADRAN 2");
    if (x<0&&y<0)
        printf("KUADRAN 3");
    if (x<0&&y>0)
        printf("KUADRAN 4");
    if (x==0&&y==0)
        printf("TITIK PUSAT");

    getch ();
    }

Hasil program
![img](https://raw.githubusercontent.com/MUTIARAIZMI/membuat-fungsi-untuk-mengetahui-kuadran-suatu-koordinat/master/mengetahui%20kuadran%20suatu%20koordinat.jpg)
