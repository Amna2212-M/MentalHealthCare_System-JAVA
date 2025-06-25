import javax.swing.*;

public class MHSM_GUI {
    public static void main(String[] args) {
        JFrame frame = new JFrame("MHSM GUI");
        frame.setSize(400, 200);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

        JLabel label = new JLabel("Welcome to Mental Healthcare System", JLabel.CENTER);
        frame.add(label);

        frame.setVisible(true);
    }
}
