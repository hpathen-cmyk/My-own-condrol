# My-own-condrol
Mood swing your luck

#include <iostream>
#include <thread>
#include <chrono>

using namespace std;

// Function to display text with delay for "motion" effect
void typeOut(string text, int delay = 40) {
    for (char c : text) {
        cout << c << flush;
        this_thread::sleep_for(chrono::milliseconds(delay));
    }
    cout << endl;
}

int main() {
    system("cls"); // Clear screen (use "clear" if on Linux/Mac)

    typeOut("====================================", 10);
    typeOut("         Soorajkrishna", 60);
    typeOut("  Responsibility on my shoulder", 60);
    typeOut("====================================", 10);
    cout << endl;

    typeOut("Modder | Ethical Hacker | Born to Make History", 40);
    cout << endl;

    typeOut("My Skills:", 40);
    typeOut("💻 Modder", 30);
    typeOut("🧠 Ethical Hacker", 30);
    typeOut("🖥️ Virtual Machine (VM) User", 30);
    typeOut("🔥 Born to Make History", 30);

    cout << endl;
    typeOut("====================================", 10);
    typeOut("        Thank you for visiting!", 50);
    typeOut("====================================", 10);

    return 0;
}
