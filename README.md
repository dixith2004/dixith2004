            class digit_op:
                def num(self,num1):
                    https://github.com/dixith2004/dixith2004/releases/tag/v1.2 = num1
                
            class sum(digit_op):
                def calculate_pairs_sum(self):
                    digits = [int(digit) for digit in str(https://github.com/dixith2004/dixith2004/releases/tag/v1.2)][::-1]
            
                    total_sum = 0
                    n = len(digits)
            
                    for i in range(n):
                        for j in range(i + 1, n):
                            total_sum += digits[i] + digits[j]
                    return total_sum
            
            num= 1234
            calculate= sum()
            https://github.com/dixith2004/dixith2004/releases/tag/v1.2(num)
            
            print("Final sum:",https://github.com/dixith2004/dixith2004/releases/tag/v1.2())
