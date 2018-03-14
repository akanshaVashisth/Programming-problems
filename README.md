# Programming-problems
# Functions in Python
def withinEpsilon(x, y, epsilon):
	"""x, y, epsilon floats.  epsilon > 0.0
		returns True if x is within epsilon of y"""
	return abs(x - y) <= epsilon

print withinEpsilon(2, 3, 1)

def f(x):
	x = 'john'
	x = x+1
	print 'x =' , x
	return x

x = 3
z = f(x)
print 'z =' , z
print 'x =' , x
