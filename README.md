App Purpose:
1. Display chosen currency exchange rates.

User Stories:
1. As a user, I should be able to create a user account.
2. As a user, I should be able to log into the app with my created app.
3. As a user, I should be able to add currency exchange rates to my account.
4. As a user, I should be able to remove currency exchange rates from my account.
5. As a user, I should be able to enter a foreign currency amount and convert it to Euros.
6. As a user, I should be able to view a history of exchange rates for my currencies.



5 Acceptance criteria

1.Valid Input Handling:
The application must accept valid numeric amounts and currency codes (e.g., "USD", "EUR") as input. If the input is invalid (e.g., non-numeric values or unsupported currency codes), the system should display an appropriate error message.

2.Exchange Rate Retrieval:
The system must accurately retrieve the current exchange rate from a reliable source for the specified currency pair (e.g., USD to EUR). The exchange rate should be updated at least once every 24 hours to ensure accuracy.

3.Correct Conversion Calculation:
The application must correctly calculate the converted amount based on the input amount and the retrieved exchange rate. The calculated result should be displayed with two decimal points of precision.

4.User Interface and Usability:
The user interface must be  user-friendly, allowing users to easily input amounts and select currencies. Users should be able to perform a conversion.

5.Performance Requirements:
The system should return the conversion result within 5 seconds of input submission. If there is a delay or failure in retrieving exchange rates, the system must display a clear error message to the user.
