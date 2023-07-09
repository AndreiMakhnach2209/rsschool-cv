
# **Andrei Makhnach**
****

![foto](./images/foto.png)

## Contacts:
****
* tel: +375 29 851-52-40  
* Email: [ahdpyxa88@gmail.com](mailto:ahdpyxa88@mail.com)  
* Discord: [Andrei (@AndreiMakhnach2209)](https://discordapp.com/users/1120793615925510146/)  

****
## About me
I work as a service engineer. I strive to learn something new. RS School courses are suitable for this. Now my goal is to gain knowledge in the field of frontend development. 
My strengths are diligence, learning ability, discipline, striving for self-development.

****
## Skills:
* Autodesk Autocad
* Autodesk Fusion 360
* While studying at the university, I studied Pascal

****
## Codewars test

pascal

```
unit BugFixMultiply;

interface

function Multiply(const A: Integer; const B: Integer): Integer;

implementation

function Multiply(const A: Integer; const B: Integer): Integer;
begin
  Result := A + B;
end;

end.


unit BugFixMultiplyTests;

interface

uses
  TestFramework,
  BugFixMultiply;

type TMultiplyTests = class(TTestCase)
  published
    procedure Examples;
end;

procedure RegisterTests;

implementation

procedure RegisterTests;
begin
  TestFramework.RegisterTest(TMultiplyTests.Suite);
end;

procedure TMultiplyTests.Examples;
begin
  CheckEquals(2, Multiply(1, 1));
  CheckEquals(3, Multiply(2, 1));
  CheckEquals(4, Multiply(2, 2));
  CheckEquals(8, Multiply(3, 5)); 
end;
end. 

```

JavaScript

```
function multiply(a, b){
 return a * b
}


const assert = require("chai").assert;

describe("Multiply", () => {
  it("fixed tests", () => {
    assert.strictEqual(multiply(1,1), 1);
    assert.strictEqual(multiply(2,1), 2);
    assert.strictEqual(multiply(2,2), 4);
    assert.strictEqual(multiply(3,5), 15);   
  });
});

```
*****

## My first project: [CV](https://andreimakhnach2209.github.io/rsschool-cv/cv)

****
## Education 

Belarusian National Technical University  
Mechanical engineer, specialty "Auto service"

****
## English
 - Beginner
 