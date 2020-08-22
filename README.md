class displacement1
{
    int dis,time,acc;
    double ans;
    void displacement(int u,int t,int a)
    {
        dis=u;
        time=t;
        acc=a;
    }
    void calc()
    {
        ans=(dis*time)+((acc*time*time)/2);
    }
    void display()
    {
        System.out.println("The ans is:" +ans);
    }
    public static void main()
    {
        displacement1 obj = new displacement1();
        obj.displacement(20,1200,10);
        obj.calc();
        obj.display();
    }
}
