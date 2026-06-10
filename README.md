# INTERNSHIP-PROJECT
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
