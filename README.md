import javax.swing.JOptionPane;

    public class Uno {
    
      public static void main(String[] args) {
        int number = -1;

        while (number < 1 || number > 100) {
            String input = JOptionPane.showInputDialog("Enter a number between 1 and 100:");
            number = Integer.parseInt(input);
        }

        JOptionPane.showMessageDialog(null, "You entered: " + number);
    }
}
