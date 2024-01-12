class multiply
{
    private int a;
    private int b;
    void add()
    {
        System.out.println("a+b");
    }
}
class Division extends multiply
{
    private int a;
    private int b;
    void sub()
    {
        System.out.println("a-b");
    }
}
class Main
{
    public static void main(String args[])
    {
        Division scan=new Division();
        scan.add();
        scan.sub();
    }
}
