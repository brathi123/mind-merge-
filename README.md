class merg {
    public static int add(){
        int a=30;
        int b=40;
        int c=a+b;
        System.out.println(c);
        return c;
        
    }
    public static String con(){
        String a= "ravi";
        String b="kumar";
        String c=a.concat(" ").concat(b);
        System.out.print(c);
        return c;
    }
    
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        add();
        con();
    }
}
