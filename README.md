import java.util.HashSet; 

public class HashSetExample {
    public static void main(String[] args) {
        // Create a HashSet of integers
        HashSet<Integer> myHashSet = new HashSet<>();

        // Add elements to the HashSet
        myHashSet.add(5);
        myHashSet.add(10);
        myHashSet.add(15);

        // Check if an element is in the HashSet
        boolean containsElement = myHashSet.contains(10);
        System.out.println("HashSet contains 10: " + containsElement);

        // Remove an element from the HashSet
        myHashSet.remove(10);

        // Iterate through the HashSet
        for (Integer element : myHashSet) {
            System.out.println("Element: " + element);
        }
    }
}
