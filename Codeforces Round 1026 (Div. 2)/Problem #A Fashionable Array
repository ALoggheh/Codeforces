#include <bits/stdc++.h>
using namespace std;
int main(){
	ios::sync_with_stdio(false);
	cin.tie(0);
	int tc;
	cin >> tc;
	for (int testcase = 0; testcase < tc; testcase ++){
		int n,k1 = 0;
		vector<int> a;
		cin >> n;
		int k2 = n;
		for (int i = 0; i < n; i++){
			int x;
			cin >> x;
			a.push_back(x);
		}
		sort(a.begin(), a.end());
		while ((a[k1] + a[n-1])%2!=0 && k1 < n-1){
			k1++;
		}
		while ((a[0]+a[k2-1])%2!=0 && k2 > 1){
			k2--;
		}
		if (k1 > n-k2){
			cout << n-k2 << '\n';
		}
		else{
			cout << k1 << '\n';
		}
	}
}
// time: 46 ms 