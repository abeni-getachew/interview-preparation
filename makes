class Solution:
    def appendCharacters(self, s: str, t: str) -> int:
        res = 0
        for r in  s:
            if r == t[res]:
                res+=1
                if res == len(t):
                    return 0
            
        return len(t) -res  
