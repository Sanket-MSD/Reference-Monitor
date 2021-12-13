# New File Operation

# Clean up of existing file
if "testfile.txt.a" in listfiles():
 removefile("testfile.txt.a")
if "testfile.txt.b" in listfiles():
 removefile("testfile.txt.b")

# Open File Function Call
myfile=ABopenfile("testfile.txt",True)  #Create an AB file

try:
 # Empty/New File should have contents 'SE' satisfying the requirement
 assert('SE' == myfile.readat(2,0))
 # Close the file:
 myfile.close()
except:
 myfile.close()
 # Error Handle or Failure Condition
 log("Empty file is not handled properly!")
