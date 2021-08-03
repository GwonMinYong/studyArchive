```c++
using namespace std;

long long solution(int price, int money, int count)
{
    long long int answer= (long long)price*(count*(1+count))/2;
    if(money>answer)
    {
        return 0;
    }
    
    return (answer-money);
}
```