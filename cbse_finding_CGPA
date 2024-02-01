import java.util.*;
class StudentPercentage {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter the number of subjects: ");
        int n = sc.nextInt();

        double[] marks = new double[n];
        // double[] totalmarks = new double[numOfSubjects];
        double totalMarks = 500;
         double total = 0;
        for (int i =0 ; i < n; i++) {
            System.out.print("Enter the marks for subject " + (i+1)+ ": ");
            marks[i] = sc.nextDouble();

            // totalmarks[i] = sc.nextDouble();

            total += marks[i] ;
        }

       
        // double totalMarks = 0;

        // for (int i = 0; i < numOfSubjects; i++) {
        //     total += marks[i] ;
        //     // totalMarks += totalmarks[i];
        // }

        double percentage = total / totalMarks * 100;
        double cgpa = total/50;
        System.out.println("The percentage of the student is: " + percentage + "%");
        System.out.println("The cgpa of the student is: "+cgpa);
        
    }
}
