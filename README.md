# D_FLIPFLOP
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)

# Code
```
module dff(d,clk,rst,Q);
input d,clk,rst;
output reg Q;
always @(posedge clk)
begin
if(rst==1)
Q=1'b0;
else
Q=d;
end
endmodule

```

# Output
![319898872-e47a8ee0-c478-45f5-9250-5ba1b37ad7cb](https://github.com/Vijayananthperumal22/D_FLIPFLOP/assets/107705127/a0507640-17e0-48b8-bcf4-961ffd89fc21)
