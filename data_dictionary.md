## Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|**intended_major**|*object*|SAT Major Earnings|The field of study the SAT test taker intends to enter into.| 
**MS SubClass**|*int64*|train_lasso|Type of dwelling
**Lot Frontage**|*float64*|train_lasso|Street connection to lot
**Lot Area**|*int64*|train_lasso|Area of lot
**Overall Qual**|*int64*|train_lasso|Quality Overall 1-5
**Overall Cond**|*int64*|train_lasso|Condition Overall 1-5
**Year Built**|*int64*|train_lasso|Year built
**Year Remod/Add**|*int64*|train_lasso|Year Remodeled
**Exter Qual**|*int64*|train_lasso|Exterior Quality 1-5
**Exter Cond**|*int64*|train_lasso|Exterior Condition 1-5
**Bsmt Qual**|*float64*|train_lasso|Basement Quality 1-5
**Bsmt Cond**|*float64*|train_lasso|Basement Condition 1-5
**BsmtFin SF 1**|*float64*|train_lasso|Basement square foot
**BsmtFin SF 2**|*float64*|train_lasso|Basement square foot
**Bsmt Unf SF**|*float64*|train_lasso|Basement unfinished square foot
**Total Bsmt SF**|*float64*|train_lasso|Total basement square foot
**1st Flr SF**|*int64*|train_lasso|First Floor square feet
**2nd Flr SF**|*int64*|train_lasso|Second Floor square feet
**Low Qual Fin SF**|*int64*|train_lasso|Low quality finish square feet
**Gr Liv Area**|*int64*|train_lasso|Above Ground Living Area
**Bsmt Full Bath**|*float64*|train_lasso|Quantity Full bath in basement
**Bsmt Half Bath**|*float64*|train_lasso|Quantity half bath in basement
**Full Bath**|*int64*|train_lasso|Number of full baths
**Half Bath**|*int64*|train_lasso|Number of half baths
**Bedroom AbvGr**|*int64*|train_lasso|Number of bedrooms above ground
**Kitchen AbvGr**|*int64*|train_lasso|If Kitchen is above ground
**Kitchen Qual**|*int64*|train_lasso|Kitchen quality 1-5
**TotRms AbvGrd**|*int64*|train_lasso|Number of rooms above ground
**Fireplaces**|*int64*|train_lasso|Number of fireplaces
**Fireplace Qu**|*float64*|train_lasso|Fireplace quality 1-5
**Garage Yr Blt**|*float64*|train_lasso|Year garage built
**Garage Finish**|*int64*|train_lasso|Garage interior finish
**Garage Cars**|*float64*|train_lasso|Number of car garage
**Garage Area**|*float64*|train_lasso|Square feet area in garage
**Garage Qual**|*float64*|train_lasso|Garage quality 1-5
**Garage Cond**|*object*|train_lasso|Garage condition 1-5
**Wood Deck SF**|*int64*|train_lasso|Wood deck square feet
**Open Porch SF**|*int64*|train_lasso|Open porch square feet
**Enclosed Porch**|*int64*|train_lasso|Has enclosed porch
**3Ssn Porch**|*int64*|train_lasso|Three season porch sq ft
**Screen Porch**|*int64*|train_lasso|Screened porch sq ft
**Pool Area**|*int64*|train_lasso|Sq ft area of pool
**Misc Val**|*int64*|train_lasso|Value of misc features
**Mo Sold**|*int64*|train_lasso|Month sold
**Yr Sold**|*int64*|train_lasso|Year sold
**BsmtFin SF 1 **2**|*float64*|train_lasso|Finished square feet of basement squared (Feature Engineered)
**Total Bsmt SF **2**|*float64*|train_lasso|Total square feet of basement squared (Feature Engineered)
**Gr Liv Area **2**|*int64*|train_lasso|Above ground square feet of living area squared (Feature Engineered)
**Garage Yr Blt **2**|*float64*|train_lasso|Year garage built squared (Feature Engineered)
**Overall Qual **2**|*int64*|train_lasso|Overall Quality squared
**Land Contour_HLS**|*uint8*|train_lasso|Land is on hillside (One hot encoded)
**Land Contour_Low**|*uint8*|train_lasso|Low slope in land(One hot encoded)
**Land Contour_Lvl**|*uint8*|train_lasso|Level lot (One hot encoded)
**Land Slope_Mod**|*uint8*|train_lasso|Moderate slope on lot (One hot encoded)
**Land Slope_Sev**|*uint8*|train_lasso|Severe slope on lot(One hot encoded)
**Neighborhood_Blueste**|*uint8*|train_lasso|Bluestem
**Neighborhood_BrDale**|*uint8*|train_lasso|Briardale
**Neighborhood_BrkSide**|*uint8*|train_lasso|Brookside
**Neighborhood_ClearCr**|*uint8*|train_lasso|Clear Creek
**Neighborhood_CollgCr**|*uint8*|train_lasso|College Creek
**Neighborhood_Crawfor**|*uint8*|train_lasso|Crawford
**Neighborhood_Edwards**|*uint8*|train_lasso|Edwards
**Neighborhood_Gilbert**|*uint8*|train_lasso|Gilbert
**Neighborhood_Greens**|*uint8*|train_lasso|Greens
**Neighborhood_GrnHill**|*uint8*|train_lasso|Green Hills
**Neighborhood_IDOTRR**|*uint8*|train_lasso|Iowa DOT and Rail Road
**Neighborhood_Landmrk**|*uint8*|train_lasso|Landmark
**Neighborhood_MeadowV**|*uint8*|train_lasso|Meadow Village
**Neighborhood_Mitchel**|*uint8*|train_lasso|Mitchell
**Neighborhood_NAmes**|*uint8*|train_lasso|North Ames
**Neighborhood_NPkVill**|*uint8*|train_lasso|Northridge
**Neighborhood_NWAmes**|*uint8*|train_lasso|Northpark Villa
**Neighborhood_NoRidge**|*uint8*|train_lasso|Northridge Heights
**Neighborhood_NridgHt**|*uint8*|train_lasso|Northwest Ames
**Neighborhood_OldTown**|*uint8*|train_lasso|Old Town
**Neighborhood_SWISU**|*uint8*|train_lasso|South & West of Iowa State University
**Neighborhood_Sawyer**|*uint8*|train_lasso|Sawyer
**Neighborhood_SawyerW**|*uint8*|train_lasso|Sawyer West
**Neighborhood_Somerst**|*uint8*|train_lasso|Somerset
**Neighborhood_StoneBr**|*uint8*|train_lasso|Stone Brook
**Neighborhood_Timber**|*uint8*|train_lasso|Timberland
**Neighborhood_Veenker**|*uint8*|train_lasso|Veenker
**Condition 1_Feedr**|*uint8*|train_lasso|Adjacent to feeder street (One hot encoded)
**Condition 1_Norm**|*uint8*|train_lasso|Normal (One hot encoded)
**Condition 1_PosA**|*uint8*|train_lasso|Adjacent to postive off-site feature (One hot encoded)
**Condition 1_PosN**|*uint8*|train_lasso|Near positive off-site feature--park, greenbelt, etc. (One hot encoded)
**Condition 1_RRAe**|*uint8*|train_lasso|Adjacent to East-West Railroad (One hot encoded)
**Condition 1_RRAn**|*uint8*|train_lasso|Adjacent to North-South Railroad (One hot encoded)
**Condition 1_RRNe**|*uint8*|train_lasso|Within 200' of East-West Railroad (One hot encoded)
**Condition 1_RRNn**|*uint8*|train_lasso|Within 200' of North-South Railroad (One hot encoded)
**Condition 2_Feedr**|*uint8*|train_lasso|Adjacent to feeder street (One hot encoded)
**Condition 2_Norm**|*uint8*|train_lasso|Normal (One hot encoded)
**Condition 2_PosA**|*uint8*|train_lasso|Adjacent to postive off-site feature (One hot encoded)
**Condition 2_PosN**|*uint8*|train_lasso|Near positive off-site feature--park, greenbelt, etc. (One hot encoded)
**Condition 2_RRAe**|*uint8*|train_lasso|Adjacent to East-West Railroad (One hot encoded)
**Condition 2_RRAn**|*uint8*|train_lasso|Adjacent to North-South Railroad (One hot encoded)
**Condition 2_RRNn**|*uint8*|train_lasso|Within 200' of North-South Railroad
**House Style_1.5Unf**|*uint8*|train_lasso|One and one-half story: 2nd level unfinished (One hot encoded)
**House Style_1Story**|*uint8*|train_lasso|One story (One hot encoded)
**House Style_2.5Fin**|*uint8*|train_lasso|Two and one-half story: 2nd level finished (One hot encoded)
**House Style_2.5Unf**|*uint8*|train_lasso|Two and one-half story: 2nd level unfinished (One hot encoded)
**House Style_2Story**|*uint8*|train_lasso|Two story (One hot encoded)
**House Style_SFoyer**|*uint8*|train_lasso|Split Foyer (One hot encoded)
**House Style_SLvl**|*uint8*|train_lasso|Split Level (One hot encoded)