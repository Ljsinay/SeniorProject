# SeniorProject

Website aims to emulate what a typical online retalier would offer. 

The main page features the cart screen used for checkout.

On the lower portion of the screen lies the text input emulating where

a customer would input their wallet addess.

There are several checks done to the submitted address. 

These include prefix (1, 3, bc1), length, and finally if the address is apart of -

the knownbad list. This is currently stored in an array, with a few lines of code

it could be stored in a database as how it would be when deployed.

Javascript was used rather than python due to the ability for instructor grading.

With the amount of imported libraries and back-end server needs it would of been

time consuming for you, the instructor, to grade. The javascript code was adapted 

from the earlier python script and functions identically.

 
Below are the following criteria the script checks for.
* Prefix which valid wallet addresses hold (1, 3, or bc1)
* Length
* Match against 'known-bad' list

Website was tested useing a HTML5 compatible browser (Chrome)
With no ad-block extentions enabled.

Included are some sample input test parameteres to meet all conditions:

Address correct prefix, length too short - 
Gives alert "Please ensure the wallet address entered is between 24 and 35 characters"

1afGkAlTalNmA
3KLgaIloPA
1bcAlGjra19Al9

Address incorrect prefix, correct length-
Gives alert "Bitcoin Address Invalid!
Please enter a BTC address with 1, 3, or bc1"

9sVwx81CDPWu3vcHMUHPuzqrq5U
Icp48e2EzSrmOo9u75gM9Jie9eEk31f
spDeOBzo7S6hDo5dcoNn64zZgmO85m

Sample Addresses for 'Known-Bad' / Invalid - 
Gives alert" Wallet Address Allowed! You may proceed with checkout"

16ftSEQ4ctQFDnVZiUBusQUXRrGhM3JYwe
3D2oEtdNuZUpQHPJmcMDDHYoHkyNVsFk9r
1BcAQxUTiVjQ41qqRkLLZA16Vm5qrtJ6c2

Sample Addresses for valid addresses- 

1pAonqEtGUNkIY7P8N2C8uGkufWUK7X1
3I34cRtrmEexlDoE2IDKdNYZ5O0gFXbW
bc1qu3nEB0MVCk5G8E3FM1ST6ViQiNjYoi
