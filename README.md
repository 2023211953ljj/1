class Solution {
    public int[] twoSum(int[] nums, int target) {
       
       for(i=0;i<num.length;i++)
       {
       for(j=i+1;j<num.length;j++){
           if(num[i]+num[j]=target){
            result[0]=i;
            return[1]=j;

           }

           return result;
       }
       }
    }
    return result;
}



///
class Solution {
    public boolean isPalindrome(int x) {
     
        if (x < 0 || x % 10 == 0 &) {
            return false;
        }
        
        int cur = 0;
        while (x >cur) {
            cur = cur * 10 + x % 10;
            x /= 10;
        }

        return x == cur || x == cur / 10;
    }
}
