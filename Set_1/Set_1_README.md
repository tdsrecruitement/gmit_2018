# SMS Spam Detection

SMS spam detection is very common nowadays. Identifying Spam SMS from a collection is used to identify authencity of SMS exchange between users.

You need to find the SMS which can be categorized as SPAM (fraud) or HAM (genuine).

The following are the tasks you need to do in this assignments:

1. Download Dataset 
2. Find the Spam SMS from the dataset based on keywords
    * Sample SPAM keyword (free, jackpot, winner, ...)
3. Find HAMs from the dataset based on words. HAM are those SMS, which do not contain words defined in spam keywords
4. Export all the sentences with spam and ham tagging to a csv file. You should create separate files for spam and ham.
    * Example
  
    | id | SMS  | Tag |
    | -- | ---  | --- |
    | 12 | Ok lar... Joking wif u oni...			| SPAM |
    | 12 | Thanks for your subscription to Ringtone UK your mobile will be charged £5/month		| SPAM |
5. Get frequency of each SPAM keywords in each 
   SMS

   Sample SMS:
   ```
   WINNER!! As a valued network customer you have been selected to receivea £900 jackpot prize reward! To claim jackpot prize call 09061701461. Claim code KL341. Valid 12 hours only.
   ```

   Sample Output:

   ```
   {
       "WINNER" : 1,
       "jackpot" : 2
   }
   ```

6. Get weight of each spam keywords
   
   ```
    In above sample SMS, total weight = 
    frequency of "winner" + frequency of "jackpot"
    => 1 + 2  = 3
    ```

7. Show top 5 spam sentences based on weights. 