def collatzcheck(n,s):
	if n == 1:
		return True
	if n in s:
		return False
	if n % 2:
		return collatzcheck(3*n+1,s)
	else:
		return collatzcheck(n//2,s)


def seta(n):
	s = set()
	return collatzcheck(n, s)

n = 574566336395328945723498572895729857298579835792
if seta(n):
	print("Yes it belong to collatz conjecture")
else:
	print("No You Found something new")
