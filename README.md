# Home_Sales
<h2>Objective:</h2>Determine key metrics about home sales data.
<h2>Results:</h2>

* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
  
<img width="168" alt="Screenshot 2024-10-03 at 10 36 42 PM" src="https://github.com/user-attachments/assets/7d18ae53-3499-4b86-9564-38468e6ef877">

* What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

<img width="220" alt="Screenshot 2024-10-03 at 10 39 51 PM" src="https://github.com/user-attachments/assets/0b5c2836-d18a-4aea-8a0b-0ff749e6cf6c">

* What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

<img width="216" alt="Screenshot 2024-10-03 at 10 40 34 PM" src="https://github.com/user-attachments/assets/8df530ef-7643-4a13-a49d-323c4463dd50">

* What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

<img width="206" alt="Screenshot 2024-10-03 at 10 40 58 PM" src="https://github.com/user-attachments/assets/a672a88b-3b18-4a42-8ea3-ff5f9ac58d55">

<h2>Runtime Comparation:</h2>

* With the Original Data: --- 1.0169997215270996 seconds ---
* With the Cacheted Data: --- 0.912147045135498 seconds ---
* With the Partition by date_built Data: --- 1.0370490550994873 seconds ---

This means and we could demotrated that the better results were with cacheted data.
