# switch_operator
switch_operator_Kazakh

    

    #include <iostream>
    using namespace std;

    int main()
    {
	bagdarlama_basy:
	int k;
	cout << "k = " ;
	cin >> k;

	switch (k)
	{ 
	case 1: 
		cout << "Qantar";
		break;
	case 2: 
		cout << "Aqpan";
		break;
	case 3:
		cout << "Nauryz";
		break;
	case 4:
		cout << "Kokek (Sauir)";
		break;
	case 5:
		cout << "Mamyr";
		break;
	case 6:
		cout << "Mausym";
		break;
	case 7:
		cout << "Shilde";
		break;
	case 8:
		cout << "Tamyz";
	case 9:
		cout << "Qyrkuiek";
		break;
	case 10:
		cout << "Qazan";
		break;
	case 11:
		cout << "Qarasha";
		break;
	case 12:
		cout << "Jeltoqsan";
		break;
	default:
		cout << "Mundai ai joq qoi" << endl;
		goto bagdarlama_basy;
		break;
	}
}

