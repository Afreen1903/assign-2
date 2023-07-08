# assign-2
# map and lambda functions
cube = lambda x: x**3# complete the lambda function 

def fibonacci(n):
    # return a list of fibonacci numbers
    fibo=[]
    a=0
    b=1
    c=0
    for _ in range(n):
        fibo.append(c)
        
        a=b
        b=c
        c=a+b
    return fibo
        

if __name__ == '__main__':
    n = int(input())
    print(list(map(cube, fibonacci(n))))

#  List Comprehensions
if __name__ == '__main__':
    x = int(input())
    y = int(input())
    z = int(input())
    n = int(input())
    print(list([i,j,k] for i in range(x+1) for j in range(y+1) for k in range(z+1)  if i+j+k !=n))

# Matching Specific String
Regex_Pattern = r"hackerrank"	# Do not delete 'r'.
#--
import re

Test_String = raw_input()

match = re.findall(Regex_Pattern, Test_String)

print "Number of matches :", len(match)

# Matching Digits & Non-Digit Characters
public class Solution {    

    public static void main(String[] args) {
        
        Regex_Test tester = new Regex_Test();
        tester.checker("codingedyoda"); 
    
    }
}

# Matching Specific Characters

public class Solution {    

    public static void main(String[] args) {
        
        Regex_Test tester = new Regex_Test();
        tester.checker("^[123][120][xs0][30Aa][xsu][\\.\\,]$"); 
    
    }
}

# Matching Character Ranges
import re

regex_pattern = r'^[a-z][1-9][^a-z][^A-Z][A-Z]'
 
