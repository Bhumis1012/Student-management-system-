# Student-management-system-

                    Micro Project

          Student Management System 



#include <stdio.h>



struct Student {

    char name[50];

    int rollNumber;

    float marks;

};



int main() {

    struct Student student;



    printf("Enter student's name: ");

    fgets(student.name, sizeof(student.name), stdin);



    printf("Enter roll number: ");

    scanf("%d", &student.rollNumber);



    printf("Enter marks: ");

    scanf("%f", &student.marks);



    printf("\nStudent Details:\n");

    printf("Name: %s", student.name);

    printf("Roll Number: %d\n", student.rollNumber);

    printf("Marks: %.2f\n", student.marks);



    return 0;

}

Output :

Enter student's name: Harry Potter

Enter roll number: 1008

Enter marks: 95



Student Details:

Name: Harry Potter

Roll Number: 1008

Marks: 95.00 

--------------------------------







By –

1210 - Siddhi Ashok Patil

1221 - Bhumi Shashank Dounde 

1222 – Ravina Bhauso Jadhav 

