# rock-paper-scissors-game-C-

#include <iostream>
#include <stdlib.h>
#include <cmath>
using namespace std;
// 
//1) look scissors cuts paper paper covers

//2) rock rock crushes lizard lizard poisons

//3) Spock Spock smashes scissors scissors

//4) decapitates lizard lizard eats paper

//5)paper disproves Spock Spock vaporizes

//6)rock and as it always has Rock crushes
//scissors
int user;
int rock = 1;
int paper = 2;
int scissors = 3;
int spoke = 4;
int lizard = 5;




int main(){
  srand (time(NULL));
 
int computer = rand() % 5 + 1;
 
int user = 0;
std::cout << "====================\n";
std::cout << "rock paper scissors!\n";
std::cout << "====================\n";
 
std::cout << "1) rock ✊\n";
std::cout << "2) paper ✋\n";
std::cout << "3) scissors ✌️\n";
std::cout<<  "4 spoke 🖖 \n";
std:cout<<   "5) lizard 🤘 \n";

 
std::cout << "shoot! ";
std::cin>>user;
if (computer == 3 && user == 2){
  std::cout<<"computer wins \n";
   std::cout<<"scissors cuts paper \n";

}

else if (computer == 2 && user == 1)
{
  std::cout<<"computer wins";
   std::cout<<" paper cover rock \n";
}


else if (computer ==1 && user == 5 ){
  std::cout<<"computer wins \n";
   std::cout<<"rock crushes lizard \n";}
else if( computer == 5 && user == 4){
  std::cout<<"computer wins \n";
   std::cout<<" lizard poisons spoke \n";
}
else if (computer ==4  && user == 3 ){
 std::cout<<"computer wins \n";
  std::cout<<"spoke crushes scissors \n";
}
else if (computer == 3 && user == 5 ){
   std::cout<<"computer wins \n";
    std::cout<<"scissors decaptelizes lizard \n";

  
}
else if (computer == 5 && user == 2 ){
   std::cout<<"computer wins \n";
    std::cout<<"lizard eats paper \n";
  
}
else if (computer ==2  && user == 4){
   std::cout<<"computer wins \n";
    std::cout<<"paper disprove spake \n";
  
}
else if (computer == 4 && user == 1 ){
   std::cout<<"computer wins \n";
    std::cout<<"spoke vaporizes rock\n";
  
}

else if (computer == 3 && user == 1){
  std::cout<<"rock crushes scissors \n";
  std::cout<<"user wins \n";

}

else if (computer == 3 && user == 3){
  std::cout<<" \n";
  std::cout<<" its tie \n";
  
}

else if (computer == 3 && user == 4){
  std::cout<<"spoke crushes scissors \n";
  std::cout<<" user wins \n";
  
}

else if (computer == 3 && user == 5){
  std::cout<<"scissors decapitates lizard \n";
  std::cout<<"user wins \n";

}


else if (computer == 2 && user == 2){
  std::cout<<" \n";
  std::cout<<"its a tie \n";
  
}

else if (computer == 2 && user == 3){
  std::cout<<"scissors cuts paper \n";
  std::cout<<"user wins \n";
  
}

else if (computer == 2 && user == 4){
  std::cout<<"paper disproves spoke \n";
  std::cout<<"computer wins \n";

}

else if (computer == 2 && user == 5){
  std::cout<<"lizard eats paper \n";
  std::cout<<"user wins \n";
  
}

else if (computer == 1 && user == 2){
  std::cout<<"paper cover rock\n";
  std::cout<<"user wins \n";
  
}

else if (computer == 1 && user == 3){
  std::cout<<"rock crushes scissors \n";
  std::cout<<"computer wins \n";
}

else if (computer == 1 && user == 4){
  std::cout<<"rock doesnt have any effect on spoke\n";
  std::cout<<"tie \n";
}

else if (computer == 1 && user == 1){
  std::cout<<"\n";
  std::cout<<"its a tie \n";
}

else if (computer == 5 && user == 1){
  std::cout<<"rock crushes lizard\n";
  std::cout<<"user wins \n";
}

else if (computer == 5 && user == 2){
  std::cout<<"lizard eats paper \n";
  std::cout<<"user wins \n";
}
else if (computer == 5 && user == 3){
  std::cout<<"scissors decapitates lizard\n";
  std::cout<<"user wins \n";
}
else if (computer == 5 && user == 5){
  std::cout<<" \n";
  std::cout<<"its a tie \n";
}
else if (computer == 4 && user == 4){
  std::cout<<" \n";
  std::cout<<"its a tie  \n";
}
else if (computer == 4 && user == 5){
  std::cout<<"lizard poisons spoke \n";
  std::cout<<"user wins \n";
}
else if (computer == 4 && user == 1){
  std::cout<<"rock doesnt have any effect on spoke \n";
  std::cout<<"do it again \n";
}

else if (computer == 4 && user == 2){
  std::cout<<"paper disprove spoke\n";
  std::cout<<"user wins \n";
}























else 
std::cout<<"invalid \n";
std::cout<<"computer = ="<<computer<<endl;
std::cout<<"user = ="<<user;









  return 0;
}
