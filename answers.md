1. CREATE [OR REPLACE] FUNCTION function_name [parameters]  
2. [(parameter_name [IN | OUT | IN OUT] type [, ...])]  
3. RETURN return_datatype  
4. {IS | AS}  
5. BEGIN  
6. < function_body >  
7. END [function_name];

create or replace function adder(n1 in number, n2 in number)  
return number  
is  
n3 number(8);  
begin  
n3 :=n1+n2;  
return n3;  
end;  
/


DECLARE  
n3 number(2);  
BEGIN  
n3 := adder(11,22);  
dbms_output.put_line('Addition is: ' || n3);  
END;

DECLARE  
a number;  
b number;  
c number;  
FUNCTION findMax(x IN number, y IN number)  
RETURN number  
IS  
z number;  
  
BEGIN  
IF x > y THEN  
z:= x;  
ELSE  
  
Z:= y;  
END IF;  
  
RETURN z;  
END;  
BEGIN  
a:= 23;  
b:= 45;  
  
c := findMax(a, b);  
dbms_output.put_line(' Maximum of (23,45): ' || c);  
END;

declare  
num number;  
factorial number;  
function fact(x number)  
return number  
is  
f number;  
begin  
if x=0 then  
f:=1;  
else  
f:=x*fact(x-1);  
end if;  
return f;  
end;  
begin  
num:=5;  
factorial:=fact(num);  
dbms_output.put_line('factorial value'|| num || 'is'||factorial);  
end;

ziyath@crescent.education

