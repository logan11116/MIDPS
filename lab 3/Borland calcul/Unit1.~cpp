//---------------------------------------------------------------------------

#include <vcl.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;

double y,x;
 bool pre;
 char imultirea,impartirea,adunarea,scaderea;
 char znak;
//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{

//---------------------------------------------------------------------------
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button18Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+0;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button5Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+1;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button6Click(TObject *Sender)
{
      Edit1->Text=Edit1->Text+2;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button7Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+3;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button8Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+4;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button9Click(TObject *Sender)
{
     Edit1->Text=Edit1->Text+5;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button10Click(TObject *Sender)
{
  Edit1->Text=Edit1->Text+6;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button11Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+7;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button12Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+8;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button13Click(TObject *Sender)
{
   Edit1->Text=Edit1->Text+9;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button16Click(TObject *Sender)
{
    if(imultirea==true)
    {
     y=Edit1->Text.ToDouble();
     x=x*y;
     Edit1->Text="";
         }
     else
     x=Edit1->Text.ToDouble();
     imultirea=true;
     Edit1->Clear();
     pre=false;
     impartirea=false;
     scaderea=false;
     adunarea=false;





}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button19Click(TObject *Sender)
{
   if(impartirea==true)
    {
     y=Edit1->Text.ToDouble();
     x=x*y;
     Edit1->Text="";
         }
     else
     x=Edit1->Text.ToDouble();
     impartirea=true;
     Edit1->Clear();
     pre=false;
     adunarea=false;
     scaderea=false;
     imultirea=false;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button14Click(TObject *Sender)
{
 if(adunarea==true)
    {
     y=Edit1->Text.ToDouble();
     x=x+y;
     Edit1->Text="";
         }
     else
     x=Edit1->Text.ToDouble();
     adunarea=true;
     Edit1->Clear();
     pre=false;
     scaderea=false;
     imultirea=false;
     impartirea=false;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button15Click(TObject *Sender)
{
 if(scaderea==true)
    {
     y=Edit1->Text.ToDouble();
     x=x-y;
     Edit1->Text="";
         }
     else
     x=Edit1->Text.ToDouble();
     scaderea=true;
     Edit1->Clear();
     pre=false;
     adunarea=false;
     imultirea=false;
     impartirea=false;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button4Click(TObject *Sender)
{
x=0;
y=0;
Edit1->Text="";
adunarea=false;
scaderea=false;
impartirea=false;
imultirea=false;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button17Click(TObject *Sender)
{

if(adunarea==true)
{
y=Edit1->Text.ToDouble();
x=x+y;
Edit1->Text=x;
x=0;
y=0;
pre=false;
}

if(scaderea==true)
{
y=Edit1->Text.ToDouble();
x=x-y;
Edit1->Text=x;
x=0;
y=0;
pre=false;
}

if(imultirea==true)
{
y=Edit1->Text.ToDouble();
x=x*y;
Edit1->Text=x;
x=0;
y=0;
pre=false;
}

if(impartirea==true)
{
y=Edit1->Text.ToDouble();
x=x/y;
Edit1->Text=x;
x=0;
y=0;
pre=false;
}

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button1Click(TObject *Sender)
{
    if(!pre)
    {
      AnsiString virg=Edit1->Text;
      virg+=",";
      Edit1->Text=virg;
      pre=true;
    }
}
//---------------------------------------------------------------------------
