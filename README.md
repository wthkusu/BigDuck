App Purpose:
1. Display chosen currency exchange rates.
2. The app allows users to quickly and accurately convert amounts between various currencies based on current exchange rates.
3. Designed for user-friendliness, the app enables individuals to input amounts and select currencies with minimal effort, making it accessible for both casual users and frequent travelers.
4. It can also serve as an educational tool, helping users learn about currency values and market fluctuations, enhancing their understanding of global finance.
5. The app serves as a handy tool for travelers, businesses, and anyone dealing with multiple currencies.

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


Functional requirements

1.The system must allow users to input a numeric amount and select both the source currency and target currency from a list of supported currencies.

2.The application must retrieve real-time exchange rates for the selected currency pair. The system should handle errors and display a user-friendly message if the data cannot be retrieved.

3.The system must accurately calculate the converted amount by multiplying the input amount by the retrieved exchange rate. The result should be rounded to two decimal places.

4.The application must maintain an up-to-date list of supported currencies and their respective codes, allowing users to select from these currencies when performing conversions.

5.Once the conversion is completed, the system must display the converted amount clearly, along with the source and target currencies and the current exchange rate used for the calculation.
