- 👋 Hi, I’m @XaviErzin
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
XaviErzin/XaviErzin is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
#include <cs50.h> // Adicionar a biblioteca do CS50

int main(void) {
    // get_string é uma função específica da biblioteca do CS50!
    string nome = get_string("Qual é seu nome? \n");
    printf("hello,%s \n",nome);
}
