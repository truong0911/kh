#include<iostream>
#include<math.h>
using namespace std;
int main(){
    int n,t0;
    float arr[100];
    cin >> n >> t0;
    for(int i = 0; i < n; i++){
        cin >> arr[i];
    }
    float ans[100], k = 0;
    while(true){
        float s = 0,a = 0, b = 0, c = 0, d = 0;
        for(int i = 0; i < t0; i++){
            a+=i*arr[i];
        }
        for(int i = 0; i < t0; i++){
            b+=arr[i];
        }
        for(int i = t0; i < n; i++){
            c+=i*arr[i];
        }
        for(int i = t0; i < n; i++){
            d+=arr[i];
        }
        s = (a/b + c/d)/2;
        cout << s << endl;
        if(abs(s-k)<0.01){
            k = s;
            break;
        }
        t0= int(s);
        k = s;
    }
    cout << int(k) << endl;
    return 0;
}
