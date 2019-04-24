//---------------------------------------------------------------------------

#include <vcl.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;

     char p1,p2,p3,p4,p5,p6,p7,p8,p9; // state of place  (p1='n' ; nic lub 'x' lub 'o' )
     char move;

     void check()
     {
       if ((((p1==p2)&&(p2==p3)) &&  p1!='n') ||
           (((p4==p5)&&(p5==p6)) &&  p4!='n') ||
           (((p7==p8)&&(p8==p9)) &&  p7!='n') ||

           (((p1==p4)&&(p4==p7)) &&  p1!='n') ||
           (((p2==p5)&&(p5==p8)) &&  p2!='n') ||
           (((p3==p6)&&(p6==p9)) &&  p3!='n') ||

           (((p1==p5)&&(p5==p9)) &&  p1!='n') ||
           (((p3==p5)&&(p5==p7)) &&  p3!='n') )

           {
               char *w;
               if (move=='x')
               {
                   w="Wygrywa kó³ko!!!";
               }
               else
               {
                   w="Wygrywa krzy¿yk!!!";
               }

               Application -> MessageBox(w, "BRAWO", MB_OK);
           }
     }

//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------


void __fastcall TForm1::FormCreate(TObject *Sender)
{
    pole1 -> Picture -> LoadFromFile("images/empty.bmp");
    pole2 -> Picture -> LoadFromFile("images/empty.bmp");
    pole3 -> Picture -> LoadFromFile("images/empty.bmp");
    pole4 -> Picture -> LoadFromFile("images/empty.bmp");
    pole5 -> Picture -> LoadFromFile("images/empty.bmp");
    pole6 -> Picture -> LoadFromFile("images/empty.bmp");
    pole7 -> Picture -> LoadFromFile("images/empty.bmp");
    pole8 -> Picture -> LoadFromFile("images/empty.bmp");
    pole9 -> Picture -> LoadFromFile("images/empty.bmp");

    polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");

    p1='n'; p2='n'; p3='n';
    p4='n'; p5='n'; p6='n';
    p7='n'; p8='n'; p9='n';

    move='o';

    pole1 -> Enabled = true;
    pole2 -> Enabled = true;
    pole3 -> Enabled = true;
    pole4 -> Enabled = true;
    pole5 -> Enabled = true;
    pole6 -> Enabled = true;
    pole7 -> Enabled = true;
    pole8 -> Enabled = true;
    pole9 -> Enabled = true;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole1Click(TObject *Sender)
{
    if (p1=='n')
        {
             if (move=='o')
             {
                p1='o';
                pole1 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p1='x';
                pole1 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole1 -> Enabled = false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole2Click(TObject *Sender)
{
     if (p2=='n')
        {
             if (move=='o')
             {
                p2='o';
                pole2 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p2='x';
                pole2 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole2 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole3Click(TObject *Sender)
{
     if (p3=='n')
        {
             if (move=='o')
             {
                p3='o';
                pole3 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p3='x';
                pole3 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole3 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole4Click(TObject *Sender)
{
    if (p4=='n')
        {
             if (move=='o')
             {
                p4='o';
                pole4 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p4='x';
                pole4 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole4 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole5Click(TObject *Sender)
{
    if (p5=='n')
        {
             if (move=='o')
             {
                p5='o';
                pole5 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p5='x';
                pole5 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole5 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole6Click(TObject *Sender)
{
    if (p6=='n')
        {
             if (move=='o')
             {
                p6='o';
                pole6 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p6='x';
                pole6 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole6 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole7Click(TObject *Sender)
{
    if (p7=='n')
        {
             if (move=='o')
             {
                p7='o';
                pole7 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p7='x';
                pole7 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole7 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole8Click(TObject *Sender)
{
   if (p8=='n')
        {
             if (move=='o')
             {
                p8='o';
                pole8 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p8='x';
                pole8 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole8 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::pole9Click(TObject *Sender)
{
   if (p9=='n')
        {
             if (move=='o')
             {
                p9='o';
                pole9 -> Picture -> LoadFromFile("images/O.bmp");
                move='x';
                polesmall -> Picture -> LoadFromFile("images/Xsmall.bmp");
             }

             else
             {
                p9='x';
                pole9 -> Picture -> LoadFromFile("images/X.bmp");
                move='o';
                polesmall -> Picture -> LoadFromFile("images/Osmall.bmp");
             }
             pole9 -> Enabled=false;
             check();
        }
}
//---------------------------------------------------------------------------
