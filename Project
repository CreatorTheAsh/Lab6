#include <iostream>
#include <cstdlib>
#include <math.h>
using namespace std;

double Gerone(double A, double B, double C) {
	double p = (A + B + C) / 2;
	long double S = sqrt(p*(p - A)*(p - B)*(p - C));
	return S;
}

int main() {
	double A, B, C;
	double Output[3];
	double max = 0;;
	for (int i = 0; i < 3; i++) {
		cout << "A:"; cin >> A;
		cout << "B:"; cin >> B;
		cout << "C:"; cin >> C;
		cout << "S = " << Gerone(A, B, C) << "\n";
		Output[i] = Gerone(A, B, C);
		if (Output[i] > max) { max = Output[i]; }
	}
	cout << "max = " << max << "\n";
	system("pause");
	return 0;
}
