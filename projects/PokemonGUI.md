---
layout: project
type: project
image: img/vacay/vacay-square.png
title: "Pokemon GUI of Hunt and Pokedex"
date: 2021
published: true
labels:
  - Java
  - GitHub
summary: "This program is group project and this developed in ICS 211."
---

<img class="img-fluid" src="../img/vacay/vacay-home-page.png">

This program is create the GUI of Pokemon that user could play to hunt Pokemon and catch. And can store Pokemon data in Pokedex and in backpack button it will display all Pokemon that were catch even Pokemon is duplicate, for Pokedex will only display the Pokemon once.

This program is implements Pokemon status and Pokedex function and the class of Pokemon panel that is requires to display and works the button and the text area in GUI. 

From this group work, I learned that how the GUI function is works like when user push the button what function will work and display the text of result of function. I feel this is important to know how the GUI could be made, it have to be made frame and function and these are connected.

This is the main method of GUI frame:

'''import javax.swing.JFrame;
/**
* Assignment 9: Pokemon GUI - the Frame.
* @author Kairi Tanaka & Jamie Laurin
* @since 12/03/2021
*/
public class PokemonFrame {
  /** main method.
   * @param args not used
   */
   public static void main(String[] args) {
      // basic JFrame setup
      JFrame frm = new JFrame("Pokemon Go");
      frm.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
   
      // contents here 
      frm.getContentPane().add(new PokemonPanel());
   
      // displays to screen
      frm.pack();
      frm.setVisible(true);
    
   }
}
'''

This is the main method of GUI frame and there is one more class that is connected to frame, this will be more important function class that program of how the result will display by user input. So the frame is outlook from outside and the panel will be a function structed inside of the frame that button or user input will gets the result output.

Source: <a href="https://github.com/km584/km584.github.io/blob/main/PokemonFrame.java">PokemonFrame</a>
Source: <a href="https://github.com/km584/km584.github.io/blob/main/PokemonPanel.java">PokemonFrame</a>
