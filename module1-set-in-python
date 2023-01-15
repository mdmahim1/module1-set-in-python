#CPSMA-3913-01
#mdmahim
#271219


A = {1, 2, 3, 4, 5}
B = {2, 3, 4, 5, 6}
C = {3, 4, 5, 6, 7}
U = {1, 2, 3, 4, 5, 6,7}
S1 =A.union(B)
S2 = A.union(C)
S3 =B.union(C)
S4= A. intersection(B)
S5= A.intersection(C)
S6=B.intersection(C)
S7=U.difference(A)
S8=U.difference(B)
S9=U.difference(C)
print(S1)
print(S2)
print(S3)
print(S4)
print(S5)
print(S6)
print(S7)
print(S8)
print(S9)
#Any set is considered to be a subset of itself
def powerset(a):
# returns a List of all subsets of the List a
  if (len(a) == 0):
    return[[]]
  else:
      allSubsets = []
for subset in powerset(a[1:]):
  allSubsets += [subset]
  allSubsets += [[a[0]] + subset] 
 return allSubsets
print (powerset([1, 2, 3, 4, 5]))
#Powerset of U would have a 128 elements in it
