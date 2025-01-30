            class digit_op:
                def num(self,num1):
                    self.num = num1
                
            class sum(digit_op):
                def calculate_pairs_sum(self):
                    digits = [int(digit) for digit in str(self.num)][::-1]
            
                    total_sum = 0
                    n = len(digits)
            
                    for i in range(n):
                        for j in range(i + 1, n):
                            total_sum += digits[i] + digits[j]
                    return total_sum
            
            num= 1234
            calculate= sum()
            calculate.num(num)
            
            print("Final sum:",calculate.calculate_pairs_sum())
