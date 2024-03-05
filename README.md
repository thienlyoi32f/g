# g#include<stdio.h>
#include<conio.h>
void
main ()
{
  int a, b;
  char dv, chuc, tram;
  clrscr ();
  printf ("Nhap so bi nhan co 3 chu so a=");
  scanf ("%d", &a);
  printf ("Nhap so nhan co 3 chu so b=");
  scanf ("%d", &b);
  int t, t100, t20, t5;
  clrscr ();
  printf ("Nhap so tien t=");
  scanf ("%d", &t);
  t100 = t / 100;
  t -= 100 * t100;
  t20 = t / 20;
  t -= 20 * t20;
  t5 = t / 5;
  t -= 5 * t5;
  printf ("So to cac loai menh gia la :\n");
  printf ("Loai 100 : %d to\n", t100);
  printf ("Loai 20 : %d to\n", t20);
  printf ("Loai 5 : %d to\n", t5);
  printf ("Loai 1 : %d to\n", t);
  printf ("Tong so to cac loai la : %d\n", t + t5
  dv = b % 10;
  chuc = b % 100 / 10;
  tram = b / 100;
  printf ("\nMo phong phep nhan tay\n\n");
  printf ("%20d\n", a);
  printf ("%15c%5d\n", 'x', b);
  printf ("%20s\n", "-------");
  printf ("%20d\n", a * dv);
  printf ("%19d\n", a * chuc);
  printf ("%18d\n", a * tram);
  printf ("%20s\n", "-------");
  printf ("%20ld\n", long (a) * b);
  getch ();

  int t, t100, t20, t5;
  clrscr ();
  printf ("Nhap so tien t=");
  scanf ("%d", &t);
  t100 = t / 100;
  t -= 100 * t100;
  t20 = t / 20;
  t -= 20 * t20;
  t5 = t / 5;
  t -= 5 * t5;
  printf ("So to cac loai menh gia la :\n");
  printf ("Loai 100 : %d to\n", t100);
  printf ("Loai 20 : %d to\n", t20);
  printf ("Loai 5 : %d to\n", t5);
  printf ("Loai 1 : %d to\n", t);
  printf ("Tong so to cac loai la : %d\n", t + t5
}
