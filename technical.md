# Problem 1 - Answer

* Response to engineering team:

Hey (name of engineer),

I had a client come in with an issue regarding the balance of her "loan" account.  Her balance is showing up negative when it shouldn't be.

I've looked into the code and it seems like when you display the balance- it is subtracted from 0 and it will immediately become negative.  Here's the code for reference:

```
function balance(account) {
    let flippedAccountTypes = ['credit', 'loan'];

    if (flippedAccountTypes.includes(account.type)) {
      return 0 - Math.abs(account.balance); // returns negative here
    } else {
        return Math.abs(account.balance);
    }
  }
```

Any way we can get this resolved? Also- if you can give me an update regarding timeline so i can keep the customer informed.

Thanks!
-Alfonso

* Response to Matt:

Hi Matt,

Thank you for bringing this to my attention.
I've looked into your client's issue as to why his balance is showing negative when it shouldn't be.

I've contacted the engineering team and we are looking to fix the issue.
I'll keep you updated on a timeline as to when this will get resolved.

Do Let me know if there is anything else i can help you with.

All the best-
Alfonso.

# Problem 2 - Answer

Hi Megan-

I've looked into the issue you have submitted regarding your client's holdings in Vanguard Mid-Cap Index Fund.  With 1,320 shares at $45.10, the value is accurate at $59,532.00.

I looked up the identifier for "Vanguard Mid-Cap Index Fund Investor Shares" and it is showing that the ticker is "VIMSX" and is reflected accurately in our system (which is priced at $45.10 per share).

There is, however, another fund called "Vanguard Mid-Cap Index Fund Admiral" shares and it has the ticker "VIMAX."

Since your client is reflecting an accurate balance, I believe that the information in our system to be accurate as well.

If there is anything else I can help you with, let me know and I'll be happy to assist.

All the best-
Alfonso.

# Problem 3 - Answer

Hey (name of engineer),

I have a client email me with an issue regarding an account with an identifier CUR:CAD.  He has 1,596.17 shares valued at $0.76 (Canadian Dollars).  Our system is showing it as 1,213.09 US Dollars, which is giving him a discrepancy of around $300.

Can we fix this and have the value reflected in CAD instead of USD?

Also- if you can give me an update regarding timeline so i can keep the customer informed.

Thanks!
-Alfonso
