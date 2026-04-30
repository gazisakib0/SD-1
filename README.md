# SD-1
# Report -2
# 1
public class ArrayStore {
    public static void main(String[] args) {
        int[] arr = {10, 20, 30, 40, 50};

        for(int i = 0; i < arr.length; i++) {
            System.out.println(arr[i]);
        }
    }
}

# 2
public class LargestNumber {
    public static void main(String[] args) {
        int[] arr = {12, 45, 7, 89, 23};

        int max = arr[0];

        for(int i = 1; i < arr.length; i++) {
            if(arr[i] > max) {
                max = arr[i];
            }
        }

        System.out.println("Largest: " + max);
    }
}
# 3
public class SmallestNumber {
    public static void main(String[] args) {
        int[] arr = {12, 45, 7, 89, 23};

        int min = arr[0];

        for(int i = 1; i < arr.length; i++) {
            if(arr[i] < min) {
                min = arr[i];
            }
        }

        System.out.println("Smallest: " + min);
    }
}
