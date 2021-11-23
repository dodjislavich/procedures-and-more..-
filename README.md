# procedures-and-more..-

}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}
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
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{


}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}
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
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{



}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}
program solohardC90;
 
 procedure how(var n :integer);
 var m,d,c,l,x,v,i,s :integer;
 begin
 if n div 1000 > 0 then begin
 m := n div 1000;
 n:= n mod 1000;
 end;
 
    if (n div 500 > 0)  then begin
d := n div 500;  
n:= n mod 500;
end;

  if (n div 100 > 0) then begin
c := n div 100;  
n:= n mod 100;
end;


      if ( n div 50 > 0)then begin
l := n div 50;  
n:= n mod 50;
end;

      if ( n div 10 > 0) then begin
x := n div 10;  
n:= n mod 10;
end;
      
      if  ( n div 5> 0)then begin
v := n div 50;  
n:= n mod 5;
end;

         if ( n div 1 >0) then i:= n div 1;
if m>0 then
  for s:= 0 to m do 
  begin
  write('M');
  end;
  
 if d>0 then 
  for s:= 1 to d do 
  begin
  write('D');
  end;
  
   if c>0 then 
  for s:= 1 to c do 
  begin
  write('C');
  end;
  
  if l>0 then
  for s:= 1 to l do 
  begin
  write('L');
  end;
  
  if x>0 then
  for s:= 1 to x do 
  begin
  write('X');
  end;
  
  if x>0 then
  for s:= 1 to v do 
  begin
  write('V');
  end;

  
   if i>0 then 
  for s:= 1 to i do 
  begin
  write('I');
  end;
  end;
  
 var z,x,c :integer;
 begin
 read (z);
 how(z);
 end.
 {{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{
  
