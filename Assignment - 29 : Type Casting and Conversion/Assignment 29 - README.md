Assignment – 29 A Job Ready Bootcamp in C++, DSA and IOT MySirG

Type Casting and Conversion

1.Write a C++ program to convert Primitive type to Complex type.
Example -
int main()
{
Complex c1;
Int x=5;
c1=x;
return 0;
}

2. Write a C++ program to convert Complex type to Primitive type.
Example -
int main()
{
Complex c1;
c1.setData(3,4);
int x;
x=c1;
return 0;
}

3. Create a Product class and convert Product type to Item type using constructor
int main()
{
Item i1;
Product p1;
p1.setData(3,4);
i1=p1;
return 0;
}

4. Create Product class and convert Product type to Item type using casting operator
int main()
{
Item i1;
Product p1;
p1.setData(3,4);
i1=p1;
return 0;
}

5. Create two classes Invent1 and Invent2 and also add necessary constructors in it. Now add
functions to support Invent1 to float and Invent1 to Invent2 type.
Example -
int main()
{
Invent1 s1=(4,5);
Invent2 d1;
float tv;
tv=s1;
d1=s1;
return 0;
}

6. Create a Time class and take Duration in seconds. Now you need to convert seconds(i.e in
int ) to Time class.

Example-
int main()
{
int duration;
cout<<”Enter time duration in minutes”;
cin>>duration;
Time t1 = duration;
t1.display();
return 0;
}

7. Create two class Time and Minute and add required getter and setter including constructors.
Now you need to type cast Time object into Minute to fetch the minute from Time and display it.
Example -
int main()
{
Time t1(2,30);
t1.display();
Minute m1;
m1.display();
m1=t1 // Fetch minute from time
t1.display();
m1.display();
return 0;
}

8. Create a Rupee class and convert it into int. And Display it.
Example-
int main()
{
Rupee r = 10;
int x = r;
cout<<x;
return 0;
}

9. Create a Dollar class and add necessary functions to support int to Dollar type conversion.
Example-
int main()
{
int x = 50;
Dollar d;
d = x;
d.display();
return 0;
}

10. Create two classes Rupee and Dollar and add necessary functions to support Rupee to
Dollar and Dollar to Rupee conversion.
Example-
int main()
{
Rupee r = 23;
Dollar d = r; // Rupee to Dollar conversion
d.display();
r.display();
r = d; // Dollar to Rupee Conversion
d.display();
r.display();
return 0;
}
