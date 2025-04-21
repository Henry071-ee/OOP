# ifndef CYLINDER_CPP
# define CYLINDER_CPP

# include "Cylinder.h"
#include <iomanip>

# define pi 3.14159265358979323846
double Cylinder :: SurfaceArea(){
    double A=0;
    A=2*pi*radius*height+pi*radius*radius*2;
    
    return A;
}

double Cylinder :: Volume(){
    double V=0;
    V=pi*radius*radius*height;
    return V;
}

double Cylinder :: Circumference(){
    double A=0;
    A=2*pi*radius;
    return A;
}

istream & operator>>(istream & in, Cylinder & cldr)
{
    in>>cldr.radius>>cldr.height;
    return in;
}

ostream & operator<<(ostream & out, Cylinder & cldr)
{
    out<<fixed<<setprecision(3)<<"Circumference: "<<cldr.Circumference()<<endl<<"SurfaceArea: "<<cldr.SurfaceArea()<<endl<<"Volume: "<<cldr.Volume()<<endl;
    return out;
}

# endif
