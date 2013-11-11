Note that in order to achieve the accuracy of this set of data, I ran training 
	several times aiming for an error between 50 and 150 in the 
	iterations. If the error is too small or too large, the accuracy
	is not good (this is based on the tests I have made). 


MultipassCRF used: 
	Gate vs. Nongate (Stage 1) followed by Wire vs. Label (Stage 2)

Site feature functions used:

	Gate vs. Nongate (Stage 1):

	biasFUnction
	distBetweenEndsLarge
	distBetweenEndsSmall
	arcLengthShort
	arcLengthLong
	turningZero
	turningSmall
	turning360
	turningLarge
	distFromLR
	distFromTB
	twoCorners

	Wire vs. Label (Stage 2):
	
	All of the above except for the last two but plus
	squareInkDensityHigh
	squareInkDensityLow

Interaction feature functions used:

	Gate vs. Nongate (Stage 1):

	touching
	minDistSmall
	minDistLarge
	maxDistSmall
	maxDistLarge
	corner
	minDistEndsLarge
	distAvgPtsSmall
	distAvgPtsLarge
	arePerpendicular
	areParallel
	biasFunction
	endsClose
	penLifted
	straightCurved
	curvedStraingth
	strainghtStraiht
	curvedCurved
	similarlyBounded
	angleSmall
	angleLarge
	CS_TJxn
	SC_TJXN
	minTimeSmall
	minTimeLarge

	Wire vs. Label (Stage 2):

	All of the above except for the last four.	
