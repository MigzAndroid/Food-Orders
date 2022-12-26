    import java.util.Scanner ;
import java.util.ArrayList;
public class JavaApplication10 {

   

    public static void main(String[] args) {
       ArrayList<String> orders = new ArrayList<String>();
       ArrayList<Double> prices = new ArrayList<Double>();
       
       Scanner sc = new Scanner (System.in);
       boolean finished = false;
       
       while(!finished) {
           System.out.println("Enter your food order(enter 'done when finished: ')");
           String order = sc.nextLine();
           if(order.equals("done")){
               finished = true;
           } else{
               orders.add(order);
               System.out.println("Enter the price: ");
               double price = sc.nextDouble();
                prices.add(price);
                sc.nextLine();
                
           }
       }
        double totalPrice = 0;
        for(double price : prices){
            
            totalPrice += price;
            
        }
        System.out.println("Your orders: " + orders);
        System.out.println("Total price: " + totalPrice);
    }
}

