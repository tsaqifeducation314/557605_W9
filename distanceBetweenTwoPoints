#include <iostream>
#include <cmath>
using namespace std;

double distance(int x1, int x2, int y1, int y2) {
    double dis = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));
    return dis;
}

double radius(int x1, int x2, int y1, int y2) {
    return distance(x1, x2, y1, y2);
}

double circumference(int x1, int x2, int y1, int y2) {
    const double pi = 3.1416;
    double rad = radius(x1, x2, y1, y2);
    return 2 * pi * rad;
}

double area(int x1, int x2, int y1, int y2) {
    const double pi = 3.1416;
    double rad = radius(x1, x2, y1, y2);
    return pi * rad * rad;
}

int main() {
    int x1, y1, x2, y2;

    cout << "Masukkan koordinat titik pertama / pusat (x1 y1) : ";
    cin >> x1 >> y1;

    cout << "Masukkan koordinat titik kedua (x2 y2)           : ";
    cin >> x2 >> y2;

    double dis = distance(x1, x2, y1, y2);
    double rad = radius(x1, x2, y1, y2);
    double cir = circumference(x1, x2, y1, y2);
    double ar = area(x1, x2, y1, y2);
    
    cout << endl;
    cout << "=== Hasil Perhitungan ===" << endl;
    cout << "Center        : " << x1 << "," << y1 << endl;
    cout << "Distance      : " << dis << endl;
    cout << "Radius        : " << rad << endl;
    cout << "Circumference : " << cir << endl;
    cout << "Area          : " << ar << endl;

    return 0;
}

