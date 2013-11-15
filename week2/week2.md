Week 2

Linear Regression with Multiple Variables

	- Multiple Features:
		More powerful than just single featured/variable regression.

		Exm: 
			x1 - Size | x2 - Number of bedrooms | x3 - Number of flooes | x4 - Age of home

			Here,  n - Number of features/variables


Gradient Descent with Multiple Variables

	- Start viewing the parametes(O1, O2, O3...On) as simply O -> (n+1) dimensional vector

	Hypothesis, h(x) = O'X


	Gradient Descent in practise

		- Feature Scaling:
			If in our problem, we have multiple features.
				Make sure that those features are on the SAME SCALE.

			Exm: X1= Size of house(0-2000 feet^2)
				 X2= Number of bedrooms(1-6) 

			Here the "scales" are NOT similar.
				This results in the contour plots being Skinny.
				Also. the Gradient steps become slow.
				It takes too long.

			So, to deal with this -> Scale the features to similar levels.
				X1 - Size / 2000
				X2 - No. of bedrooms / 6

			Idea is to get every feature into an approx -1 <= X(i) <= 1 range

			So, divide the numbers in the features to get to the proper scale.
			However, features DO NOT have to be exactly in the same scale. Close enough works.

		- Mean Normalization:
			Replace X(i) with (Xi - Ui) to make features have approximately Zero mean.

			Exm: X1 = Size - 1000 / 2000
				 X2 = No. of bedrooms - 2 / 6


	Gradient Descent may take different number of iterations to converge for different application.

	Automatic Convergence Test
		- Tells us veforehand whether the G.D algo will converge by some small value(e) after
		  a single iteration. 

	For sufficiently small a, J(O) should decrease on every iteration.

Features & Polynomial regression.
	
	Using our own insight, we can "twist" things using that insight.
	We can choose some other features than we initially have.

	Polynomial Regression
		We can fit more than single model.
		We can fit multple models(Say, Quadratic model, Cubic function etc)

Normal Equation
	N.E for some linear regression problem gives us a better way to solve for 
	the "optimal value" forthe paremeters O.

	In contrast to Gradient Descent( where we solve incrementally/iteratively), Normal Equation allows us to solve for O "analytically".
	We can solve "in one go"
	So it takes one step to get to the optimal value.


- However, the advantage of Gradient Descent is that, G.D works very well, even when the 
  number of features(n)is very large [say >= 10^6]

- Normal equation gets slow if n is large (say n >= 10^5)

- Moreover, advanced algos like Logistic regression(for Classification) can not be solved
  using Normal Equation.














