Type of classification:
	Gate vs. Nongate (Stage 1 using CRF) followed by 
        Wire vs. Label (Stage 2 using SVM)

Site feature functions used in the CRF (Stage 1):

	biasFunction
	distBetweenEndsLarge
	distBetweenEndsSmall
	arcLengthShort
	arcLengthLong
	turningZero
	turningSmall
	turning360
	turningLarge
	distFromLR
	squareInkDensityHigh
	squareInkDensityLow


Interaction feature functions used in the CRF (stage 1):

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

Feature functions used in the SVM (stage 2)


	arcLengthLong
	arcLengthShort
	distBetweenEndsLarge
	distBetweenEndsSmall
	turning360
	turningLarge
	turningSmall
	turningZero
	squareInkDensityHigh
	squareInkDensityLow
	distFromLR
	distFromTB