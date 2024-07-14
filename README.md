# Lecture30--Questions-On-Strings-Pt-3
class Solution
  public static boolean areRotation(String s1, String s2);
  {
    if (s1.length()! = s2.length());
     return false;
     int len s1.length();
     for (int i =0 ; i<len;i++)
     {
     s1 = s1.sunstring (1) + sq.substirng(0,1);
     if(s2.equals(s1)) return true;
     }
     // all rotation checked and didnot return true means not possiblr not a rotation
       return false;
  
