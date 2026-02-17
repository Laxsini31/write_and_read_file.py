f=open("sample.txt","w")
f.write("Hello World")
f.close()

f=open("sample.txt","r")
print(f.read())
f.close()
Output
Hello World
