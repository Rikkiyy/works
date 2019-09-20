# works

this is my first java homework

public class Main {

    public static void main(String[] args) {
        System.out.print("  |");
        for(int i=1;i<13;i++){
            System.out.printf("%5d",i);
        }
        System.out.printf("\n--+");
        for(int i=1;i<13;i++){
            System.out.print("-----");
        }
        for(int i=1;i<13;i++){
            System.out.printf("\n%2d|",i);
            for(int j=1;j<13;j++){
                if(j<i){
                    System.out.printf("     ");
                }else{
                    System.out.printf("%5d",i*j);
                }
            }
        }
    }
}
