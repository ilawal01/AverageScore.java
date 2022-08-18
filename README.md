# AverageScore.java
Finding the Average
 import javax.swing.JOptionPane; // Needed for JOptionPane
2
3 /**
4    This program demonstrates the if statement.
5 */
6
7 public class AverageScore
8 {
9    public static void main(String[] args}
10   {
11      double score1;    //To hold score #1
12      double score2;    //To hold score #2
13      double score3;    //To hold score #3
14      double average;   //To hold the average score
15      String input;     //To hold the user's input
16
17      // Get the first test score
18      input = JOptionPlane.showInputDialog("Enter score #1:");
19      scorel = Double.parseDouble(input);
20
21      // Get the second score.
22      input= JOptionPane.showinputDialog("Enter score #2:");
23      score2 = Double.parseDouble(input);
24
25      // Get the third test score.
26      input= JOptionPane.showinputDialog("Enter score #3:");
27      score3 = Double.parseDouble(input);
28
29      // Calculate the average score.
30      average = (score1 + score2 + score3) I 3.0;
31
32      // Display the average score.
33      JOptionPane.showMessageDialog(null,
34                                 "The average is " +average);
35      
36      // If the score was greater than 95, let the user know
37      // that's a great score.
38      if (average > 95)
39      JOptionPane.showMessageDialog(null,
40                                 "That's a great score!");
41
42          System.exit(0);
43       } 
44    }
