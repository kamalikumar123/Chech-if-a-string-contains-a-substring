# Chech-if-a-string-contains-a-substring
public class Main {
  public static void main(String[] args) {
   
    String txt = "This is Programiz";
    String str1 = "Programiz";
    String str2 = "Programming";

    
    boolean result = txt.contains(str1);
    if(result) {
      System.out.println(str1 + " is present in the string.");
    }
    else {
      System.out.println(str1 + " is not present in the string.");
    }

    result = txt.contains(str2);
    if(result) {
      System.out.println(str2 + " is present in the string.");
    }
    else {
      System.out.println(str2 + " is not present in the string.");
    }
  }
}
