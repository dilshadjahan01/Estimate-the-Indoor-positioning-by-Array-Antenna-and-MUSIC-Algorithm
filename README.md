# Estimate-the-Indoor-positioning-by-Array-Antenna-and-MUSIC-Algorithm
Generated position estimates X^, y^ from CSI using the MUSIC algorithm and array antenna. In theory, we could provide M×Nsub all "raw" channel coefficients to our neural network and let it directly estimate them from this raw data.
![image](https://github.com/dilshadjahan01/Estimate-the-Indoor-positioning-by-Array-Antenna-and-MUSIC-Algorithm/assets/106269209/685fa8f1-9d63-4cd5-a38e-d92050581e6d)

We plot the MUSIC spectrum and estimated DOAs to visually understand where signals are
coming from in relation to the antenna array. This helps us identify signal sources and verify the
accuracy of the direction of arrival estimation algorithm.

![image](https://github.com/dilshadjahan01/Estimate-the-Indoor-positioning-by-Array-Antenna-and-MUSIC-Algorithm/assets/106269209/b1cb3c8f-f62e-4954-94cf-66a76ca4a8e2)
Estimate DOA:
Use the music_doa function to estimate the DOA using the CSI data.
Assume the most probable DOA as the prediction.
Calculate Errors:
Compute the absolute errors by subtracting predicted positions from true positions.
Analyze Error Distribution:
Plot a histogram of the absolute error distances to visualize their distribution.
Fit a normal distribution curve to the absolute errors.
Mark outliers, defined as errors exceeding a threshold.
Display Statistics:
Print the number of outliers and their values.


![image](https://github.com/dilshadjahan01/Estimate-the-Indoor-positioning-by-Array-Antenna-and-MUSIC-Algorithm/assets/106269209/3b2220cf-df49-409a-ade9-3c651e78bd59)

The purpose of this code is to visually represent the distribution of absolute errors in a Direction
of Arrival (DOA) estimation algorithm. It uses a hexbin plot to show the spatial distribution of
errors relative to the true positions of the data points. By coloring each hexagon based on the
magnitude of the absolute error and overlaying the antenna location and data points, the plot
helps to quickly assess the performance of the algorithm and identify any patterns or outliers in
the errors.


![image](https://github.com/dilshadjahan01/Estimate-the-Indoor-positioning-by-Array-Antenna-and-MUSIC-Algorithm/assets/106269209/1b5fc08b-79c9-4974-90eb-de998b29593b)
The uniform linear array (ULA) is used in this context because it's simple, easy to implement,
and well-suited for tasks like the direction of arrival (DOA) estimation. Its equally spaced antennas
along a straight line provide directional sensitivity, making it effective for analyzing signals
arriving from specific directions. This array configuration facilitates spatial signal processing
techniques and is commonly used in research, education, and practical applications.

![image](https://github.com/dilshadjahan01/Estimate-the-Indoor-positioning-by-Array-Antenna-and-MUSIC-Algorithm/assets/106269209/a2805c3c-44df-4c3e-ba4a-36123e258f65)
