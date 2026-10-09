## Conversion from One Base to Another
1. **Convert the decimal number 156 to:**
   - Binary
   - Octal
   - Hexadecimal

2. **Convert the binary number 101101 to:**
   - Decimal
   - Octal
   - Hexadecimal

3. **Convert the octal number 745 to:**
   - Decimal
   - Binary
   - Hexadecimal

4. **Convert the hexadecimal number 3F9 to:**
   - Decimal
   - Binary
   - Octal

===============================================================
# Conversion from One Base to Another

## 1. Convert decimal number 15610156_{10}15610

### a) Decimal to Binary

Divide by 2 repeatedly and record the remainders.

| Division | Quotient | Remainder |
| -------- | -------- | --------- |
| 156 ÷ 2  | 78       | 0         |
| 78 ÷ 2   | 39       | 0         |
| 39 ÷ 2   | 19       | 1         |
| 19 ÷ 2   | 9        | 1         |
| 9 ÷ 2    | 4        | 1         |
| 4 ÷ 2    | 2        | 0         |
| 2 ÷ 2    | 1        | 0         |
| 1 ÷ 2    | 0        | 1         |

Read the remainders from bottom to top.

Answer: 15610=100111002\boxed{156_{10}=10011100_2}15610=100111002

### b) Decimal to Octal

Divide by 8 repeatedly.

| Division | Quotient | Remainder |
| -------- | -------- | --------- |
| 156 ÷ 8  | 19       | 4         |
| 19 ÷ 8   | 2        | 3         |
| 2 ÷ 8    | 0        | 2         |

Read the remainders from bottom to top.

Answer: 15610=2348\boxed{156_{10}=234_8}15610=2348

### c) Decimal to Hexadecimal

Divide by 16 repeatedly.

| Division | Quotient | Remainder |
| -------- | -------- | --------- |
| 156 ÷ 16 | 9        | 12 (C)    |
| 9 ÷ 16   | 0        | 9         |

Read the remainders from bottom to top. In hexadecimal, 12 is represented by C.

Answer: 15610=9C16\boxed{156_{10}=9C_{16}}15610=9C16

## 2. Convert binary number 1011012101101_21011012

### a) Binary to Decimal

Multiply each binary digit by its corresponding power of 2.

1011012=1(25)+0(24)+1(23)+1(22)+0(21)+1(20)=32+0+8+4+0+1=45\begin{aligned} 101101_2={}&1(2^5)+0(2^4)+1(2^3)\\ &+1(2^2)+0(2^1)+1(2^0)\\ ={}&32+0+8+4+0+1\\ ={}&45 \end{aligned}1011012===1(25)+0(24)+1(23)+1(22)+0(21)+1(20)32+0+8+4+0+145

Answer: 1011012=4510\boxed{101101_2=45_{10}}1011012=4510

### b) Binary to Octal

Group the binary digits into groups of three, starting from the right.

101101101\quad101101101

Convert each group to an octal digit:

* 1012=58101_2=5_81012=58

* 1012=58101_2=5_81012=58

Answer: 1011012=558\boxed{101101_2=55_8}1011012=558

### c) Binary to Hexadecimal

Group the binary digits into groups of four, starting from the right. Add leading zeros if necessary.

001011010010\quad110100101101

Convert each group to hexadecimal:

* 00102=2160010_2=2_{16}00102=216

* 11012=D161101_2=D_{16}11012=D16

Answer: 1011012=2D16\boxed{101101_2=2D_{16}}1011012=2D16

## 3. Convert octal number 7458745_87458

### a) Octal to Decimal

Multiply each digit by its corresponding power of 8.

7458=7(82)+4(81)+5(80)=7(64)+4(8)+5(1)=448+32+5=485\begin{aligned} 745_8&=7(8^2)+4(8^1)+5(8^0)\\ &=7(64)+4(8)+5(1)\\ &=448+32+5\\ &=485 \end{aligned}7458=7(82)+4(81)+5(80)=7(64)+4(8)+5(1)=448+32+5=485

Answer: 7458=48510\boxed{745_8=485_{10}}7458=48510

