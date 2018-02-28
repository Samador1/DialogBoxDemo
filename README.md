/* Using dialog boxes for input and output of Strings
with reusability in our code by 
    Amador, Sierra
*/

import javax.swing.JOptionPane;


public class DialogBoxDemo1
{
    public static void main ( String [] args )
    {
      String input = JOptionPane.showInputDialog ( null, 
              
                    "Please enter your first and last names" );
      JOptionPane.showMessageDialog ( null, "Hello, " + input ); 
      
/* This will allow you to access a diolag box where you can insert you names to be greeted */

      String name = JOptionPane.showInputDialog ( null, 
              
                    "Please enter your age in years" );
      JOptionPane.showMessageDialog ( null, "You are  " + 25 ); 

      /* This will allow you to access a diolag box where you can insert
      your age to allow the prgoram to know your age */
}
}
