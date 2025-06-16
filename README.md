HTML Inputs - Takes amount (number input) and currency selections (from and to dropdowns).
Fixed Exchange Rates - Uses a rates object (e.g., USD: 1.0, EUR: 0.93).
Conversion Formula - Converts via (amount / rates[from]) * rates[to].
USD Base Conversion - First converts to USD, then to the target currency.
Result Display - Shows formatted result (e.g., 100 USD = 83.50 INR).
Validation - Checks if amount is positive; else shows error.
Static Rates - Rates don’t update automatically (hardcoded).
No API/Libraries - Pure HTML/CSS/JS with no external dependencies.
Mobile-Friendly - Responsive design works on all devices.
Limitation - Needs an API for real-time rates.
