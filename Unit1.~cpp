//---------------------------------------------------------------------------
#include <iostream>
#include <vcl.h>
#pragma hdrstop
#include <string>
#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;
std::string board[15][15];
      std::string kto=" o ";
         int turn=0;
//---------------------------------------------------------------------------

void algorythms(){
   std::string znak="   ";
   int win;
   char * w1;
   char * w2;
   char * w3;
   bool found=0;
   if(turn%2==0)
        znak=" o " ;

   else
        znak=" x " ;

        for(int i=0;i<15;i++)
        {
            for(int j=0;j<15;j++)
            {
                if(board[i][j]==znak )
                {
                    win++;
                    if(win == 5 && board[i][j+1]!=znak)
                        found = true;
                }
                else
                {
                    win=0;
                }
            }
        }
        for(int i=0;i<15;i++)
        {
            for(int j=0;j<15;j++)
            {
                if(board[j][i]==znak)
                {
                    win++;
                    if(win == 5&& board[j+1][i]!=znak)
                        found = true;
                }
                else
                {
                    win=0;
                }
            }
        }
        int l=5;
        for(int i=15-5;i>=0;i--)
            {
                for(int j=0;j<l;j++)
                {
                    if(board[j][i+j]==znak)
                    {
                        win++;
                        if(win == 5&& board[j+1][i+j+1]!=znak)
                            found = true;
                    }
                    else
                    {
                        win=0;
                    }
                }
                l++;
            }
            l=15;
            for(int i=0;i<=15-5;i++)
            {
                for(int j=0;j<l;j++)
                {
                    if(board[i+j][j]==znak)
                    {
                        win++;
                        if(win == 5 && board[i+j+1][j+1]!=znak )
                            found = true;
                    }
                    else
                    {
                        win=0;
                    }
                }
                l--;
            }
            l=15;
            for(int i=15-1;i>=4;i--)
            {
                for(int j=0;j<l;j++)
                {
                    if(board[j][i-j]==znak)
                    {
                        win++;
                        if(win == 5&& board[j+1][i-j-1]!=znak)
                            found = true;
                    }
                    else
                    {
                        win=0;
                    }
                }
                l--;
            }
            l=15;
            for(int i=0;i<=15-5;i++)
            {
                for(int j=0;j<l;j++)
                {
                    if(board[15-1-j][i+j]==znak)
                    {
                        win++;
                        if(win == 5&& board[15-1-j-1][i+j+1]!=znak)
                            found = true;
                    }
                    else
                    {
                        win=0;
                    }
                }
                l--;
            }
        turn++;
        char * w;

        if (found && znak==" o "){ w="Wygrywa zielony!";
             Application->MessageBox(w, "Koniec gry", MB_OK);}
        if (found && znak==" x ") {w="Wygrywa czerwony!";
        Application->MessageBox(w, "Koniec gry", MB_OK);}

}

_fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{


    for(int i=0;i<15;i++)
    {
        for(int j=0;j<15;j++)
        {
            board[i][j]="   " ;
        }
    }
        Image1->Picture->LoadFromFile("grafika/cross.bmp");
        Image2->Picture->LoadFromFile("grafika/cross.bmp");
        Image3->Picture->LoadFromFile("grafika/cross.bmp");
        Image4->Picture->LoadFromFile("grafika/cross.bmp");
        Image5->Picture->LoadFromFile("grafika/cross.bmp");
        Image6->Picture->LoadFromFile("grafika/cross.bmp");
        Image7->Picture->LoadFromFile("grafika/cross.bmp");
        Image8->Picture->LoadFromFile("grafika/cross.bmp");
        Image9->Picture->LoadFromFile("grafika/cross.bmp");
        Image10->Picture->LoadFromFile("grafika/cross.bmp");
        Image11->Picture->LoadFromFile("grafika/cross.bmp");
        Image12->Picture->LoadFromFile("grafika/cross.bmp");
        Image13->Picture->LoadFromFile("grafika/cross.bmp");
        Image14->Picture->LoadFromFile("grafika/cross.bmp");
        Image15->Picture->LoadFromFile("grafika/cross.bmp");
        Image16->Picture->LoadFromFile("grafika/cross.bmp");
        Image17->Picture->LoadFromFile("grafika/cross.bmp");
        Image18->Picture->LoadFromFile("grafika/cross.bmp");
        Image19->Picture->LoadFromFile("grafika/cross.bmp");
        Image20->Picture->LoadFromFile("grafika/cross.bmp");
        Image21->Picture->LoadFromFile("grafika/cross.bmp");
        Image22->Picture->LoadFromFile("grafika/cross.bmp");
        Image23->Picture->LoadFromFile("grafika/cross.bmp");
        Image24->Picture->LoadFromFile("grafika/cross.bmp");
        Image25->Picture->LoadFromFile("grafika/cross.bmp");
        Image26->Picture->LoadFromFile("grafika/cross.bmp");
        Image27->Picture->LoadFromFile("grafika/cross.bmp");
        Image28->Picture->LoadFromFile("grafika/cross.bmp");
        Image29->Picture->LoadFromFile("grafika/cross.bmp");
        Image30->Picture->LoadFromFile("grafika/cross.bmp");
        Image31->Picture->LoadFromFile("grafika/cross.bmp");
        Image32->Picture->LoadFromFile("grafika/cross.bmp");
        Image33->Picture->LoadFromFile("grafika/cross.bmp");
        Image34->Picture->LoadFromFile("grafika/cross.bmp");
        Image35->Picture->LoadFromFile("grafika/cross.bmp");
        Image36->Picture->LoadFromFile("grafika/cross.bmp");
        Image37->Picture->LoadFromFile("grafika/cross.bmp");
        Image38->Picture->LoadFromFile("grafika/cross.bmp");
        Image39->Picture->LoadFromFile("grafika/cross.bmp");
        Image40->Picture->LoadFromFile("grafika/cross.bmp");
        Image41->Picture->LoadFromFile("grafika/cross.bmp");
        Image42->Picture->LoadFromFile("grafika/cross.bmp");
        Image43->Picture->LoadFromFile("grafika/cross.bmp");
        Image44->Picture->LoadFromFile("grafika/cross.bmp");
        Image45->Picture->LoadFromFile("grafika/cross.bmp");
        Image46->Picture->LoadFromFile("grafika/cross.bmp");
        Image47->Picture->LoadFromFile("grafika/cross.bmp");
        Image48->Picture->LoadFromFile("grafika/cross.bmp");
        Image49->Picture->LoadFromFile("grafika/cross.bmp");
        Image50->Picture->LoadFromFile("grafika/cross.bmp");
        Image51->Picture->LoadFromFile("grafika/cross.bmp");
        Image52->Picture->LoadFromFile("grafika/cross.bmp");
        Image53->Picture->LoadFromFile("grafika/cross.bmp");
        Image54->Picture->LoadFromFile("grafika/cross.bmp");
        Image55->Picture->LoadFromFile("grafika/cross.bmp");
        Image56->Picture->LoadFromFile("grafika/cross.bmp");
        Image57->Picture->LoadFromFile("grafika/cross.bmp");
        Image58->Picture->LoadFromFile("grafika/cross.bmp");
        Image59->Picture->LoadFromFile("grafika/cross.bmp");
        Image60->Picture->LoadFromFile("grafika/cross.bmp");
        Image61->Picture->LoadFromFile("grafika/cross.bmp");
        Image62->Picture->LoadFromFile("grafika/cross.bmp");
        Image63->Picture->LoadFromFile("grafika/cross.bmp");
        Image64->Picture->LoadFromFile("grafika/cross.bmp");
        Image65->Picture->LoadFromFile("grafika/cross.bmp");
        Image66->Picture->LoadFromFile("grafika/cross.bmp");
        Image67->Picture->LoadFromFile("grafika/cross.bmp");
        Image68->Picture->LoadFromFile("grafika/cross.bmp");
        Image69->Picture->LoadFromFile("grafika/cross.bmp");
        Image70->Picture->LoadFromFile("grafika/cross.bmp");
        Image71->Picture->LoadFromFile("grafika/cross.bmp");
        Image72->Picture->LoadFromFile("grafika/cross.bmp");
        Image73->Picture->LoadFromFile("grafika/cross.bmp");
        Image74->Picture->LoadFromFile("grafika/cross.bmp");
        Image75->Picture->LoadFromFile("grafika/cross.bmp");
        Image76->Picture->LoadFromFile("grafika/cross.bmp");
        Image77->Picture->LoadFromFile("grafika/cross.bmp");
        Image78->Picture->LoadFromFile("grafika/cross.bmp");
        Image79->Picture->LoadFromFile("grafika/cross.bmp");
        Image80->Picture->LoadFromFile("grafika/cross.bmp");
        Image81->Picture->LoadFromFile("grafika/cross.bmp");
        Image82->Picture->LoadFromFile("grafika/cross.bmp");
        Image83->Picture->LoadFromFile("grafika/cross.bmp");
        Image84->Picture->LoadFromFile("grafika/cross.bmp");
        Image85->Picture->LoadFromFile("grafika/cross.bmp");
        Image86->Picture->LoadFromFile("grafika/cross.bmp");
        Image87->Picture->LoadFromFile("grafika/cross.bmp");
        Image88->Picture->LoadFromFile("grafika/cross.bmp");
        Image89->Picture->LoadFromFile("grafika/cross.bmp");
        Image90->Picture->LoadFromFile("grafika/cross.bmp");
        Image91->Picture->LoadFromFile("grafika/cross.bmp");
        Image92->Picture->LoadFromFile("grafika/cross.bmp");
        Image93->Picture->LoadFromFile("grafika/cross.bmp");
        Image94->Picture->LoadFromFile("grafika/cross.bmp");
        Image95->Picture->LoadFromFile("grafika/cross.bmp");
        Image96->Picture->LoadFromFile("grafika/cross.bmp");
        Image97->Picture->LoadFromFile("grafika/cross.bmp");
        Image98->Picture->LoadFromFile("grafika/cross.bmp");
        Image99->Picture->LoadFromFile("grafika/cross.bmp");
        Image100->Picture->LoadFromFile("grafika/cross.bmp");
        
        Image101->Picture->LoadFromFile("grafika/cross.bmp");
        Image102->Picture->LoadFromFile("grafika/cross.bmp");
        Image103->Picture->LoadFromFile("grafika/cross.bmp");
        Image104->Picture->LoadFromFile("grafika/cross.bmp");
        Image105->Picture->LoadFromFile("grafika/cross.bmp");
        Image106->Picture->LoadFromFile("grafika/cross.bmp");
        Image107->Picture->LoadFromFile("grafika/cross.bmp");
        Image108->Picture->LoadFromFile("grafika/cross.bmp");
        Image109->Picture->LoadFromFile("grafika/cross.bmp");
        Image110->Picture->LoadFromFile("grafika/cross.bmp");
        Image111->Picture->LoadFromFile("grafika/cross.bmp");
        Image112->Picture->LoadFromFile("grafika/cross.bmp");
        Image113->Picture->LoadFromFile("grafika/cross.bmp");
        Image114->Picture->LoadFromFile("grafika/cross.bmp");
        Image115->Picture->LoadFromFile("grafika/cross.bmp");
        Image116->Picture->LoadFromFile("grafika/cross.bmp");
        Image117->Picture->LoadFromFile("grafika/cross.bmp");
        Image118->Picture->LoadFromFile("grafika/cross.bmp");
        Image119->Picture->LoadFromFile("grafika/cross.bmp");
        Image120->Picture->LoadFromFile("grafika/cross.bmp");
        Image121->Picture->LoadFromFile("grafika/cross.bmp");
        Image122->Picture->LoadFromFile("grafika/cross.bmp");
        Image123->Picture->LoadFromFile("grafika/cross.bmp");
        Image124->Picture->LoadFromFile("grafika/cross.bmp");
        Image125->Picture->LoadFromFile("grafika/cross.bmp");
        Image126->Picture->LoadFromFile("grafika/cross.bmp");
        Image127->Picture->LoadFromFile("grafika/cross.bmp");
        Image128->Picture->LoadFromFile("grafika/cross.bmp");
        Image129->Picture->LoadFromFile("grafika/cross.bmp");
        Image130->Picture->LoadFromFile("grafika/cross.bmp");
        Image131->Picture->LoadFromFile("grafika/cross.bmp");
        Image132->Picture->LoadFromFile("grafika/cross.bmp");
        Image133->Picture->LoadFromFile("grafika/cross.bmp");
        Image134->Picture->LoadFromFile("grafika/cross.bmp");
        Image135->Picture->LoadFromFile("grafika/cross.bmp");
        Image136->Picture->LoadFromFile("grafika/cross.bmp");
        Image137->Picture->LoadFromFile("grafika/cross.bmp");
        Image138->Picture->LoadFromFile("grafika/cross.bmp");
        Image139->Picture->LoadFromFile("grafika/cross.bmp");
        Image140->Picture->LoadFromFile("grafika/cross.bmp");
        Image141->Picture->LoadFromFile("grafika/cross.bmp");
        Image142->Picture->LoadFromFile("grafika/cross.bmp");
        Image143->Picture->LoadFromFile("grafika/cross.bmp");
        Image144->Picture->LoadFromFile("grafika/cross.bmp");
        Image145->Picture->LoadFromFile("grafika/cross.bmp");
        Image146->Picture->LoadFromFile("grafika/cross.bmp");
        Image147->Picture->LoadFromFile("grafika/cross.bmp");
        Image148->Picture->LoadFromFile("grafika/cross.bmp");
        Image149->Picture->LoadFromFile("grafika/cross.bmp");
        Image150->Picture->LoadFromFile("grafika/cross.bmp");
        Image151->Picture->LoadFromFile("grafika/cross.bmp");
        Image152->Picture->LoadFromFile("grafika/cross.bmp");
        Image153->Picture->LoadFromFile("grafika/cross.bmp");
        Image154->Picture->LoadFromFile("grafika/cross.bmp");
        Image155->Picture->LoadFromFile("grafika/cross.bmp");
        Image156->Picture->LoadFromFile("grafika/cross.bmp");
        Image157->Picture->LoadFromFile("grafika/cross.bmp");
        Image158->Picture->LoadFromFile("grafika/cross.bmp");
        Image159->Picture->LoadFromFile("grafika/cross.bmp");
        Image160->Picture->LoadFromFile("grafika/cross.bmp");
        Image161->Picture->LoadFromFile("grafika/cross.bmp");
        Image162->Picture->LoadFromFile("grafika/cross.bmp");
        Image163->Picture->LoadFromFile("grafika/cross.bmp");
        Image164->Picture->LoadFromFile("grafika/cross.bmp");
        Image165->Picture->LoadFromFile("grafika/cross.bmp");
        Image166->Picture->LoadFromFile("grafika/cross.bmp");
        Image167->Picture->LoadFromFile("grafika/cross.bmp");
        Image168->Picture->LoadFromFile("grafika/cross.bmp");
        Image169->Picture->LoadFromFile("grafika/cross.bmp");
        Image170->Picture->LoadFromFile("grafika/cross.bmp");
        Image171->Picture->LoadFromFile("grafika/cross.bmp");
        Image172->Picture->LoadFromFile("grafika/cross.bmp");
        Image173->Picture->LoadFromFile("grafika/cross.bmp");
        Image174->Picture->LoadFromFile("grafika/cross.bmp");
        Image175->Picture->LoadFromFile("grafika/cross.bmp");
        Image176->Picture->LoadFromFile("grafika/cross.bmp");
        Image177->Picture->LoadFromFile("grafika/cross.bmp");
        Image178->Picture->LoadFromFile("grafika/cross.bmp");
        Image179->Picture->LoadFromFile("grafika/cross.bmp");
        Image180->Picture->LoadFromFile("grafika/cross.bmp");
        Image181->Picture->LoadFromFile("grafika/cross.bmp");
        Image182->Picture->LoadFromFile("grafika/cross.bmp");
        Image183->Picture->LoadFromFile("grafika/cross.bmp");
        Image184->Picture->LoadFromFile("grafika/cross.bmp");
        Image185->Picture->LoadFromFile("grafika/cross.bmp");
        Image186->Picture->LoadFromFile("grafika/cross.bmp");
        Image187->Picture->LoadFromFile("grafika/cross.bmp");
        Image188->Picture->LoadFromFile("grafika/cross.bmp");
        Image189->Picture->LoadFromFile("grafika/cross.bmp");
        Image190->Picture->LoadFromFile("grafika/cross.bmp");
        Image191->Picture->LoadFromFile("grafika/cross.bmp");
        Image192->Picture->LoadFromFile("grafika/cross.bmp");
        Image193->Picture->LoadFromFile("grafika/cross.bmp");
        Image194->Picture->LoadFromFile("grafika/cross.bmp");
        Image195->Picture->LoadFromFile("grafika/cross.bmp");
        Image196->Picture->LoadFromFile("grafika/cross.bmp");
        Image197->Picture->LoadFromFile("grafika/cross.bmp");
        Image198->Picture->LoadFromFile("grafika/cross.bmp");
        Image199->Picture->LoadFromFile("grafika/cross.bmp");
        Image200->Picture->LoadFromFile("grafika/cross.bmp");
        Image201->Picture->LoadFromFile("grafika/cross.bmp");
        Image202->Picture->LoadFromFile("grafika/cross.bmp");
        Image203->Picture->LoadFromFile("grafika/cross.bmp");
        Image204->Picture->LoadFromFile("grafika/cross.bmp");
        Image205->Picture->LoadFromFile("grafika/cross.bmp");
        Image206->Picture->LoadFromFile("grafika/cross.bmp");
        Image207->Picture->LoadFromFile("grafika/cross.bmp");
        Image208->Picture->LoadFromFile("grafika/cross.bmp");
        Image209->Picture->LoadFromFile("grafika/cross.bmp");
        Image210->Picture->LoadFromFile("grafika/cross.bmp");
        Image211->Picture->LoadFromFile("grafika/cross.bmp");
        Image212->Picture->LoadFromFile("grafika/cross.bmp");
        Image213->Picture->LoadFromFile("grafika/cross.bmp");
        Image214->Picture->LoadFromFile("grafika/cross.bmp");
        Image215->Picture->LoadFromFile("grafika/cross.bmp");
        Image216->Picture->LoadFromFile("grafika/cross.bmp");
        Image217->Picture->LoadFromFile("grafika/cross.bmp");
        Image218->Picture->LoadFromFile("grafika/cross.bmp");
        Image219->Picture->LoadFromFile("grafika/cross.bmp");
        Image220->Picture->LoadFromFile("grafika/cross.bmp");
        Image221->Picture->LoadFromFile("grafika/cross.bmp");
        Image222->Picture->LoadFromFile("grafika/cross.bmp");
        Image223->Picture->LoadFromFile("grafika/cross.bmp");
        Image224->Picture->LoadFromFile("grafika/cross.bmp");
        Image225->Picture->LoadFromFile("grafika/cross.bmp");

        Image1->Enabled = true;
        Image2->Enabled = true;
        Image3->Enabled = true;
        Image4->Enabled = true;
        Image5->Enabled = true;
        Image6-> Enabled = true;
        Image7-> Enabled = true;
        Image8->Enabled = true;
        Image9->Enabled = true;
        Image10-> Enabled = true;
        Image11-> Enabled = true;
        Image12-> Enabled = true;
        Image13->Enabled = true;
        Image14-> Enabled = true;
        Image15->Enabled = true;
        Image16->Enabled = true;
        Image17->Enabled = true;
        Image18->Enabled = true;
        Image19-> Enabled = true;
        Image20-> Enabled = true;
        Image21->Enabled = true;
        Image22-> Enabled = true;
        Image23-> Enabled = true;
        Image24->   Enabled = true;
        Image25->Enabled = true;
        Image26->Enabled = true;
        Image27->Enabled = true;
        Image28->Enabled = true;
        Image29->Enabled = true;
        Image30->Enabled = true;
        Image31->Enabled = true;
        Image32->  Enabled = true;
        Image33-> Enabled = true;
        Image34-> Enabled = true;
        Image35-> Enabled = true;
        Image36-> Enabled = true;
        Image37-> Enabled = true;
        Image38-> Enabled = true;
        Image39->Enabled = true;
        Image40->  Enabled = true;
        Image41->Enabled = true;
        Image42->Enabled = true;
        Image43->Enabled = true;
        Image44->Enabled = true;
        Image45->Enabled = true;
        Image46->Enabled = true;
        Image47->Enabled = true;
        Image48-> Enabled = true;
        Image49->Enabled = true;
        Image50-> Enabled = true;
        Image51->  Enabled = true;
        Image52-> Enabled = true;
        Image53->  Enabled = true;
        Image54->   Enabled = true;
        Image55->Enabled = true;
        Image56->Enabled = true;
        Image57->Enabled = true;
        Image58-> Enabled = true;
        Image59->Enabled = true;
        Image60->Enabled = true;
        Image61->Enabled = true;
        Image62-> Enabled = true;
        Image63->Enabled = true;
        Image64->Enabled = true;
        Image65-> Enabled = true;
        Image66->Enabled = true;
        Image67->Enabled = true;
        Image68->Enabled = true;
        Image69->  Enabled = true;
        Image70-> Enabled = true;
        Image71-> Enabled = true;
        Image72->   Enabled = true;
        Image73-> Enabled = true;
        Image74->Enabled = true;
        Image75-> Enabled = true;
        Image76->Enabled = true;
        Image77->Enabled = true;
        Image78->Enabled = true;
        Image79->Enabled = true;
        Image80->Enabled = true;
        Image81->Enabled = true;
        Image82-> Enabled = true;
        Image83->Enabled = true;
        Image84->Enabled = true;
        Image85->Enabled = true;
        Image86->Enabled = true;
        Image87-> Enabled = true;
        Image88->Enabled = true;
        Image89->Enabled = true;
        Image90->Enabled = true;
        Image91-> Enabled = true;
        Image92->Enabled = true;
        Image93-> Enabled = true;
        Image94->Enabled = true;
        Image95->Enabled = true;
        Image96->Enabled = true;
        Image97->Enabled = true;
        Image98->Enabled = true;
        Image99->Enabled = true;
        Image100->Enabled = true;

        Image101->Enabled = true;
        Image102->Enabled = true;
        Image103-> Enabled = true;
        Image104->Enabled = true;
        Image105->Enabled = true;
        Image106-> Enabled = true;
        Image107->Enabled = true;
        Image108-> Enabled = true;
        Image109-> Enabled = true;
        Image110-> Enabled = true;
        Image111-> Enabled = true;
        Image112->Enabled = true;
        Image113->Enabled = true;
        Image114->Enabled = true;
        Image115->Enabled = true;
        Image116->Enabled = true;
        Image117->Enabled = true;
        Image118->Enabled = true;
        Image119-> Enabled = true;
        Image120->Enabled = true;
        Image121->Enabled = true;
        Image122->Enabled = true;
        Image123-> Enabled = true;
        Image124->Enabled = true;
        Image125-> Enabled = true;
        Image126-> Enabled = true;
        Image127->Enabled = true;
        Image128->Enabled = true;
        Image129->Enabled = true;
        Image130->Enabled = true;
        Image131-> Enabled = true;
        Image132->Enabled = true;
        Image133-> Enabled = true;
        Image134->Enabled = true;
        Image135->Enabled = true;
        Image136->Enabled = true;
        Image137-> Enabled = true;
        Image138-> Enabled = true;
        Image139->   Enabled = true;
        Image140->  Enabled = true;
        Image141-> Enabled = true;
        Image142->  Enabled = true;
        Image143-> Enabled = true;
        Image144->Enabled = true;
        Image145-> Enabled = true;
        Image146-> Enabled = true;
        Image147->  Enabled = true;
        Image148->Enabled = true;
        Image149->Enabled = true;
        Image150->Enabled = true;
        Image151->Enabled = true;
        Image152->Enabled = true;
        Image153->Enabled = true;
        Image154->Enabled = true;
        Image155->Enabled = true;
        Image156->Enabled = true;
        Image157->Enabled = true;
        Image158->Enabled = true;
        Image159->Enabled = true;
        Image160->Enabled = true;
        Image161->Enabled = true;
        Image162->Enabled = true;
        Image163->Enabled = true;
        Image164->Enabled = true;
        Image165->Enabled = true;
        Image166->Enabled = true;
        Image167->Enabled = true;
        Image168->Enabled = true;
        Image169->Enabled = true;
        Image170->Enabled = true;
        Image171->Enabled = true;
        Image172->Enabled = true;
        Image173->Enabled = true;
        Image174-> Enabled = true;
        Image175->Enabled = true;
        Image176->Enabled = true;
        Image177->Enabled = true;
        Image178->Enabled = true;
        Image179->Enabled = true;
        Image180->Enabled = true;
        Image181->Enabled = true;
        Image182-> Enabled = true;
        Image183->Enabled = true;
        Image184->Enabled = true;
        Image185->Enabled = true;
        Image186->Enabled = true;
        Image187->Enabled = true;
        Image188->Enabled = true;
        Image189-> Enabled = true;
        Image190->Enabled = true;
        Image191->Enabled = true;
        Image192->Enabled = true;
        Image193->Enabled = true;
        Image194->Enabled = true;
        Image195->Enabled = true;
        Image196-> Enabled = true;
        Image197->Enabled = true;
        Image198->Enabled = true;
        Image199-> Enabled = true;
        Image200-> Enabled = true;
        Image201-> Enabled = true;
        Image202->Enabled = true;
        Image203->  Enabled = true;
        Image204-> Enabled = true;
        Image205->Enabled = true;
        Image206->  Enabled = true;
        Image207->Enabled = true;
        Image208->Enabled = true;
        Image209-> Enabled = true;
        Image210-> Enabled = true;
        Image211-> Enabled = true;
        Image212->Enabled = true;
        Image213->Enabled = true;
        Image214->Enabled = true;
        Image215->Enabled = true;
        Image216->  Enabled = true;
        Image217->   Enabled = true;
        Image218-> Enabled = true;
        Image219->  Enabled = true;
        Image220-> Enabled = true;
        Image221->Enabled = true;
        Image222->Enabled = true;
        Image223->Enabled = true;
        Image224->Enabled = true;
        Image225->Enabled = true;

         //std::string kto=" o ";
         //int turn=1;

}
//---------------------------------------------------------------------------


