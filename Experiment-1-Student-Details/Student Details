class Student {
    private String name;
    private int rollNo;
    private int marks;

    Student() {
        name = "";
        rollNo = 0;
        marks = 0;
    }

    public Student(String name, int rollNo, int marks) {
        this.name = name;
        this.rollNo = rollNo;
        this.marks = marks;
    }

    public String getName() {
        return name;
    }

    public int getRollNo() {
        return rollNo;
    }

    public int getMarks() {
        return marks;
    }

    public void setName(String name) {
        this.name = name;
    }

    public void setRollNo(int rollNo) {
        this.rollNo = rollNo;
    }

    public void setMarks(int marks) {
        this.marks = marks;
    }

    public String calculateGrade() {
        if (marks >= 90) {
            return "A";
        } else if (marks >= 80) {
            return "B";
        } else if (marks >= 70) {
            return "C";
        } else if (marks >= 60) {
            return "D";
        } else {
            return "F";
        }
    }

    public void displayDetails() {
        System.out.println("Student Name: " + name);
        System.out.println("Student RollNo: " + rollNo);
        System.out.println("Student Marks: " + marks);
    }
}

class Result extends Student {

    Result(String name, int rollNo, int marks) {
        super(name, rollNo, marks);
    }

    public void displayDetails() {
        System.out.println("--- Student Result ---");
        super.displayDetails();
    }
}

public class StudentResult {
    public static void main(String args[]) {

        Result s1 = new Result("Rahul", 101, 95);
        Result s2 = new Result("Priya", 102, 75);
        Result s3 = new Result("Arun", 103, 58);

        s1.displayDetails();
        System.out.println("Grade: " + s1.calculateGrade());
        System.out.println();

        s2.displayDetails();
        System.out.println("Grade: " + s2.calculateGrade());
        System.out.println();

        s3.displayDetails();
        System.out.println("Grade: " + s3.calculateGrade());
    }
}
