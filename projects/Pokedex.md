---
layout: project
type: project
image: https://user-images.githubusercontent.com/89556168/216536157-0f427213-2723-4c0b-a184-b66e7e63e596.jpeg
title: "Pokedex"
date: 2021

published: true
labels:
  - Java
  - GitHub
summary: "A pokedex of Pokemon created in ICS 211."
---

<img class="img-fluid" src="../img/Pokedex image.jpeg">

In this project it is using class in class by calling function to implement the class objects. This project have at least four file to make a pokedex that makes function to put out the Pokemon datas but the data of Pokemon status and type have to be create file and implement in the class. It could add more Pokemon by creating the class of Pokemon status and type of Pokemon, also it could be possible to make Pokedex that stores the every Pokemon by implementing the all Pokemon class.

The below are part of pokedex function that takes user input by switch statement that output the add, remove and prints Pokemon in pokedex by array by using function calls.

<hr>

<pre>

import java.util.Scanner;

 /**.
 * Class for Pokedex driver
 * @author Kairi Tanaka
 * @since 11/25/21
 */

 public class Pokedex {

    /**.
    * Pokedex Ask Pokemons to add and remove from tree
    * @param commandlineArguments are not used
    */

    public static void main(String[] commandlineArguments) {

       //variable sets
       Pokemon pTemp;
       PokeTree<Pokemon> tree = new PokeTree<>();
       Scanner userIn = new Scanner(System.in);
       String inString = "";
       boolean end = false;

       //while user not input 0 keep asking
       while (!end) {
          System.out.println("Please enter number");
          System.out.println("1: Add Pokemon\n" + "2: Release a Pokemon\n"
             + "3: Print Pokedex\n" + "0: End Pokedex");
          inString = userIn.nextLine();
          inString = inString.trim();

          switch(inString) {
             case "0": 
                end = true;
                System.out.println("Goodbye");
                break;

             case "1":
                pTemp = Pokedex.addPokemon();
                tree.add(pTemp);

                break;

             case "2":
                pTemp = Pokedex.addPokemon();
                tree.remove(pTemp);
                break;

             case "3":
                System.out.println(tree.printPokeTree());
                break;

             default:
                System.out.println("Invalid input");
                break;
          }
       }
    }

</pre>

<hr>

Source: <a href="https://github.com/km584/km584.github.io/blob/main/Pokedex.java"><i class="large github icon "></i>kairi/ics211-Pokedex</a>
