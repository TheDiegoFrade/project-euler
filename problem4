//A palindromic number reads the same both ways. The largest palindrome made 
//from the product of two 2-digit numbers is 9009 = 91 × 99.
//Find the largest palindrome made from the product of two 3-digit numbers.


list = []
num = 998001

while (num > 10000) {
    num = String(num);
    if (num[0] == num[5] && num[1] == num[4] && num[2] == num[3] ) {
        num = parseInt(num);
        num2 = 100
        num3 = num/num2
        while (num2 < 999) {
            if (String(num3).length == 3) {
                list.push(num);
                list.push(num2);
                list.push(num3);
                list.push("|");
            }
            num2 ++ ;
            num3 = num/num2; 
        }
    }    
    num = parseInt(num);
    num --;
  }


console.log("Largest Palindrome: " + list[0] +
            "\r\n" + "First 3 Digit Numer: " + list[1] +
            "\r\n" + "Second 3 Digit Numer: " + list[2])







