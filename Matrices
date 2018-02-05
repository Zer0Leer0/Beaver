# Beaver
X= [5,8,9]
Y= [4,5,2] 
dotproduct = sum(i*j for i,j in zip(X,Y))
print('Dot product is : ' , dotproduct)
Dot product is : 78

X = [-3, -2, 5]
Y = [6, -10, -1]
Z = [X[1]*Y[2]  - X[2]*Y[1], X[0]*Y[2] - X[2]*Y[0], X[0]*Y[1] - X[1]*Y[0]]
print(Z)
[52, 27, 42]

def matrixmult (A, B):
  C = [[0 for row in range(len(A))] for col in range(len(B[0]))]
  for i in range(len(A)):
  for j in range(len(B[0])):
  for k in range(len(B)):
  C[i][j] += A[i][k]*B[k][j]
  return C
  
  A = [1,4,3] , [3,2,3] , [4,2,5]
  B = [5,0,3] , [3,9,3] , [6,5,2]
  matrixmult(A, B)
  [[35, 51, 21], [39, 33, 21], [56, 43, 28)]
