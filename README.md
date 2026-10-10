# Week-4

class Week4 {
    public static void main(String[] args) {
        double price = 1999.0;
        double discount = 10.0;

        double discountAmount = price * discount / 100;
        double finalPrice = price - discountAmount;

        System.out.println("Original Price: Rs." + price);
        System.out.println("Discount: " + discount + "%");
        System.out.println("Discount Amount: Rs." + discountAmount);
        System.out.println("Final Price: Rs." + finalPrice);
    }
}
