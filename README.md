# Array
//Q.1

// import java.util.*;
// class Main{
//   public static void main(String[] args){
// Scanner sc=new Scanner(System.in);
//     System.out.println("enter the number of elements");
//     int n=sc.nextInt();
//     int arr[]=new int[n];
//     int sum=0;
//     for(int i=0;i<n;i++){
//       System.out.println("enter element");
//       arr[i]=sc.nextInt();
      
//     }
//     for(int i=0;i<n;i++){
//       sum=sum+arr[i];
//     }
//     System.out.println("the average of the array is:"+sum/n);
//   }
// }



//Q.2

// import java.util.*;
// class Main{
//   public static void main(String[]args){
//     Scanner sc=new Scanner(System.in);
//     System.out.println("enter the number of elements");
//     int n=sc.nextInt();
//     int arr[]=new int[n];
//     int max=arr[0];
//     int min=arr[0];
//     for(int i=0;i<n;i++){
//       System.out.println("enter element");
//       arr[i]=sc.nextInt();
//     }
//     for(int i=0;i<n;i++){
//       if(arr[i]>max){
//         max=arr[i];
//       }
//     }
//     for(int j=0;j<n;j++){
//       if(arr[j]<min){
//         min=arr[j];
//       }
//     }
//     System.out.println("the max element is:"+max);
//     System.out.println("the min element is:"+min);
//   }

// }




//Q.3(second largest element)

// import java.util.*;
// class Main{
//   public static void main(String[]args){
//     Scanner sc=new Scanner(System.in);
//     System.out.println("enter the number of elements");
//     int n=sc.nextInt();
//     int arr[]=new int[n];
//     int max1=0;
//     int max2=0;
//     for(int i=0;i<n;i++){
//       System.out.println("enter element");
//       arr[i]=sc.nextInt();
//     }
//     for(int i=0;i<n;i++){
//       if(arr[i]>max1){
//         max1=arr[i];
//       }
//     }
//     for(int j=0;j<n;j++){
//       if(arr[j]>max2 && arr[j]<max1){
//         max2=arr[j];
//       }
//     }
//     System.out.println("the second largest element is:"+max2);
//   }
// }




//Q.4(find the index)

// import java.util.*;
// class Main{
//   public static void main(String[]args){
//     Scanner sc=new Scanner(System.in);
//     System.out.println("enter the number of elements");
//     int n=sc.nextInt();
//     int arr[]=new int[n];
//     System.out.println("enter the element you want to search");
//     int x=sc.nextInt();
//     for(int i=0;i<n;i++){
//       System.out.println("enter element");
//       arr[i]=sc.nextInt();
//     }
//     for(int i=0;i<n;i++){
//       if(arr[i]==x){
//         System.out.println("the element is present at index:"+i);
//       }
//     }
//   }
// }



//Q.5

// import java.util.*;
// class Main{
//   public static void main(String[]args){
//     Scanner sc=new Scanner(System.in);
//     System.out.println("enter the number of elements");
//     int n=sc.nextInt();
//     int arr[]=new int[n];
//     int even=0;
//     int odd=0;
//     for(int i=0;i<n;i++){
//       System.out.println("enter element");
//       arr[i]=sc.nextInt();
//     }
//     for(int i=0;i<n;i++){
//       if(arr[i]%2==0){
//         even++;
//       }
//       else{
//         odd++;
//       }
//     }
//     System.out.println("the number of even elements are:"+even);
//     System.out.println("the number of odd elements are:"+odd);

//       }
// }

