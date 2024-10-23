// GF-robotic
//the files that i'm including to keep this doc neately
#include <iostream>
#include <cmath>

//to not write"std::"everythime i wrote a code
using namespace vex;

int main() {
  vexcodeInit();
  Brain.Screen.print("GF-robotic");
  Drivetrain.turnFor(left,90,degrees);
  //partsName/code/(specific order);
  //have to name it & have to download some website for use code
    return 0;
}

