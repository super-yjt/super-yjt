<h1 align="center">Hi , I'm Desdenmora</h1>

```c++
#include <iostream>
#include <vector>
class Person
{
public:
    inline void setAndPrintName(std::vector<unsigned char> M_name)
    {
        Name = M_name;
        for (std::vector<unsigned char>::iterator it = Name.begin(); it != Name.end(); ++it)
            std::cout << *it;
        std::cout << "\n";
    }
    inline void setAndPrintLanguage(std::vector<unsigned char> M_language)
    {
        Language = M_language;
        for (std::vector<unsigned char>::iterator it = Language.begin(); it != Language.end(); ++it)
            std::cout << *it;
        std::cout << "\n";
    }

private:
    std::vector<unsigned char> Name;
    std::vector<unsigned char> Language;
};
int main(void)
{
    Person Myself;
    Myself.setAndPrintName({'D', 'e', 's', 'd', 'e', 'n', 'm', 'o', 'r', 'a'}); // Desdenmora
    Myself.setAndPrintLanguage({'C', '+', '+', '.', '.', '.'});                 // C++...
}
```
<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=super-yjt&show_icons=true&theme=onedark)
