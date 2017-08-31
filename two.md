import java.util.*;

public class test2 {


    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int count = Integer.valueOf(scanner.nextLine());
        TreeSet<String> set = new TreeSet<>();
        for(int i =0;i<count;i++){
            set.add(scanner.nextLine());
        }
        int temp = Integer.valueOf(scanner.nextLine());
        for(int i =0;i<temp;i++){
            set.remove(scanner.next());
        }
        for (String s : set) {
            System.out.println(s);
        }
    }
}
