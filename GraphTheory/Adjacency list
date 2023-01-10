//
//  main.cpp
//  GraphTheory
//
//  Created by RAJU MOLLA on 11/1/23.
//

#include <algorithm>
#include <array>
#include <bitset>
#include <cassert>
#include <chrono>
#include <climits>
#include <cmath>
#include <complex>
#include <cstring>
#include <functional>
#include <iomanip>
#include <iostream>
#include <map>
#include <numeric>
#include <queue>
#include <random>
#include <set>
#include <vector>
using namespace std;

vector<int>v[1000000];

int main(){
    int node, edge;
    cin >> node >> edge;
    int x, y;
    while(edge--){
        cin >> x >> y;
        v[x].push_back(y);
        v[y].push_back(x);
    }
    for(int i = 1; i <= node; i++){
        cout << i;
        for(int j = 0; j < v[i].size(); j++){
            cout << "->" << v[i][j];
        }
        cout << '\n';
    }
}
