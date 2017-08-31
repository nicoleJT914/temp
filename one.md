import java.util.*;

public class test2 {


    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int count = scanner.nextInt();
        List<Integer> list = new ArrayList<>(count);
        for(int i =0;i<count;i++ ){
            list.add(scanner.nextInt());
        }
        int temp = -1;
        int result = 0;
        for(int i=0;i<count;i++){
            if(list.get(i)!=temp){
                temp = list.get(i);
                result++;
            }
        }
        System.out.println(result);
    }
}
