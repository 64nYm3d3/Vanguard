# Vanguard
Mockup for building vanguard decks in TTS, TTS requires an images to be in specific format

7x images a row ending with <p style='clear: both;'>

Repeat 6 times with the 7th row being 6 images (the 70th card face in an image is reserved), as unuseable as this code is, it gives me a reference to look at if I follow through and make a website to build Vanguard decks

~~~
cardFaceAll == [$url0,$url1,$url2,$url3...]
// all card urls

string cardFace = 'nothing'

def cardFaceURL;
  for(i=0, i in range cardFaceAll.length, i=i++);
  {
  //iterate through our array of cards, returning the URLfor the desired vanguard to the function
    if (cardFaceAll[i] == true);
        return cardFaceAll[i]
        else;
            break;
   }

public static void main (){
}

public class mapface
{
//returns code to place the image on the page properly
return (<img src='$cardFaceURL" style="float:left; width:14%; margin-right: . 25%; margin-bottom: 0.5em;">)
}
~~~
   
