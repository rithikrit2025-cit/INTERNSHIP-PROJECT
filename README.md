# INTERNSHIP-PROJECT CODE ALPHA
Built two C++ applications:  Sudoku Solver using backtracking and recursion to solve puzzles efficiently.  CGPA Calculator to compute student grades and credit‑based averages with precise output.  These projects strengthened my skills in algorithms, structured programming, and practical application development.
cgpa calculator code:
#include <iostream>
using namespace std;

int main() {
    int n;
    float gradePoint, credit;
    float totalCredits = 0, weightedSum = 0;

    cout << "Enter the number of subjects: ";
    cin >> n;

    for (int i = 1; i <= n; i++) {
        cout << "\nSubject " << i << endl;  

        cout << "Enter Grade Point: ";
        cin >> gradePoint;

        cout << "Enter Credits: ";
        cin >> credit;

        weightedSum += gradePoint * credit;
        totalCredits += credit;
    }

    float cgpa = weightedSum / totalCredits;

    cout << "\nCGPA = " << cgpa << endl;

    return 0;
}
<img width="1920" height="1020" alt="Screenshot 2026-06-10 205056" src="https://github.com/user-attachments/assets/e0d5a5bf-d0e3-448c-b914-2ac4837579e3" />
<img width="1920" height="1020" alt="Screenshot 2026-06-10 211838" src="https://github.com/user-attachments/assets/79b17561-0f0e-4a86-9d99-8ccf442a213e" />
