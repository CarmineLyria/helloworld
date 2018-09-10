# helloworld
Hello World Practice
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package helloworld;

/**
 *
 * @author lizadair
 */
public class Helloworld {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        final int AGE_NEEDED = 25;
        //declaring a variable of type String
        String output;
        //assigning a value to variable output
        output = "You are allowed to code.";
        int ageOfProgrammer = 25;
        //declare int variable
        
        //flow of control for if
        if (ageOfProgrammer >= AGE_NEEDED){
            System.out.println("Hello there." + output + "Don't let it go to your head.");
            
        } else {
            System.out.println("Sorry, you're too new.");
        } //close if/else
        
        //declare and intialiase numloops
        
        int numLoops = 10;
        
        // declare and initialise counter
        
        int counter = 0;
        
        //practice looping
        while(counter < numLoops){
            counter = counter+1;
            System.out.println("loop");
        } //end while
        
    } //close main
} // close class
