# CODSOFT- to-do-list
import sys
import datetime

def help():



# function to add item in todo list
def add(s):

    f = open('todo.txt', 'a')
    f.write(s)
    f.write("\n")
    f.close()
    s = '"'+s+'"'
    print(f"Added todo: {s}")

# Function to print the todo list items
def ls():

	try:

		nec()
		l = len(d)
		k = l

		for i in d:
			sys.stdout.buffer.write(f"[{l}] {d[l]}".encode('utf8'))
			sys.stdout.buffer.write("\n".encode('utf8'))
			l = l-1

	except Exception as e:
		raise e
