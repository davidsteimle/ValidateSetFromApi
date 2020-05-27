# Validate Set from API
Use an API to provide set validation for a paramater.

> This process draws **greatly** from [Creating Dynamic Sets for ValidateSet](https://vexx32.github.io/2018/11/29/Dynamic-ValidateSet/).

My original need was to create a list of valid color names to include in a funtion's paramater list, but at 144 entries it made the script quite cumbersome. I created [a JSON version](https://github.com/davidsteimle/ValidateSetFromApi/raw/master/colors.json), and used ``Invoke-RestMethod`` inside [Vexx32](https://vexx32.github.io/)'s process for creating a dynamic set.
