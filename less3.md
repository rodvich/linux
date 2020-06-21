ubuntu@ip-172-31-17-236:~/lesson3$ vim hello.txt 
ubuntu@ip-172-31-17-236:~/lesson3$ mv hello.txt hello.py
ubuntu@ip-172-31-17-236:~/lesson3$ cat hello.py 
print('Hello, World!')
ubuntu@ip-172-31-17-236:~/lesson3$ cat hello.py | wc -l
2
ubuntu@ip-172-31-17-236:~/lesson3$ echo 'print("Linear regression")' > file.py
ubuntu@ip-172-31-17-236:~/lesson3$ cat hello.py file.py
print('Hello, World!')

print("Linear regression")
ubuntu@ip-172-31-17-236:~/lesson3$ cat hello.py file.py > hello_file.py
ubuntu@ip-172-31-17-236:~/lesson3$ cat hello_file.py 
print('Hello, World!')

print("Linear regression")