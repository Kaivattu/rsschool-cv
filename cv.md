# **Alexander Volkov**
#### Software Engineer
---
**email:** alex.alanen@gmail.com
**Discord:** Sawyer#8347
---
## About me:
I'm interested in web development
---
## Expirience:
**_2020 - to date_**
: Qt/C++ Developer (Desktop apps)

**_2013 - 2020_**
: circuit engineer, microcontroller programmer

---
## Education:
**_2008 - 2013_**
: MIEM University (Faculty of Electronic)

## Skills:
* Qt
* C++
* Javascript
---
## Code Example:
**CodeWars <6kyu>: Given an array of integers, find the one that appears and odd number of time.
There will always be only one integer that appears and odd number of times.**
```
#include <vector>

int findOdd(const std::vector<int>& numbers)
{
  int val;
  int coinc;
  
  for(size_t i = 0; i < numbers.size(); i++)
  {
    val=numbers[i];
    coinc=0;
    
    for(int j:numbers)
    {
      if(val==j)
        coinc++;
    }
    if(coinc%2!=0)
      return val;
   }
}
```
## Languages:
**English - B1**
**Russian - Native**