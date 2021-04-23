# Find-n-th-term-of-series
Python programming

def term(n) :
	ans = 0
	for i in range(1,n+1) :
		ans = ans + i
	
	return ans
n = 5
print(term(n))

