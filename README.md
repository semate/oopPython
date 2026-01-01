
Question 1: UBOS Multi-District Population & Growth Forecast Given the following dataset (Population estimates in thousands for 10 years):
Kampala = [1200, 1250, 1300, 1350, 1420, 1500, 1580, 1650, 1720, 1800] Wakiso = [950, 1000, 1070, 1150, 1220, 1300, 1390, 1480, 1570, 1670] Gulu = [320, 330, 345, 360, 375, 390, 410, 430, 455, 480]
Attempt the following tasks:
1.1. Store the data for each district in a NumPy array.
1.2. Use the statistics module to compute mean, median, variance, and standard
deviation for each district.
1.3. Generate a Fibonacci sequence of length 5 to project the next 5 years of growth.
1.4. Compare the variance of actual vs projected data.
1.5. Plot actual vs projected populations using Matplotlib.


Question 2: Solar Micro-Grid Simulation
Equations: 3x + 2y = D1 and 4x + y = D2, where x = solar panels, y = batteries.
Attempt the following tasks:
2.1. Prompt the user to enter daily demand values D1 and D2.
2.2. Use scipy.linalg.solve() to calculate energy from solar panels and batteries.
2.3. Repeat for 7 days, storing results in a NumPy array.
2.4. Use statistics to compute mean, variance, and standard deviation of solar vs
battery usage.
2.5. Plot daily solar vs battery usage.


Question 3: Lake Victoria Fish Export Risk Model Attempt the following tasks:
3.1. Generate 15 Fibonacci numbers to simulate fish stock growth.
3.2. Simulate fish prices in UGX per kg, e.g. [12000, 12500, 11800, 13000, 12800,...].
3.3. Multiply stock × price to estimate daily revenue.
3.4. Compute mean, median, variance of revenue using statistics.
3.5. Print 'High risk' if variance > 50,000, else 'Low risk'.
3.6. Plot fish stock vs revenue trend.

Question 4: Weather & Agriculture Analysis Rainfall data (mm) for Kampala across 12 months:
[120, 140, 180, 200, 220, 180, 90, 70, 60, 100, 110, 130] Attempt the following tasks:
4.1. Store rainfall data in a NumPy array.
4.2. Compute mean rainfall and classify months as 'Good for maize' (>150mm) or
'Drought risk' (<150mm).
4.3. Simulate Gulu rainfall with different values.
4.4. Compute cosine similarity of Kampala vs Gulu rainfall trends using math.cos().
4.5. Plot both regions' rainfall in one chart.

Question 5: Taxi Transport Revenue & Variability
Passenger counts for 10 days on Kampala–Ntinda route: [35, 40, 42, 50, 55, 60, 48, 52, 47, 45]
Attempt the following tasks:
5.1. Store passenger counts in a NumPy array.
5.2. Compute daily revenues at UGX 2000 per passenger.
5.3. Use statistics to analyze mean, variance, and std deviation.
5.4. Use scipy.linalg.solve to model a simple supply-demand system.
5.5. Forecast 11th day's revenue using average of last 3 days.
5.6. Plot actual vs forecasted revenues.

# **Uploaded Assigment 2 and 3 as well.**