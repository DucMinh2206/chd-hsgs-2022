#include </Library/Developer/CommandLineTools/usr/include/c++/v1/bits/stdc++.h>
#define pb push_back
#define ll long long int
#define dict minh
using namespace std;
int max1(int a, int b){
    return max(a,b);
}
string minh="uwu";
int cnt[3];
int main () {
    ios::sync_with_stdio(0);
    cin.tie(0);
    cout.tie(0);
    int n;
    string s;
    cin>>s;
    n=int(s.length());
    int ans=0;
    for(ll j=0;j<=n-3;j++){
        bool t=true;
        for(ll p=0;p<3;p++){
            if(minh[p]!=s[j+p]){
                t=false;
            }
        }
        if(t==true){
            cnt[j%3]++;
        }
        else{
            ans=max1(ans,cnt[j%3]);
            cnt[j%3]=0;
        }
    }
    for(int j=0;j<3;j++){
        ans=max1(ans,cnt[j%3]);
    }
    cout<<ans;
}
           

