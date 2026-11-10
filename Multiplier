module multiplier (a, b, c);

input [3:0] a, b;
output [7:0] c;

wire P1, P2, P3, P4;

assign P1 = {a[3]&b[0], a[2]&b[0], a[1]&b[0], a[0]&b[0], 4'b0};

assign P2 = {1'b0, a[3]&b[1], a[2]&b[1], a[1]&b[1], a[0]&b[1], 3'b0};

assign P3 = {2'b0, a[3]&b[2], a[2]&b[2], a[1]&b[2], a[0]&b[2], 2'b0};

assign P4 = {3'b0, a[3]&b[3], a[2]&b[3], a[1]&b[3], a[0]&b[3], 1'b0};

assign c = P1 + P2 + P3 + P4;

endmodule
