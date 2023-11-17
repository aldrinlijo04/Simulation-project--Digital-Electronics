```
NAME:ALDRIN LIJO J E
REG NO: 212222240007
```
# TITTLE
Minimise the function using K map F(A,B,C)=A′B'+BC′+BC+A'B′C′ and simulate the logic diagram using verilog

# THEORY 
![image](https://github.com/JoyceBeulah/Simulation-project--Digital-Electronics/assets/118343698/b526aa32-49be-4107-aed4-4bc7426d2241)


# LOGIC DIAGRAM 
![image](https://github.com/JoyceBeulah/Simulation-project--Digital-Electronics/assets/118343698/967a6452-f6bf-49b3-abd0-2b2d5a8960aa)


# NETLIST DIAGRAM
![image](https://github.com/JoyceBeulah/Simulation-project--Digital-Electronics/assets/118343698/3671b818-5045-44cf-befa-955491502e15)


# TIMING DIAGRAM
![image](https://github.com/JoyceBeulah/Simulation-project--Digital-Electronics/assets/118343698/fd6dfcb6-3006-4c67-a42a-b52710b1694f)


# PROGRAM

```
module lab(a,b,y);
input a,b;
output y;
wire x;
Not (x,a);
or(y,x,b);
endmodule
```

# RESULT:
Thus the given equation is minimised using k map and simulated the logic diagram using verilog.