void __fastcall TForm1::Image1Click(TObject *Sender)
{
 if(board[0][0]=="   ")
   {
      if(kto==" o ")
      {
         Image1->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image1->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image1->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image2Click(TObject *Sender)
{
      if(board[0][1]=="   ")
   {
      if(kto==" o ")
      {
         Image2->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image2->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image2->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image3Click(TObject *Sender)
{
 if(board[0][2]=="   ")
   {
      if(kto==" o ")
      {
         Image3->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image3->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image3->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image4Click(TObject *Sender)
{
 if(board[0][3]=="   ")
   {
      if(kto==" o ")
      {
         Image4->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image4->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image4->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image5Click(TObject *Sender)
{
 if(board[0][4]=="   ")
   {
      if(kto==" o ")
      {
         Image5->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image5->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image5->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image6Click(TObject *Sender)
{
 if(board[0][5]=="   ")
   {
      if(kto==" o ")
      {
         Image6->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image6->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image6->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image7Click(TObject *Sender)
{
 if(board[0][6]=="   ")
   {
      if(kto==" o ")
      {
         Image7->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image7->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image7->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image8Click(TObject *Sender)
{
 if(board[0][7]=="   ")
   {
      if(kto==" o ")
      {
         Image8->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image8->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image8->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image9Click(TObject *Sender)
{
 if(board[0][8]=="   ")
   {
      if(kto==" o ")
      {
         Image9->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image9->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image9->Enabled=false;
      algorythms();
   }

}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image10Click(TObject *Sender)
{
 if(board[0][9]=="   ")
   {
      if(kto==" o ")
      {
         Image10->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image10->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image10->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image12Click(TObject *Sender)
{
      if(board[0][11]=="   ")
   {
      if(kto==" o ")
      {
         Image12->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image12->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image12->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image11Click(TObject *Sender)
{
 if(board[0][10]=="   ")
   {
      if(kto==" o ")
      {
         Image11->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image11->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image11->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image13Click(TObject *Sender)
{
 if(board[0][12]=="   ")
   {
      if(kto==" o ")
      {
         Image13->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image13->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image13->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image14Click(TObject *Sender)
{
 if(board[0][13]=="   ")
   {
      if(kto==" o ")
      {
         Image14->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image14->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image14->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image15Click(TObject *Sender)
{
 if(board[0][14]=="   ")
   {
      if(kto==" o ")
      {
         Image15->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[0][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image15->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[0][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image15->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image16Click(TObject *Sender)
{
 if(board[1][0]=="   ")
   {
      if(kto==" o ")
      {
         Image16->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image16->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image16->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image17Click(TObject *Sender)
{
 if(board[1][1]=="   ")
   {
      if(kto==" o ")
      {
         Image17->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image17->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image17->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image18Click(TObject *Sender)
{
 if(board[1][2]=="   ")
   {
      if(kto==" o ")
      {
         Image18->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image18->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image18->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image19Click(TObject *Sender)
{
 if(board[1][3]=="   ")
   {
      if(kto==" o ")
      {
         Image19->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image19->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image19->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image20Click(TObject *Sender)
{
 if(board[1][4]=="   ")
   {
      if(kto==" o ")
      {
         Image20->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image20->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image20->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image21Click(TObject *Sender)
{
 if(board[1][5]=="   ")
   {
      if(kto==" o ")
      {
         Image21->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image21->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image21->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image22Click(TObject *Sender)
{
 if(board[1][6]=="   ")
   {
      if(kto==" o ")
      {
         Image22->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image22->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image22->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image23Click(TObject *Sender)
{
 if(board[1][7]=="   ")
   {
      if(kto==" o ")
      {
         Image23->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image23->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image23->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image24Click(TObject *Sender)
{
 if(board[1][8]=="   ")
   {
      if(kto==" o ")
      {
         Image24->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image24->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image24->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image25Click(TObject *Sender)
{
 if(board[1][9]=="   ")
   {
      if(kto==" o ")
      {
         Image25->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image25->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image25->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image26Click(TObject *Sender)
{
 if(board[1][10]=="   ")
   {
      if(kto==" o ")
      {
         Image26->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image26->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image26->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image27Click(TObject *Sender)
{
 if(board[1][11]=="   ")
   {
      if(kto==" o ")
      {
         Image27->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image27->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image27->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image28Click(TObject *Sender)
{
 if(board[1][12]=="   ")
   {
      if(kto==" o ")
      {
         Image28->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image28->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image28->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image29Click(TObject *Sender)
{
 if(board[1][13]=="   ")
   {
      if(kto==" o ")
      {
         Image29->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image29->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image29->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image30Click(TObject *Sender)
{
 if(board[1][14]=="   ")
   {
      if(kto==" o ")
      {
         Image30->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[1][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image30->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[1][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image30->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image31Click(TObject *Sender)
{
  if(board[2][0]=="   ")
     {
      if(kto==" o ")
      {
         Image31->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image31->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image31->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image32Click(TObject *Sender)
{
  if(board[2][1]=="   ")
     {
      if(kto==" o ")
      {
         Image31->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image31->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image31->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image33Click(TObject *Sender)
{
  if(board[2][2]=="   ")
     {
      if(kto==" o ")
      {
         Image33->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image33->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image33->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image34Click(TObject *Sender)
{
  if(board[2][3]=="   ")
     {
      if(kto==" o ")
      {
         Image34->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image34->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image34->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image35Click(TObject *Sender)
{
  if(board[2][4]=="   ")
     {
      if(kto==" o ")
      {
         Image35->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image35->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image35->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image36Click(TObject *Sender)
{
  if(board[2][5]=="   ")
     {
      if(kto==" o ")
      {
         Image36->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image36->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image36->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image37Click(TObject *Sender)
{
  if(board[2][6]=="   ")
     {
      if(kto==" o ")
      {
         Image37->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image37->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image37->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image38Click(TObject *Sender)
{
  if(board[2][7]=="   ")
     {
      if(kto==" o ")
      {
         Image38->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image38->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image38->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image39Click(TObject *Sender)
{
  if(board[2][8]=="   ")
     {
      if(kto==" o ")
      {
         Image39->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image39->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image39->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image40Click(TObject *Sender)
{
  if(board[2][9]=="   ")
     {
      if(kto==" o ")
      {
         Image40->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image40->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image40->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image41Click(TObject *Sender)
{
   if(board[2][10]=="   ")
     {
      if(kto==" o ")
      {
         Image41->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image41->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image41->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image42Click(TObject *Sender)
{
   if(board[2][11]=="   ")
     {
      if(kto==" o ")
      {
         Image42->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image42->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image42->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image43Click(TObject *Sender)
{
   if(board[2][12]=="   ")
     {
      if(kto==" o ")
      {
         Image43->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image43->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image43->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image44Click(TObject *Sender)
{
   if(board[2][13]=="   ")
     {
      if(kto==" o ")
      {
         Image44->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[2][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image44->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[2][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image44->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image45Click(TObject *Sender)
{
   if(board[3][14]=="   ")
     {
      if(kto==" o ")
      {
         Image45->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image45->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image45->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image46Click(TObject *Sender)
{
   if(board[3][0]=="   ")
     {
      if(kto==" o ")
      {
         Image46->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image46->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image46->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image47Click(TObject *Sender)
{
   if(board[3][1]=="   ")
     {
      if(kto==" o ")
      {
         Image47->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image47->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image47->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image48Click(TObject *Sender)
{
   if(board[3][2]=="   ")
     {
      if(kto==" o ")
      {
         Image48->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image48->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image48->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image49Click(TObject *Sender)
{
   if(board[3][3]=="   ")
     {
      if(kto==" o ")
      {
         Image49->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image49->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image49->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image50Click(TObject *Sender)
{
   if(board[3][4]=="   ")
     {
      if(kto==" o ")
      {
         Image50->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image50->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image50->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image51Click(TObject *Sender)
{
   if(board[3][5]=="   ")
     {
      if(kto==" o ")
      {
         Image51->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image51->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image51->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image52Click(TObject *Sender)
{
   if(board[3][6]=="   ")
     {
      if(kto==" o ")
      {
         Image52->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image52->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image52->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image53Click(TObject *Sender)
{
   if(board[3][7]=="   ")
     {
      if(kto==" o ")
      {
         Image53->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image53->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image53->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image54Click(TObject *Sender)
{
   if(board[3][8]=="   ")
     {
      if(kto==" o ")
      {
         Image54->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image54->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image54->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image55Click(TObject *Sender)
{
   if(board[3][9]=="   ")
     {
      if(kto==" o ")
      {
         Image55->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image55->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image55->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image56Click(TObject *Sender)
{
   if(board[3][10]=="   ")
     {
      if(kto==" o ")
      {
         Image56->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image56->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image56->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image57Click(TObject *Sender)
{
   if(board[3][11]=="   ")
     {
      if(kto==" o ")
      {
         Image57->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image57->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image57->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image58Click(TObject *Sender)
{
   if(board[3][12]=="   ")
     {
      if(kto==" o ")
      {
         Image58->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image58->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image58->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image59Click(TObject *Sender)
{
   if(board[3][13]=="   ")
     {
      if(kto==" o ")
      {
         Image59->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image59->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image59->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image60Click(TObject *Sender)
{
   if(board[3][14]=="   ")
     {
      if(kto==" o ")
      {
         Image60->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[3][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image60->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[3][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image60->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image61Click(TObject *Sender)
{
   if(board[4][0]=="   ")
     {
      if(kto==" o ")
      {
         Image61->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image61->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image61->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image62Click(TObject *Sender)
{
   if(board[4][1]=="   ")
     {
      if(kto==" o ")
      {
         Image62->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image62->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image62->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image63Click(TObject *Sender)
{
   if(board[4][2]=="   ")
     {
      if(kto==" o ")
      {
         Image63->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image63->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image63->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image64Click(TObject *Sender)
{
   if(board[4][3]=="   ")
     {
      if(kto==" o ")
      {
         Image64->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image64->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image64->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image65Click(TObject *Sender)
{
   if(board[4][4]=="   ")
     {
      if(kto==" o ")
      {
         Image65->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image65->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image65->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image66Click(TObject *Sender)
{
   if(board[4][5]=="   ")
     {
      if(kto==" o ")
      {
         Image66->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image66->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image66->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image67Click(TObject *Sender)
{
   if(board[4][6]=="   ")
     {
      if(kto==" o ")
      {
         Image67->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image67->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image67->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image68Click(TObject *Sender)
{
   if(board[4][7]=="   ")
     {
      if(kto==" o ")
      {
         Image68->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image68->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image68->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image69Click(TObject *Sender)
{
   if(board[4][8]=="   ")
     {
      if(kto==" o ")
      {
         Image69->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image69->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image69->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image70Click(TObject *Sender)
{
   if(board[4][9]=="   ")
     {
      if(kto==" o ")
      {
         Image70->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image70->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image70->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image71Click(TObject *Sender)
{
   if(board[4][10]=="   ")
     {
      if(kto==" o ")
      {
         Image71->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image71->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image71->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image72Click(TObject *Sender)
{
   if(board[4][11]=="   ")
     {
      if(kto==" o ")
      {
         Image72->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image72->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image72->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image73Click(TObject *Sender)
{
   if(board[4][12]=="   ")
     {
      if(kto==" o ")
      {
         Image73->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image73->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image73->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image74Click(TObject *Sender)
{
   if(board[4][13]=="   ")
     {
      if(kto==" o ")
      {
         Image74->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image74->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image74->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image75Click(TObject *Sender)
{
   if(board[4][14]=="   ")
     {
      if(kto==" o ")
      {
         Image75->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[4][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image75->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[4][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image75->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image76Click(TObject *Sender)
{
   if(board[5][0]=="   ")
     {
      if(kto==" o ")
      {
         Image76->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image76->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image76->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image77Click(TObject *Sender)
{
  if(board[5][1]=="   ")
     {
      if(kto==" o ")
      {
         Image77->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image77->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image77->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image78Click(TObject *Sender)
{
  if(board[5][2]=="   ")
     {
      if(kto==" o ")
      {
         Image78->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image78->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image78->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image79Click(TObject *Sender)
{
  if(board[5][3]=="   ")
     {
      if(kto==" o ")
      {
         Image79->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image79->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image79->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image80Click(TObject *Sender)
{
  if(board[5][4]=="   ")
     {
      if(kto==" o ")
      {
         Image80->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image80->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image80->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image81Click(TObject *Sender)
{
  if(board[5][5]=="   ")
     {
      if(kto==" o ")
      {
         Image81->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image81->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image81->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image82Click(TObject *Sender)
{
  if(board[5][6]=="   ")
     {
      if(kto==" o ")
      {
         Image82->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image82->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image82->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image83Click(TObject *Sender)
{
  if(board[5][7]=="   ")
     {
      if(kto==" o ")
      {
         Image83->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image83->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image83->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image84Click(TObject *Sender)
{
  if(board[5][8]=="   ")
     {
      if(kto==" o ")
      {
         Image84->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image84->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image84->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image85Click(TObject *Sender)
{
  if(board[5][9]=="   ")
     {
      if(kto==" o ")
      {
         Image85->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image85->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image85->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image86Click(TObject *Sender)
{
  if(board[5][10]=="   ")
     {
      if(kto==" o ")
      {
         Image86->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image86->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image86->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image87Click(TObject *Sender)
{
  if(board[5][11]=="   ")
     {
      if(kto==" o ")
      {
         Image87->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image87->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image87->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image88Click(TObject *Sender)
{
  if(board[5][12]=="   ")
     {
      if(kto==" o ")
      {
         Image88->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image88->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image88->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image89Click(TObject *Sender)
{
  if(board[5][13]=="   ")
     {
      if(kto==" o ")
      {
         Image89->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image89->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image89->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image90Click(TObject *Sender)
{
  if(board[5][14]=="   ")
     {
      if(kto==" o ")
      {
         Image90->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[5][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image90->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[5][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image90->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image91Click(TObject *Sender)
{
  if(board[6][0]=="   ")
     {
      if(kto==" o ")
      {
         Image91->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image91->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image91->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image92Click(TObject *Sender)
{
  if(board[6][1]=="   ")
     {
      if(kto==" o ")
      {
         Image92->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image92->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image92->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image93Click(TObject *Sender)
{
  if(board[6][2]=="   ")
     {
      if(kto==" o ")
      {
         Image93->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image93->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image93->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image94Click(TObject *Sender)
{
  if(board[6][3]=="   ")
     {
      if(kto==" o ")
      {
         Image94->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image94->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image94->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image95Click(TObject *Sender)
{
  if(board[6][4]=="   ")
     {
      if(kto==" o ")
      {
         Image95->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image95->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image95->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image96Click(TObject *Sender)
{
  if(board[6][5]=="   ")
     {
      if(kto==" o ")
      {
         Image96->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image96->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image96->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image97Click(TObject *Sender)
{
  if(board[6][6]=="   ")
     {
      if(kto==" o ")
      {
         Image97->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image97->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image97->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image98Click(TObject *Sender)
{
  if(board[6][7]=="   ")
     {
      if(kto==" o ")
      {
         Image98->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image98->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image98->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image99Click(TObject *Sender)
{
  if(board[6][8]=="   ")
     {
      if(kto==" o ")
      {
         Image99->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image99->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image99->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image100Click(TObject *Sender)
{
  if(board[6][9]=="   ")
     {
      if(kto==" o ")
      {
         Image100->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image100->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image100->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image101Click(TObject *Sender)
{
  if(board[6][10]=="   ")
     {
      if(kto==" o ")
      {
         Image101->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image101->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image101->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image102Click(TObject *Sender)
{
  if(board[6][11]=="   ")
     {
      if(kto==" o ")
      {
         Image102->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image102->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image102->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image103Click(TObject *Sender)
{
  if(board[6][12]=="   ")
     {
      if(kto==" o ")
      {
         Image103->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image103->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image103->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image104Click(TObject *Sender)
{
  if(board[6][13]=="   ")
     {
      if(kto==" o ")
      {
         Image104->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image104->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image140->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image105Click(TObject *Sender)
{
  if(board[6][14]=="   ")
     {
      if(kto==" o ")
      {
         Image105->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[6][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image105->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[6][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image105->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image106Click(TObject *Sender)
{
  if(board[7][0]=="   ")
     {
      if(kto==" o ")
      {
         Image106->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image106->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image106->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image107Click(TObject *Sender)
{
  if(board[7][1]=="   ")
     {
      if(kto==" o ")
      {
         Image107->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image107->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image107->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image108Click(TObject *Sender)
{
  if(board[7][2]=="   ")
     {
      if(kto==" o ")
      {
         Image108->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image108->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image108->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image109Click(TObject *Sender)
{
  if(board[7][3]=="   ")
     {
      if(kto==" o ")
      {
         Image109->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image109->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image109->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image110Click(TObject *Sender)
{
  if(board[7][4]=="   ")
     {
      if(kto==" o ")
      {
         Image110->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image110->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image110->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image111Click(TObject *Sender)
{
  if(board[7][5]=="   ")
     {
      if(kto==" o ")
      {
         Image111->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image111->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image111->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image112Click(TObject *Sender)
{
  if(board[7][6]=="   ")
     {
      if(kto==" o ")
      {
         Image112->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image112->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image112->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image113Click(TObject *Sender)
{
  if(board[7][7]=="   ")
     {
      if(kto==" o ")
      {
         Image113->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image113->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image113->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image114Click(TObject *Sender)
{
  if(board[7][8]=="   ")
     {
      if(kto==" o ")
      {
         Image114->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image114->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image114->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image115Click(TObject *Sender)
{
  if(board[7][9]=="   ")
     {
      if(kto==" o ")
      {
         Image115->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image115->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image115->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image116Click(TObject *Sender)
{
  if(board[7][10]=="   ")
     {
      if(kto==" o ")
      {
         Image116->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image116->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image116->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image117Click(TObject *Sender)
{
  if(board[7][11]=="   ")
     {
      if(kto==" o ")
      {
         Image117->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image117->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image117->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image118Click(TObject *Sender)
{
  if(board[7][12]=="   ")
     {
      if(kto==" o ")
      {
         Image118->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image118->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image118->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image119Click(TObject *Sender)
{
  if(board[7][13]=="   ")
     {
      if(kto==" o ")
      {
         Image119->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image119->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image119->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image120Click(TObject *Sender)
{
  if(board[7][14]=="   ")
     {
      if(kto==" o ")
      {
         Image120->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[7][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image120->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[7][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image120->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image121Click(TObject *Sender)
{
  if(board[8][0]=="   ")
     {
      if(kto==" o ")
      {
         Image121->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image121->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image121->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image122Click(TObject *Sender)
{
  if(board[8][1]=="   ")
     {
      if(kto==" o ")
      {
         Image122->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image122->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image122->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image123Click(TObject *Sender)
{
  if(board[8][2]=="   ")
     {
      if(kto==" o ")
      {
         Image123->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image123->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image123->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image124Click(TObject *Sender)
{
  if(board[8][3]=="   ")
     {
      if(kto==" o ")
      {
         Image124->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image124->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image124->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image125Click(TObject *Sender)
{
  if(board[8][4]=="   ")
     {
      if(kto==" o ")
      {
         Image125->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image125->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image125->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image126Click(TObject *Sender)
{
  if(board[8][5]=="   ")
     {
      if(kto==" o ")
      {
         Image126->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image126->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image126->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image127Click(TObject *Sender)
{
  if(board[8][6]=="   ")
     {
      if(kto==" o ")
      {
         Image127->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image127->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image127->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image128Click(TObject *Sender)
{
  if(board[8][7]=="   ")
     {
      if(kto==" o ")
      {
         Image128->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image128->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image128->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image129Click(TObject *Sender)
{
  if(board[8][8]=="   ")
     {
      if(kto==" o ")
      {
         Image129->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image129->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image129->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image130Click(TObject *Sender)
{
  if(board[8][9]=="   ")
     {
      if(kto==" o ")
      {
         Image130->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image130->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image130->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image131Click(TObject *Sender)
{
  if(board[8][10]=="   ")
     {
      if(kto==" o ")
      {
         Image131->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image131->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image131->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image132Click(TObject *Sender)
{
  if(board[8][11]=="   ")
     {
      if(kto==" o ")
      {
         Image132->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image132->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image132->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image133Click(TObject *Sender)
{
  if(board[8][12]=="   ")
     {
      if(kto==" o ")
      {
         Image133->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image133->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image133->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image134Click(TObject *Sender)
{
  if(board[8][13]=="   ")
     {
      if(kto==" o ")
      {
         Image134->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image134->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image134->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image135Click(TObject *Sender)
{
  if(board[8][14]=="   ")
     {
      if(kto==" o ")
      {
         Image135->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[8][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image135->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[8][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image135->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image136Click(TObject *Sender)
{
  if(board[9][0]=="   ")
     {
      if(kto==" o ")
      {
         Image136->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image136->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image136->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image137Click(TObject *Sender)
{
  if(board[9][1]=="   ")
     {
      if(kto==" o ")
      {
         Image137->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image137->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image137->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image138Click(TObject *Sender)
{
  if(board[9][2]=="   ")
     {
      if(kto==" o ")
      {
         Image138->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image138->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image138->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image139Click(TObject *Sender)
{
   if(board[9][3]=="   ")
     {
      if(kto==" o ")
      {
         Image139->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image139->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image139->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image140Click(TObject *Sender)
{
  if(board[9][4]=="   ")
     {
      if(kto==" o ")
      {
         Image140->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image140->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image140->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image141Click(TObject *Sender)
{
  if(board[9][5]=="   ")
     {
      if(kto==" o ")
      {
         Image141->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image141->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image141->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image142Click(TObject *Sender)
{
  if(board[9][6]=="   ")
     {
      if(kto==" o ")
      {
         Image142->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image142->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image142->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image143Click(TObject *Sender)
{
  if(board[9][7]=="   ")
     {
      if(kto==" o ")
      {
         Image143->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image143->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image143->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image144Click(TObject *Sender)
{
  if(board[9][8]=="   ")
     {
      if(kto==" o ")
      {
         Image144->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image144->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image144->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image145Click(TObject *Sender)
{
  if(board[9][9]=="   ")
     {
      if(kto==" o ")
      {
         Image145->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image145->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image145->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image146Click(TObject *Sender)
{
  if(board[9][10]=="   ")
     {
      if(kto==" o ")
      {
         Image146->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image146->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image146->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image147Click(TObject *Sender)
{
  if(board[9][11]=="   ")
     {
      if(kto==" o ")
      {
         Image147->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image147->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image147->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image148Click(TObject *Sender)
{
  if(board[9][12]=="   ")
     {
      if(kto==" o ")
      {
         Image148->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image148->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image148->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image149Click(TObject *Sender)
{
  if(board[9][13]=="   ")
     {
      if(kto==" o ")
      {
         Image149->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image149->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image149->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image150Click(TObject *Sender)
{
  if(board[9][14]=="   ")
     {
      if(kto==" o ")
      {
         Image150->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[9][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image150->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[9][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image150->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image151Click(TObject *Sender)
{
  if(board[10][0]=="   ")
     {
      if(kto==" o ")
      {
         Image151->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image151->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image151->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image152Click(TObject *Sender)
{
  if(board[10][1]=="   ")
     {
      if(kto==" o ")
      {
         Image152->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image152->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image152->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image153Click(TObject *Sender)
{
  if(board[10][2]=="   ")
     {
      if(kto==" o ")
      {
         Image153->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image153->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image153->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image154Click(TObject *Sender)
{
  if(board[10][3]=="   ")
     {
      if(kto==" o ")
      {
         Image154->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image154->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image154->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image155Click(TObject *Sender)
{
  if(board[10][4]=="   ")
     {
      if(kto==" o ")
      {
         Image155->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image155->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image155->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image156Click(TObject *Sender)
{
  if(board[10][5]=="   ")
     {
      if(kto==" o ")
      {
         Image156->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image156->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image156->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image157Click(TObject *Sender)
{
  if(board[10][6]=="   ")
     {
      if(kto==" o ")
      {
         Image157->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image157->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image157->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image158Click(TObject *Sender)
{
  if(board[10][7]=="   ")
     {
      if(kto==" o ")
      {
         Image158->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image158->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image158->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image159Click(TObject *Sender)
{
  if(board[10][8]=="   ")
     {
      if(kto==" o ")
      {
         Image159->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image159->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image159->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image160Click(TObject *Sender)
{
  if(board[10][9]=="   ")
     {
      if(kto==" o ")
      {
         Image160->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image160->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image160->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image161Click(TObject *Sender)
{
  if(board[10][10]=="   ")
     {
      if(kto==" o ")
      {
         Image161->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image161->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image161->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image162Click(TObject *Sender)
{
  if(board[10][11]=="   ")
     {
      if(kto==" o ")
      {
         Image162->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image162->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image162->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image163Click(TObject *Sender)
{
  if(board[10][12]=="   ")
     {
      if(kto==" o ")
      {
         Image163->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image163->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image163->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image164Click(TObject *Sender)
{
  if(board[10][13]=="   ")
     {
      if(kto==" o ")
      {
         Image164->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image164->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image164->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image165Click(TObject *Sender)
{
  if(board[10][14]=="   ")
     {
      if(kto==" o ")
      {
         Image165->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[10][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image165->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[10][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image165->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image166Click(TObject *Sender)
{
  if(board[11][0]=="   ")
     {
      if(kto==" o ")
      {
         Image166->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image166->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image166->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image167Click(TObject *Sender)
{
  if(board[11][1]=="   ")
     {
      if(kto==" o ")
      {
         Image167->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image167->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image167->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image168Click(TObject *Sender)
{
  if(board[11][2]=="   ")
     {
      if(kto==" o ")
      {
         Image168->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image168->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image168->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image169Click(TObject *Sender)
{
  if(board[11][3]=="   ")
     {
      if(kto==" o ")
      {
         Image169->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image169->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image169->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image170Click(TObject *Sender)
{
  if(board[11][4]=="   ")
     {
      if(kto==" o ")
      {
         Image170->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image170->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image170->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image171Click(TObject *Sender)
{
  if(board[11][5]=="   ")
     {
      if(kto==" o ")
      {
         Image171->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image171->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image171->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image172Click(TObject *Sender)
{
  if(board[11][6]=="   ")
     {
      if(kto==" o ")
      {
         Image172->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image172->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image172->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image173Click(TObject *Sender)
{
  if(board[11][7]=="   ")
     {
      if(kto==" o ")
      {
         Image173->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image173->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image173->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image174Click(TObject *Sender)
{
  if(board[11][8]=="   ")
     {
      if(kto==" o ")
      {
         Image174->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image174->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image174->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image175Click(TObject *Sender)
{
  if(board[11][9]=="   ")
     {
      if(kto==" o ")
      {
         Image175->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image175->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image175->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image176Click(TObject *Sender)
{
  if(board[11][10]=="   ")
     {
      if(kto==" o ")
      {
         Image176->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image176->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image176->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image177Click(TObject *Sender)
{
  if(board[11][11]=="   ")
     {
      if(kto==" o ")
      {
         Image177->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image177->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image177->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image178Click(TObject *Sender)
{
  if(board[11][12]=="   ")
     {
      if(kto==" o ")
      {
         Image178->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image178->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image178->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image179Click(TObject *Sender)
{
  if(board[11][13]=="   ")
     {
      if(kto==" o ")
      {
         Image179->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image179->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image179->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image180Click(TObject *Sender)
{
  if(board[11][14]=="   ")
     {
      if(kto==" o ")
      {
         Image180->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[11][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image180->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[11][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image180->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image181Click(TObject *Sender)
{
  if(board[12][0]=="   ")
     {
      if(kto==" o ")
      {
         Image181->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image181->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image181->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image182Click(TObject *Sender)
{
  if(board[12][1]=="   ")
     {
      if(kto==" o ")
      {
         Image182->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image182->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image182->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image183Click(TObject *Sender)
{
  if(board[12][2]=="   ")
     {
      if(kto==" o ")
      {
         Image183->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image183->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image183->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image184Click(TObject *Sender)
{
  if(board[12][3]=="   ")
     {
      if(kto==" o ")
      {
         Image184->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image184->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image184->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image185Click(TObject *Sender)
{
  if(board[12][4]=="   ")
     {
      if(kto==" o ")
      {
         Image185->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image185->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image185->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image186Click(TObject *Sender)
{
  if(board[12][5]=="   ")
     {
      if(kto==" o ")
      {
         Image186->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image186->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image186->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image187Click(TObject *Sender)
{
  if(board[12][6]=="   ")
     {
      if(kto==" o ")
      {
         Image187->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image187->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image187->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image188Click(TObject *Sender)
{
  if(board[12][7]=="   ")
     {
      if(kto==" o ")
      {
         Image188->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image188->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image188->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image189Click(TObject *Sender)
{
  if(board[12][8]=="   ")
     {
      if(kto==" o ")
      {
         Image189->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image189->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image189->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image190Click(TObject *Sender)
{
  if(board[12][9]=="   ")
     {
      if(kto==" o ")
      {
         Image190->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image190->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image190->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image191Click(TObject *Sender)
{
  if(board[12][10]=="   ")
     {
      if(kto==" o ")
      {
         Image191->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image191->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image191->Enabled=false;
      algorythms();
   }
}

//---------------------------------------------------------------------------

void __fastcall TForm1::Image192Click(TObject *Sender)
{
  if(board[12][11]=="   ")
     {
      if(kto==" o ")
      {
         Image192->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image192->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image192->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image193Click(TObject *Sender)
{
  if(board[12][12]=="   ")
     {
      if(kto==" o ")
      {
         Image193->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image193->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image193->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image194Click(TObject *Sender)
{
  if(board[12][13]=="   ")
     {
      if(kto==" o ")
      {
         Image194->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image194->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image194->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image195Click(TObject *Sender)
{
  if(board[12][14]=="   ")
     {
      if(kto==" o ")
      {
         Image195->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[12][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image195->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[12][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image195->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image196Click(TObject *Sender)
{
  if(board[13][0]=="   ")
     {
      if(kto==" o ")
      {
         Image196->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image196->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image196->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image197Click(TObject *Sender)
{
  if(board[13][1]=="   ")
     {
      if(kto==" o ")
      {
         Image197->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image197->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image197->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image198Click(TObject *Sender)
{
  if(board[13][2]=="   ")
     {
      if(kto==" o ")
      {
         Image198->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image198->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image198->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image199Click(TObject *Sender)
{
  if(board[13][3]=="   ")
     {
      if(kto==" o ")
      {
         Image199->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image199->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image199->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image200Click(TObject *Sender)
{
  if(board[13][4]=="   ")
     {
      if(kto==" o ")
      {
         Image200->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image200->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image200->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image201Click(TObject *Sender)
{
  if(board[13][5]=="   ")
     {
      if(kto==" o ")
      {
         Image201->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image201->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image201->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image202Click(TObject *Sender)
{
  if(board[13][6]=="   ")
     {
      if(kto==" o ")
      {
         Image202->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image202->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image202->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image203Click(TObject *Sender)
{
  if(board[13][7]=="   ")
     {
      if(kto==" o ")
      {
         Image203->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image203->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image203->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image204Click(TObject *Sender)
{
  if(board[13][8]=="   ")
     {
      if(kto==" o ")
      {
         Image204->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image204->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image204->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image205Click(TObject *Sender)
{
  if(board[13][9]=="   ")
     {
      if(kto==" o ")
      {
         Image205->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image205->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image205->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image206Click(TObject *Sender)
{
  if(board[13][10]=="   ")
     {
      if(kto==" o ")
      {
         Image206->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image206->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image206->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image207Click(TObject *Sender)
{
  if(board[13][11]=="   ")
     {
      if(kto==" o ")
      {
         Image207->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image207->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image207->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image208Click(TObject *Sender)
{
  if(board[13][12]=="   ")
     {
      if(kto==" o ")
      {
         Image208->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image208->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image208->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image209Click(TObject *Sender)
{
  if(board[13][13]=="   ")
     {
      if(kto==" o ")
      {
         Image209->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image209->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image209->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image210Click(TObject *Sender)
{
  if(board[13][14]=="   ")
     {
      if(kto==" o ")
      {
         Image210->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[13][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image210->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[13][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image210->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image211Click(TObject *Sender)
{
  if(board[14][0]=="   ")
     {
      if(kto==" o ")
      {
         Image211->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][0]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image211->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][0]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image211->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image212Click(TObject *Sender)
{
  if(board[14][1]=="   ")
     {
      if(kto==" o ")
      {
         Image212->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][1]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image212->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][1]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image212->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image213Click(TObject *Sender)
{
  if(board[14][2]=="   ")
     {
      if(kto==" o ")
      {
         Image213->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][2]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image213->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][2]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image213->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image214Click(TObject *Sender)
{
  if(board[14][3]=="   ")
     {
      if(kto==" o ")
      {
         Image214->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][3]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image214->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][3]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image214->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image215Click(TObject *Sender)
{
  if(board[14][4]=="   ")
     {
      if(kto==" o ")
      {
         Image215->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][4]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image215->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][4]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image215->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image216Click(TObject *Sender)
{
  if(board[14][5]=="   ")
     {
      if(kto==" o ")
      {
         Image216->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][5]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image216->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][5]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image216->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image217Click(TObject *Sender)
{
  if(board[14][6]=="   ")
     {
      if(kto==" o ")
      {
         Image217->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][6]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image217->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][6]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image217->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image218Click(TObject *Sender)
{
  if(board[14][7]=="   ")
     {
      if(kto==" o ")
      {
         Image218->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][7]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image218->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][7]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image218->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image219Click(TObject *Sender)
{
  if(board[14][8]=="   ")
     {
      if(kto==" o ")
      {
         Image219->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][8]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image219->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][8]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image219->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image220Click(TObject *Sender)
{
  if(board[14][9]=="   ")
     {
      if(kto==" o ")
      {
         Image220->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][9]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image220->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][9]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image220->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image221Click(TObject *Sender)
{
  if(board[14][10]=="   ")
     {
      if(kto==" o ")
      {
         Image221->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][10]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image221->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][10]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image221->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image222Click(TObject *Sender)
{
  if(board[14][11]=="   ")
     {
      if(kto==" o ")
      {
         Image222->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][11]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image222->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][11]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image222->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image223Click(TObject *Sender)
{
  if(board[14][12]=="   ")
     {
      if(kto==" o ")
      {
         Image223->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][12]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image223->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][12]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image223->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image224Click(TObject *Sender)
{
  if(board[14][13]=="   ")
     {
      if(kto==" o ")
      {
         Image224->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][13]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image224->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][13]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image224->Enabled=false;
      algorythms();
   }        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image225Click(TObject *Sender)
{
  if(board[14][14]=="   ")
     {
      if(kto==" o ")
      {
         Image225->Picture->LoadFromFile("grafika/gcircle.bmp");
         board[14][14]=" o ";
         kto=" x ";
         //ruch->Picture->LoadFromFile("img/xsmall.bmp");
      }
      else
      {
         Image225->Picture->LoadFromFile("grafika/rcircle.bmp");
         board[14][14]=" x ";
         kto=" o ";
        // tura->Picture->LoadFromFile("img/osmall.bmp");
      }
     Image225->Enabled=false;
      algorythms();
   }
}
//---------------------------------------------------------------------------

