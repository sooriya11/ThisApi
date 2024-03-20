
These test cases cover various scenarios to ensure robustness and reliability of the API. Here they are, with some additional clarification:

Test with correct stock symbol: Verify that the API returns the current stock price for a known, valid stock symbol like "RIL".

Test with a stock symbol which does not exist: Confirm that the API returns an appropriate error message or code when provided with a nonexistent stock symbol like "XYZ".

Test with stock symbol in all caps: Ensure that the API is case-insensitive and returns the same result regardless of whether the stock symbol is provided in all uppercase or not.

Test with stock symbol in all small: Similar to the previous test case, but ensuring that the API handles stock symbols provided in all lowercase.

Test with blank stock symbol: Validate that the API handles cases where the stock symbol input is an empty string and provides an appropriate error response.

Test with null stock symbol: Verify that the API handles cases where the stock symbol input is null and provides an appropriate error response.

Test with missing stock symbol field: Ensure that the API handles cases where the stock symbol field is completely absent from the request and provides an appropriate error response.

Test with 1 stock symbol in each category - small cap, mid cap, large cap: Test the API's capability to handle different types of stocks by providing one stock symbol from each category (small cap, mid cap, large cap) and verify that it returns the respective stock prices correctly.

Test with stock symbol which has been delisted: Check whether the API handles cases where the provided stock symbol has been delisted from the stock exchange and provides an appropriate response, such as an error indicating that the stock is no longer traded.

These test cases cover a broad range of scenarios to ensure that the API functions correctly and handles various inputs gracefully.



