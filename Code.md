using namespace std;

void veHCN (int chdai, int chrong); int main()

{ cout << "Ve hinh chu nhat" << endl;

veHCN (3,5); cout<<endl; cout<<endl;

veHCN (4,3); cout<<endl; cout<<endl;

veHCN (5,5);

return 0;

void veHCN (int chdai, int chrong)

for (int i=1;i<=chdai; i++) cout<<"*"; cout<<endl;

for (int j=1;j<=chrong-2;j++)

cout<<"*";

for (int k=1; k<=chdai-2; k++) cout<<" ";

cout<<"*"; cout<<endl;

}

for (int i=1;i<=chdai; i++) cout<<"*"; cout<<endl;

}
