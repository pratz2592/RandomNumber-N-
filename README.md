# RandomNumber-N-

public class RandomNumberGenerator {
 
    public static void main(String args[])
    {
        int N = 9;
 
        //Generates a random number
        double randomNumber = Math.random();
        int randomInt = (int)(N * randomNumber);
 
        System.out.println(randomInt);
 
    }
}

Output
4
