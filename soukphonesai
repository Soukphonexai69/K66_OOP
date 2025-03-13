#include <iostream>
#include <string>
using namespace std;

class Student {
private:
    string name;
    string id;
    double gpa;

public:
    // Constructor
    Student(string studentName, string studentId, double studentGpa) {
        name = studentName;
        id = studentId;
        gpa = studentGpa;
    }

    // Getters
    string getName() const { return name; }
    string getId() const { return id; }
    double getGpa() const { return gpa; }

    // Setters
    void setName(string newName) { name = newName; }
    void setId(string newId) { id = newId; }
    void setGpa(double newGpa) { gpa = newGpa; }

    // Method to display student details
    void displayInfo() const {
        cout << "Student Name: " << name << endl;
        cout << "Student ID: " << id << endl;
        cout << "GPA: " << gpa << endl;
    }
};

int main() {
    // Create a Student object
    Student student1("John Doe", "S12345", 3.75);
    
    // Display student information
    student1.displayInfo();
    
    // Modify student details
    student1.setName("Jane Doe");
    student1.setGpa(3.90);
    
    cout << "\nUpdated Student Information:" << endl;
    student1.displayInfo();
    
    return 0;
}
