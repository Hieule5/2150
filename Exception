public class QuotientException{
    public static void main(String [] args)
    {
        java.util.Scanner input = new java.util.Scanner(System.in);
        int num;
        int den;
        int result  = 0;
        String response = "";

        do{

            try{

                System.out.print("Enter a nominator integer: ");
                num = input.nextInt();

                System.out.print("Enter a denominator integer: ");
                den = input.nextInt();

                result = num / den;
                System.out.println(num + "/ " + den + " = " + result);

            }catch(ArithmeticException ae)
            {
                System.out.println("You must enter 0 for denominator!!!");
            }
           System.out.println("Do you want to try it again? Type Yes or N0: ");
            response = input.next(); 

        }while(response.toLowerCase().startsWith("y"));

        System.out.println("Good bye");


    }

}
