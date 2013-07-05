It is almost spring in some places, and believe it or not, several Unicorns have already been spotted by our Magical Creature Department. I started thinking that with all these freaking Unicorns around, wouldn’t it be nice to make contact? So I thought up a puzzle: Can we pat them only once? Let’s start with the following piece of code:

public class MagicalLand {
  public static void main(String[] args) {
    for (int i = 0; i < (Math.random() * 500) + 2; i++) {
      if (Unicorn.pat()) {
        System.out.println("UNICORN #1: PAT THIS UNICORN ONCE");
      }
    }
 
    for (int i = 0; i < (Math.random() * 500) + 2; i++) {
      if (Unicorn.pat()) {
        System.out.println("UNICORN #2: PAT THIS UNICORN ONCE");
      }
    }
    System.out.println("END OF PROGRAM");
  }
}
There are two Unicorns hidden in this puzzle, but the magic surrounding the area makes it difficult to tell them apart. Your goal is to pat both Unicorns only once and then leave the magical land. Let me give you an example run.

# example run
javac MagicalLand.java
java MagicalLand
UNICORN #1: PAT THIS UNICORN ONCE
UNICORN #2: PAT THIS UNICORN ONCE
END OF PROGRAM
There are two rules. The first rule is that the body of the MagicalLand is not to be tampered with! The second rule is that you are not allowed to deflect the program flow and just print out the expected output directly. After all, these Unicorns produce top-quality meat, and we think that they’ve earned a pat!