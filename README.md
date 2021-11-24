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
  for s:= 1 to m do 
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
  
}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}  
  program magmaA94;
  
 procedure nnn( var min,max,sred :integer);
 
 var z,x,c :integer;
 
 begin
 
if max < min then begin

  z:= min;
  
  min := max;
  
  max :=z ;
  
   end;
   
  if max< sred then begin
  
  x := sred;
  
  sred := max;
  
  max := x;
  
   end;
   
  if sred< min then begin
  c := min; 
 min := sred;
  sred:= c;
   end;
 
   writeln( min);
   writeln( sred);
   writeln( max);     
   end;
         
var z,x,c :integer;

begin

read(z);

read(x);

read(c);

nnn(z,x,c)

end.
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{

}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}  
program abcB94;

 procedure del(var a,b :integer);
 
 var sigma,x,omega,n1,n2, nod :integer;
 
 begin
 
   sigma:=a;
   
   omega:=b;
   
   if sigma < omega then 
   begin
   x:=omega;
   omega:=sigma;
   sigma:=x;
   end;
   
 while omega <>0 do
 
   begin
   
   sigma := sigma mod omega;
   
   x:=omega;
   omega:=sigma;
   sigma:=x;
   
   end;
   
  nod := sigma;
  
  writeln (a div nod);
  writeln('----');
  writeln (b div nod);
  
   end;
   
var z,b :integer;

begin

read(z,b);

del (z,b);

end.
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{   
 
 
}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}  
 program abcC94;
 
procedure del(var a,b :integer);

var sigma, x, omega, n1, n2, nod, nok :integer;

begin

 sigma:=a;
 
 omega:=b;
 
 if sigma < omega then
 
  begin 
  
   x:=omega; 
   
   omega:=sigma;
   
   sigma:=x;
   
  end;
  
 while omega <>0 do
 
  begin
  
   sigma := sigma mod omega;
   
 if sigma < omega then
 
  begin 
  
   x:=omega; 
   
   omega:=sigma;
   
   sigma:=x;
   
  end;
  
  end;

 nod := sigma;
 
 writeln (nod);
 
 nok:= (a*b) div nod;
 
 writeln (nok);
 
end;

var z, b :integer;

begin

read(z,b);

del (z,b);

end. 
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{   
 
}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}  
program abcA100;

function del(var a,b :integer): integer;

var sigma,x,omega,n1,n2, nod :integer;

begin

sigma:=a;

omega:=b;

if sigma < omega then begin x:=omega; omega:=sigma; sigma:=x; end;

while omega <>0 do

begin

sigma := sigma mod omega;

x:=omega; omega:=sigma; sigma:=x;

end;
del:=  sigma;

end;

var z,b :integer;

begin

read(z,b);

writeln ('НОD(',z,',', b,')',' = ',del(z,b));

end. 
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{   

}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}  
program abcB100;

function summa(var a :integer) : integer;

var q,w,e :integer;

begin

 q:=0;
 
 w:=0;
 
 while a<>0 do 
 
  begin
  
   q := a mod 10;
   
   w := w + q;
   
   a := a div 10;
   
  end;
  
 summa := w;
 
end;

var z :integer;

begin

read(z);

writeln (summa(z));

end. 
{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{   

]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]
program abcC100;

function reverse(var a :integer) : integer;

var q,w,e :integer;

begin

q:=0;

w:=0;

while a<>0 do 

begin

q := a mod 10;

w := w*10 + q;

a := a div 10;

end;
 
 reverse := w;

end;

var z :integer;

begin

read(z);

writeln (reverse(z));

end. 
[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[

]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]
program abcA105;

function ideal(var a :integer) :boolean;

var q,w,e :integer;

begin

 q:=0;
 
 w:=1;
 
for e:= 0 to a do begin
  
  if a mod w = 0 then 
  
  if w < a then
  
    q:=q + w;
    
    w:= w + 1;
    
    end;
    
 if q = a then
 
     ideal:= True
     
else ideal:= False;

end;

var z :integer;

begin

read(z);

writeln (ideal(z));

end.
[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[


]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]
program abcB105;
 function prostiesli(var a,b :integer): boolean;

var sigma,x,omega,n1,n2, nod :integer;

begin

sigma:=a;

omega:=b;

if sigma < omega then

 begin x:=omega;
 
 omega:=sigma; 
 
 sigma:=x; 
 
 end;

while omega <>0 do

begin

sigma := sigma mod omega;

x:=omega;

 omega:=sigma; 
 
 sigma:=x;

end;

if sigma = 1 then 
 
 prostiesli := true
 
 else prostiesli :=false;

end;

var z,b :integer;

begin

read(z,b);

writeln('числа ',z,',',b,' простые: ',prostiesli(z,b));

end. 
[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[
