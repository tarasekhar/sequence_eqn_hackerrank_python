# sequence_eqn_hackerrank_python
#python code, solution to the sequence problem in implementation
n=int(input())
p=list(map(int,input().split()))
y=[]
for x in range(1,len(p)+1):
    y.append(p.index(p.index(x)+1)+1)

for item in y:
    print(item)