### b) Octal to Binary

Convert each octal digit into its three-bit binary equivalent.

| Octal digit | Binary equivalent |
| ----------- | ----------------- |
| 7           | 111               |
| 4           | 100               |
| 5           | 101               |

Combine the binary groups.

111100101111\quad100\quad101111100101

Answer: 7458=1111001012\boxed{745_8=111100101_2}7458=1111001012

### c) Octal to Hexadecimal

First, convert the octal number to binary:

7458=1111001012745_8=111100101_27458=1111001012

Group the binary digits into sets of four from the right, adding leading zeros if needed.

0001111001010001\quad1110\quad0101000111100101

Convert each group to hexadecimal:

* 00012=1160001_2=1_{16}00012=116

* 11102=E161110_2=E_{16}11102=E16

* 01012=5160101_2=5_{16}01012=516

Answer: 7458=1E516\boxed{745_8=1E5_{16}}7458=1E516

## 4. Convert hexadecimal number 3F9163F9_{16}3F916

### a) Hexadecimal to Decimal

Multiply each digit by its corresponding power of 16. Remember that F=15F=15F=15.

3F916=3(162)+15(161)+9(160)=3(256)+15(16)+9(1)=768+240+9=1017\begin{aligned} 3F9_{16}&=3(16^2)+15(16^1)+9(16^0)\\ &=3(256)+15(16)+9(1)\\ &=768+240+9\\ &=1017 \end{aligned}3F916=3(162)+15(161)+9(160)=3(256)+15(16)+9(1)=768+240+9=1017

Answer: 3F916=101710\boxed{3F9_{16}=1017_{10}}3F916=101710

### b) Hexadecimal to Binary

Convert each hexadecimal digit into its four-bit binary equivalent.

| Hexadecimal digit | Binary equivalent |
| ----------------- | ----------------- |
| 3                 | 0011              |
| F                 | 1111              |
| 9                 | 1001              |

Combine the binary groups.

0011111110010011\quad1111\quad1001001111111001

Remove the leading zeros.

Answer: 3F916=11111110012\boxed{3F9_{16}=1111111001_2}3F916=11111110012

### c) Hexadecimal to Octal

First, convert hexadecimal to binary:

3F916=00111111100123F9_{16}=001111111001_23F916=0011111110012

Group the binary digits into sets of three from the right.

001111111001001\quad111\quad111\quad001001111111001

Convert each group to octal:

* 0012=18001_2=1_80012=18

* 1112=78111_2=7_81112=78

* 1112=78111_2=7_81112=78

* 0012=18001_2=1_80012=18

Answer: 3F916=17718\boxed{3F9_{16}=1771_8}3F916=17718

## Final answers at a glance

| No. | Original number        | Converted values                           |
| --- | ---------------------- | ------------------------------------------ |
| 1   | 15610156_{10}15610     | Binary: 10011100210011100_2100111002       |
|     |                        | Octal: 2348234_82348                       |
|     |                        | Hexadecimal: 9C169C_{16}9C16               |
| 2   | 1011012101101_21011012 | Decimal: 451045_{10}4510                   |
|     |                        | Octal: 55855_8558                          |
|     |                        | Hexadecimal: 2D162D_{16}2D16               |
| 3   | 7458745_87458          | Decimal: 48510485_{10}48510                |
|     |                        | Binary: 1111001012111100101_21111001012    |
|     |                        | Hexadecimal: 1E5161E5_{16}1E516            |
| 4   | 3F9163F9_{16}3F916     | Decimal: 1017101017_{10}101710             |
|     |                        | Binary: 111111100121111111001_211111110012 |
|     |                        | Octal: 177181771_817718                    |

Remember these rules:

* To decimal: Multiply each digit by its base raised to the appropriate position power, then add.

* From decimal: Repeatedly divide by the target base and read the remainders from bottom to top.

* Binary to octal: Group binary digits in sets of 3.

* Binary to hexadecimal: Group binary digits in sets of 4.

* Octal or hexadecimal to another base: Convert to binary first when convenient.
