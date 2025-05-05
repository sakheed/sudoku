Run 
python3 P2.py 

then once it says "Debugger is active!": 

The default puzzle is Puzzle 1, so once running on your local server, the "/" path, will give the 48 step solution for Puzzle 1:
http://127.0.0.1:5000/

Then, you can modify the URL to include any puzzle by adding it after the "/".
For example.
http://127.0.0.1:5000/?board=[[1,0,0,0],[0,0,0,0],[0,0,0,0],[0,0,0,4]]
This will convert the given board into the correct format, and solve.
