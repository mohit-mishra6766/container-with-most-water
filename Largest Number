class Solution {
    public String largestNumber(int[] nums) {
        String[] str = new String[nums.length];
        for(int i=0;i<nums.length;i++){
            str[i] = String.valueOf(nums[i]);
        }
        Arrays.sort( str, (s1, s2) -> (s2+s1).compareTo(s1+s2) );
        if(str[0].charAt(0)=='0'){
            return "0";
        }
        StringBuilder ans = new StringBuilder();
        for(String s:str){
            ans.append(s);
        }
        return ans.toString();
    }
}
