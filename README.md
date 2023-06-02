# JavaPratik43_DizidekiTekrarEdenSayilariBulanProgram
Dizide Tekrar Eden çift Sayılar

    import java.util.Arrays;

    public class Main {
      public static void main(String[] args) {
        int[] list={2,2,5,9,7,4,4,20,20,64,64};
        int[] duplicate = new int[list.length];
        int index = 0;
        for (int i=0; i< list.length;i++){
            for (int j = 0;j< list.length;j++){
                if ((i != j) && (list[i] == list[j]) && list[i]%2==0){
                    duplicate[index++] = list[i];
                }

            }
        }
        System.out.println(Arrays.toString(duplicate));

    }
    
    }
