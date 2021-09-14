class Main
{
    double balance;
    double withdraw(double amount)
    {
        balance = balance-amount;
        return balance;
    }
    public static void main(String[] args)
    {
        Main acc=new Main();
        acc.balance=6000;
        acc.withdraw(1000);
        if(acc.balance<5000)
                System.out.println("-1");
            else
            System.out.println(acc.balance);
    }
}
