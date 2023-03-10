
#include <iostream>

using namespace std;

int main()
{
    float r1, r2, r3, r4, rt;

    cout << "Nhap gia tri dien tro R1: ";
    cin >> r1;

    cout << "Nhap gia tri dien tro R2: ";
    cin >> r2;

    cout << "Nhap gia tri dien tro R3: ";
    cin >> r3;

    cout << "Nhap gia tri dien tro R4: ";
    cin >> r4;

    rt = (r1*r2*r3*r4) / (r1*r2 + r1*r3 + r1*r4 + r2*r3 + r2*r4 + r3*r4);

    cout << "Dien tro tuong duong cua 4 dien tro: " << rt << " Ohm";

    return 0;
}
