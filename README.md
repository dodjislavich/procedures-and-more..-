# procedures-and-more..-


program bogdanA90;
procedure tired(var n :integer);
var k :integer;
begin
for k:= 0 to n do
begin
  write('-');
end;
end;

var z,x,c :integer;
begin
read(z);
tired(z);
end.


program CEEEEEEEEEEEEEEBB90;

procedure polka( var n :integer);
var a,k,s :integer;
begin
a:=0;
k:=0;
while n<>0 do
begin
a:= n mod 10;
n:= n div 10;
k:= k*10+a;
end;
while k<>0 do
begin
s:= k mod 10;
k:= k div 10;
writeln(s);
end;
end;


var z,x,c :integer;
begin
read (z);
polka(z);
end.

