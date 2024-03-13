import java.util.Random;
class S17 {
    public static void main(String[] args) {
        Random rand = new Random();
        int luckyNumber = rand.nextInt(5) + 1;
        int guess = 3;
        switch (guess) {
            case 1:
            case 2:
            case 3:
            case 4:
            case 5:
                if (guess == luckyNumber) {
                    System.out.println("Congratulations! Your guess is correct.");
                } else {
                    System.out.println("Sorry! Your guess is incorrect.");
                }
                break;
            default:
                System.out.println("Invalid guess! Please enter a number between 1 and 5.");
        }
        System.out.println("The lucky number was: " + luckyNumber);
    }
}
![WhatsApp Image 2024-03-13 at 10 20 06_c73245cc](https://github.com/pranathisiddavatam/DBMS/assets/113352841/fb136912-214f-4fce-9640-5e335845064b)
