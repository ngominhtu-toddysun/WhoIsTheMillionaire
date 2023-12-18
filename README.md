# WhoIsTheMillionaire
package pkg20_bai_tap_java_co_ban;
import javax.swing.JOptionPane;
public class Who_is_the_Millionnaire {
    public static void main(String[] args) {
        
        int correctChoice = 0;
        int incorrectChoice = 0;
        
        String stringA = JOptionPane.showInputDialog("Import your name: ");
        String respond;
       
        
        
        String ques1 = JOptionPane.showInputDialog("1. What is the biggest alive animal on Earth?");
        if (ques1.equals("whale") || ques1.equals("Whale")) {
            respond = "Good starting! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Incorrecto! (-.-')";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques2 = JOptionPane.showInputDialog("2. The acceleration of gravity on Earth is?");
        if (ques2.equals("9.8")) {
            respond = "Nice! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Wrong amigo! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques3 = JOptionPane.showInputDialog("3. Who is the author of the painting 'Starry Night'?");
        if (ques3.equals("Vincent Van Gogh") || ques3.equals("VanGogh") || ques3.equals("Van Gogh")) {
            respond = "Good kill! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Incorrecto! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques4 = JOptionPane.showInputDialog("4. What is the most using language in the world?");
        if (ques4.equals("Chinese") || ques4.equals("Chingchong") || ques4.equals("chinese") || ques4.equals("chingchong") ) {
            respond = "Perfeito! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Wrong hole! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques5 = JOptionPane.showInputDialog("5. BMW brand belongs to which country?");
        if (ques5.equals("German") || ques5.equals("Germany") || ques5.equals("german") || ques5.equals("germany")) {
            respond = "Exactly amigo! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "c'mon, keep goin'! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques6 = JOptionPane.showInputDialog("6. Import PI number with 5 following numbers after command?");
        if (ques6.equals("3.14159")) {
            respond = "Bingo! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Incorrecto! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques7 = JOptionPane.showInputDialog("7. Another name of assult riffle AK47?");
        if (ques7.equals("kalashnikov 47") || ques7.equals("kalash") || ques7.equals("kalashnikov") || ques7.equals("Kalashnikov") || ques7.equals("Kalash") || ques7.equals("Avtomat Kalashnikova 1947") || ques7.equals("Kalashnikov 47")) {
            respond = "Gotcha! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Incorrecto! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques8 = JOptionPane.showInputDialog("8. The song 'We Will Rock You' belongs to which music band?");
        if (ques8.equals("The Queen")) {
            respond = "Perfeito! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Incorrecto! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques9 = JOptionPane.showInputDialog("9. The main actor of the famous comedy film |Home alone| names 'Kevin McCallister', what is ther real name of him?");
        if (ques9.equals("Macaulay Culkin") || ques9.equals("MacaulayCulkin")) {
            respond = "Unstoppable! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Intentar mas! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        String ques10 = JOptionPane.showInputDialog("10. Which is the capital of Nepal?");
        if (ques10.equals("Kathmandu") || ques10.equals("kathmandu")) {
            respond = "exactly! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Incorrecto! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques11 = JOptionPane.showInputDialog("11. Which is the main Operating System of 'Nokia mobile phone' from 2003 to 2007?");
        if (ques11.equals("Symbian") || ques11.equals("symbian")) {
            respond = "No cap! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "nah! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques12 = JOptionPane.showInputDialog("12. What is the 'Class (body style)' of Toyota Avanza?");
        if (ques12.equals("MPV") || ques12.equals("mpv") || ques12.equals("mini mpv") || ques12.equals("compact mpv")) {
            respond = "God kill! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Falla! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques13 = JOptionPane.showInputDialog("13. What is the main color of 'Adobe Photoshop'?");
        if (ques13.equals("Blue") || ques13.equals("blue") || ques13.equals("light blue")) {
            respond = "Wow! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Falla! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques14 = JOptionPane.showInputDialog("14. what NBA stands for?");
        if (ques14.equals("National Basketball Association") || ques14.equals("national basketball association") || ques14.equals("National basketball association")) {
            respond = "Wow! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "Falla! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        String ques15 = JOptionPane.showInputDialog("15. What number does basketball player Kobe Bryant wear?");
        if (ques15.equals("8") || ques15.equals("24")) {
            respond = "Hellas! (^-^) ";
            correctChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        else {
            respond = "try more! (-.-') ";
            incorrectChoice += 1;
            JOptionPane.showMessageDialog(null, respond);
        }
        
        
        
        int select = JOptionPane.showConfirmDialog(null,"16. Become a good person, can't you?");
        if (select == JOptionPane.YES_OPTION) {
            correctChoice += 1;
        }
        else {
            incorrectChoice += 1;
        }
        
        
        JOptionPane.showMessageDialog(null, "Felicidades! " + stringA + " got " + correctChoice + " correct questions, your prize is " + correctChoice*2559 + " VND!");   
    }
}
