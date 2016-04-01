LOLCODE
=======
A Quick Reference
-----------------

### Version ###
    HAI 1.2

    KTHXBYE

### Comments ###
    BTW Line comment
    OBTW
        Block comment
    TLDR

### Variables ###
    BTW Case sensitive variables
    I HAS A variable
    I HAS A otherVariable ITZ 3

    BTW Assignment
    variable R "O HAI"

### Input/Output ###
    BTW Output
    VISIBLE "Hai wurld!"

    BTW Input
    I HAS A values
    GIMMEH values

### Types ###
    BTW Type casting
    MAEK variable A TROOF

 | Type     | Meaning   |
 |----------|-----------|
 | NOOB     | untyped   |
 | TROOF    | boolean   |
 | NUMBR    | integer   |
 | NUMBAR   | float     |
 | YARN     | string    |

### Strings ###
    BTW Concatenation
    SMOOSH "Can has a " AN "CHEESEBURGER" MKAY
 | Escape           | Meaning       |
 |------------------|---------------|
 | :)               | \n            |
 | :>               | \t            |
 | :o               | \g (beep)     |
 | :"               | "             |
 | ::               | :             |
 | :(&lt;hex&gt;)   | Unicode       |
 | :{&lt;var&gt;}   | Interpolate   |

### Operators ###
    SUM OF a AN b                        BTW +
    DIFF OF a AN b                       BTW -
    PRODUKT OF a AN b                    BTW *
    QUOSHUNT OF a AN b                   BTW /
    MOD OF a AN b                        BTW modulo
    BIGGR OF a AN b                      BTW max
    SMALLR OF a AN b                     BTW min

    BOTH OF a AN b                       BTW and
    EITHER OF a AN b                     BTW or
    WON OF a AN b                        BTW xor
    NOT a                                BTW not

    BOTH SAEM a AN b                     BTW ==
    BOTH DIFFRINT a AN b                 BTW !=

	BOTH SAEM a AN BIGGR OF a AN b       BTW >=
	BOTH SAEM a AN SMALLR OF a AN b      BTW <=
	BOTH DIFFRINT a AN SMALLR OF a AN b  BTW >
	BOTH DIFFRINT a AN BIGGR OF a AN b   BTW <

### Flow Control ###
	BTW If statement
	BOTH SAEM a AN b
	O RLY?
		YA RLY
			BTW If
		MEBBE BOTH SAEM b AN c
			BTW ElseIf
		NO WAI
			BTW Else
	OIC

	BTW Case statement
	variable
	WTF?
		OMG "R"
			BTW variable = "R"
			GTFO
		OMG "Y"
			BTW variable = "Y"
		OMG "G"
			BTW variable = "Y" or variable = "G"
			GTFO
		OMGWTF
			BTW default
	OIC

	BTW While loop
	IM IN YR loop    BTW 'loop' is the name of the loop
		GTFO         BTW break
	IM OUTTA YR loop

	BTW Can also pretend to be a for loop
	IM IN YR forLoop UPPIN YR index TIL BOTH SAEM index AN 5
		VISIBLE index
	IM OUTTA YR forLoop

### Functions ###
	HOW IZ I functionName YR arg1 AN YR arg2
		BOTH SAEM arg1 AN "return the value"
		O RLY?
			YA RLY
				FOUND YR arg2  BTW Returns arg2
			NO WAI
				GTFO           BTW Returns NOOB
		OIC
	IF U SAY SO

	I IZ functionName YR "return the value" AN YR 3 MKAY
