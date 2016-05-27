class cons()
{
double side;
double length,breadth;
double area=(side)*(side);
}
class square extends cons()
{
double perimeter=(4*side);
}
class rectangle extends cons()
{
double area =(length*breadth);
}
square.side=4;
rectangle.length=8;
rectnagle.breadth=6;
system.out.println("rectangle.area is"+rectangle.area);
system.out.println("square.perimeter is"+square.perimeter);
}
