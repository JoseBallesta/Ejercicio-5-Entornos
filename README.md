# Ejercicio-5-Entornos
#
static Scanner sc=new Scanner(System.in);   
    
    public static void main(String[] args) {
       
        for (int num=2; num<=100; num++) {
       
            boolean encontrado=false;
           
            for (int x=2; x<(num/2); x++) {
               
                if (num%x==0) {
                    encontrado=true;
                }
               
            }
           
            if (!encontrado) {
                System.out.print(num+", ");
            }
        }
       
    }
