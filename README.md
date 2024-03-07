t=int(input())
for i in range(t):
  a,b=input().split()
  b=int(b)
  r=""
  for j in a:
    x=ord(j)+b   
    if x>=123:
      x=96+(x-122)
      r=r+chr(x)
    else:
      r=r+chr(x)
  print(r)
