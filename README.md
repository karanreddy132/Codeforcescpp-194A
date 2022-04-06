# Codeforcescpp-194A
#include <bits/stdc++.h>
using namespace std;

int main() {
	int n, k;
	cin >> n >> k;
	cout << ( k < 3*n ? 3*n-k:0);
	return 0;
}
