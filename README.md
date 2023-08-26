# pr15
import java.util.ArrayList;
import java.util.Collections;

public class SortList {
  public static void main(String[] args) {
    ArrayList<String> list = new ArrayList<>();
    list.add("Java");
    list.add("Python");
    list.add("C++");
    System.out.println(list);
    Collections.sort(list);
    System.out.println(list);
  }
}
