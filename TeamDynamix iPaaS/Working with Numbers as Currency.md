iPaaS does not have an inherint currenty format that I have been able to find. 

In order to make people feel like they are working with currency, on forms have a regex of ^\$\d{1,3}(,\d{3})*(\.\d{2})?$
applied to a string field.  Run the follow flow steps to work with the string as a number.

![Flow-Convert-Currency.png](pictures/Flow-Convert-Currency.png)

The "as Number" function in iPaaS will not convert with a $ at the beginning of the string.
On the otherhand the "Trim" function only works on blank spaces.  To address this use the "Replace with" 
function and replace "$" with a blank entry in the replace with field.  Once you have completd those steps
and the number only has the commas and the decimal point you can run it through the "as Number" function.

The flow will now work with that as a number.
