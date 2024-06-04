







public class Rectaangle {
 public static void main(String[] args) {
            int row=7;
            int col=14;
            int i=0;
            while(i<row) {
                int j=0;
                while(j<col) {
                    if( i==0 || j==0 || i== row-1 || j==col-1) {
                        System.out.print("*");
                    }
                    else {
                        System.out.print(" ");
                    }
                    j++;
                }System.out.println();
                i++;
            }
        }


}
public class pyramid {
    public static void main(String[] args) {

		int n=5;
		for(int row=1; row<=n ; row++) {
			for (int spa =1 ; spa<=n-row;spa++) {
				System.out.print(" ");
			}for(int sta=1; sta<=row ; sta++) {
				System.out.print("*");
			}System.out.println();
		}

	}

}
public class RTriangle {
    public static void main(String[] args) {
       int n=5;
       int i=0;
       while(i<n){
        int j=n;
        while(j>i){
            System.out.print("*");
            j--;

        }System.out.println();
        i++;
       }

}}
public class palidrone {

    public static void main(String[] args) {
        int num=121;
        int rev=0;
        int num1=num;
        while(num>0){
            int dig=num%10;
            rev=rev*10+dig;
            num=num/10;
        }
        if(num1==rev){
            System.out.println("palidrone number");
        }
        else{
            System.out.println("not a palidrone number");
        }
    }


}
class InvertedRight {
    public static void main(String[] args) {
        int row=10;
        int i=0;
        while(i<row){
            int j=row;
            while(j>i){
                System.out.print("*");
                j--;
            }System.out.println();
            i++;
        }
    }
}
package project;

public class HollowDiamond {
    public static void main(String[] args) {
        int rows = 5;
        for (int i = 1; i <= rows; i++) {
            for (int j = rows; j > i; j--) {
                System.out.print(" ");
            }
            for (int k = 1; k <= (2 * i - 1); k++) {
                if (k == 1 || k == (2 * i - 1)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
        for (int i = rows - 1; i >= 1; i--) {
            for (int j = rows; j > i; j--) {
                System.out.print(" ");
            }
            for (int k = 1; k <= (2 * i - 1); k++) {
                if (k == 1 || k == (2 * i - 1)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
    }
}
package project;

public class HourGlassPattern {
    public static void main(String[] args) {
        int n = 4;
        // upper part
        for (int i = n; i >= 1; i--) {
            for (int j = n; j > i; j--) {
                System.out.print(" ");
            }
            for (int k = 1; k <= (2 * i - 1); k++) {
                System.out.print("*");
            }
            System.out.println();
        }
        // lower part
        for (int i = 2; i <= n; i++) {
            for (int j = n; j > i; j--) {
                System.out.print(" ");
            }
            for (int k = 1; k <= (2 * i - 1); k++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
package project;

public class Hpyramidp {

	
	 public static void main(String[] args) {
		int n=5;
		for(int i=1; i<=n; i++) {
			for(int j=n ; j>i; j--) {
				System.out.print(" ");
			}for(int k=1 ; k<=(2*i-1) ; k++) {
				if(k==1 || k == (2*i-1) || i== n) {
					System.out.print("*");
				}
				else {
					System.out.print(" ");
				}
			}System.out.println();
		}
	}
}

package project;

package project;

public class Xpattern {
    public static void main(String[] args) {
        int n = 5;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= n; j++) {
                if (j == i || j == (n - i + 1)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
    }
}

package project;

public class ButterflyPattern {
    public static void main(String[] args) {
        int n = 3;
        // upper part
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            for (int j = 1; j <= 2 * (n - i); j++) {
                System.out.print(" ");
            }
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
//lower
        for (int i = n; i >= 1; i--) {
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            for (int j = 1; j <= 2 * (n - i); j++) {
                System.out.print(" ");
            }
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}

package project;

public class RightArrow {
    public static void main(String[] args) {
        int n = 5;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j < i; j++) {
                System.out.print(" ");
            }
            for (int k = i; k <= n; k++) {
                System.out.print("* ");
            }
            System.out.println();
        }
        for (int i = n - 1; i >= 1; i--) {
            for (int j = 1; j < i; j++) {
                System.out.print(" ");
            }
            for (int k = i; k <= n; k++) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}





