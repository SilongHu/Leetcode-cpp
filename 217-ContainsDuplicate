class Solution {
public:
    bool containsDuplicate(vector<int>& nums) {
        if(nums.size()<2) return false;
        sort(nums.begin(),nums.end());
        int i = 0;
        while(i<nums.size()){
            if (nums[i++] == nums[i]) return true;
        }
        return false;
    }
};
