/**
 * 冒泡排序 相邻的两个数依次进行比较和调整，让较大的数往下沉，较小的往上冒
 * @author Administrator
 *
 */
public class BubbleSort {
  public void bubbleSort(int[] a){
    int size = a.length;
    for (int i = size-1; i > 0; i--) {
      for (int j = 0; j < i; j++) {
        if (a[i] < a[j]) {
          this.swap(a, i, j);
        }
      }
    }
  }
  
  protected void swap(int[] a, int i, int j){
    int temp = a[i];   
    a[i] = a[j];   
    a[j] = temp;
  }
}
