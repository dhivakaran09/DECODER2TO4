# DECODER2TO4
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)
# Program
```
module decoder_8(a,b,c,y);
input a,b,c;
output [7:0]y;
and gl (y[0], (~a), (~b), (~c));
and g2 (y[1], (~a), (~b), (c));
and g3 (y[2], (~a), (b), (~c));
and g4 (y[3], (~a), (b), (c));
and g5(y[4], (a), (~b), (~c));
and g6(y[5], (a), (~b), (c));
and g7(y[6], (a), (b), (~c));
and g8 (y[7], (a), (b), (c));
endmodule
```
# OUTPUT
![WhatsApp Image 2024-03-25 at 13 50 35_5271a9b8](https://github.com/dhivakaran09/DECODER2TO4/assets/164842673/f89cfa70-5732-4c06-8a4d-b1557f99a6c4)
