# Ames Housing Dataset - Feature Metadata

## Dataset Overview
The Ames Housing dataset contains information about residential properties in Ames, Iowa, including 79 explanatory variables describing various aspects of residential homes. This dataset is commonly used for regression analysis and machine learning tasks to predict house prices.

## Target Variable
- **SalePrice**: The property's sale price in dollars (USD) - This is the target variable for prediction

## Feature Categories and Descriptions

### 1. Identification Features
- **Order**: Sequential row number (integer)
- **PID**: Parcel identification number (integer) - Unique identifier for each property

### 2. Property Classification
- **MS SubClass**: Identifies the type of dwelling involved in the sale (integer)
  - 020: 1-STORY 1946 & NEWER ALL STYLES
  - 030: 1-STORY 1945 & OLDER
  - 040: 1-STORY W/FINISHED ATTIC ALL AGES
  - 050: 1-1/2 STORY - UNFINISHED ALL AGES
  - 060: 1-1/2 STORY FINISHED ALL AGES
  - 070: 2-STORY 1946 & NEWER
  - 080: 2-STORY 1945 & OLDER
  - 090: 2-STORY W/FINISHED ATTIC ALL AGES
  - 120: 1-STORY PUD (Planned Unit Development) - 1946 & NEWER
  - 150: 1-1/2 STORY PUD - ALL AGES
  - 160: 2-STORY PUD - 1946 & NEWER
  - 180: PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
  - 190: 2 FAMILY CONVERSION - ALL STYLES AND AGES

- **MS Zoning**: Identifies the general zoning classification of the sale (categorical)
  - A (agr): Agriculture
  - C (all): Commercial
  - FV: Floating Village Residential
  - I (all): Industrial
  - RH: Residential High Density
  - RL: Residential Low Density
  - RP: Residential Low Density Park
  - RM: Residential Medium Density

### 3. Lot Information
- **Lot Frontage**: Linear feet of street connected to property (integer, feet)
- **Lot Area**: Lot size in square feet (integer, square feet)
- **Street**: Type of road access to property (categorical)
  - Grvl: Gravel
  - Pave: Paved
- **Alley**: Type of alley access to property (categorical)
  - Grvl: Gravel
  - Pave: Paved
  - NA: No alley access
- **Lot Shape**: General shape of property (categorical)
  - Reg: Regular
  - IR1: Slightly irregular
  - IR2: Moderately irregular
  - IR3: Irregular
- **Land Contour**: Flatness of the property (categorical)
  - Lvl: Near flat/level
  - Bnk: Banked - Quick and significant rise from street grade to building
  - HLS: Hillside - Significant slope from side to side
  - Low: Depression
- **Utilities**: Type of utilities available (categorical)
  - AllPub: All public utilities (E,G,W,& S)
  - NoSewr: Electricity, Gas, and Water (Septic Tank)
  - NoSeWa: Electricity and Gas Only
  - ELO: Electricity only
- **Lot Config**: Lot configuration (categorical)
  - Inside: Inside lot
  - Corner: Corner lot
  - CulDSac: Cul-de-sac
  - FR2: Frontage on 2 sides of property
  - FR3: Frontage on 3 sides of property
- **Land Slope**: Slope of property (categorical)
  - Gtl: Gentle slope
  - Mod: Moderate slope
  - Sev: Severe slope

### 4. Neighborhood Information
- **Neighborhood**: Physical locations within Ames city limits (categorical)
  - Various neighborhoods including NAmes, CollgCr, OldTown, Edwards, etc.

### 5. Property Conditions
- **Condition 1**: Proximity to various conditions (categorical)
  - Artery: Adjacent to arterial street
  - Feedr: Adjacent to feeder street
  - Norm: Normal
  - RRNn: Within 200' of North-South Railroad
  - RRAn: Adjacent to North-South Railroad
  - PosN: Near positive off-site feature--park, greenbelt, etc.
  - PosA: Adjacent to postive off-site feature
  - RRNe: Within 200' of East-West Railroad
  - RRAe: Adjacent to East-West Railroad
- **Condition 2**: Proximity to various conditions (if more than one is present) (categorical)
  - Same categories as Condition 1

### 6. Building Information
- **Bldg Type**: Type of dwelling (categorical)
  - 1Fam: Single-family Detached
  - 2FmCon: Two-family Conversion; originally built as one-family dwelling
  - Duplex: Duplex
  - TwnhsE: Townhouse End Unit
  - TwnhsI: Townhouse Inside Unit
- **House Style**: Style of dwelling (categorical)
  - 1Story: One story
  - 1.5Fin: One and one-half story: 2nd level finished
  - 1.5Unf: One and one-half story: 2nd level unfinished
  - 2Story: Two story
  - 2.5Fin: Two and one-half story: 2nd level finished
  - 2.5Unf: Two and one-half story: 2nd level unfinished
  - SFoyer: Split Foyer
  - SLvl: Split Level

### 7. Quality Ratings
- **Overall Qual**: Rates the overall material and finish of the house (integer, 1-10)
  - 10: Very Excellent
  - 9: Excellent
  - 8: Very Good
  - 7: Good
  - 6: Above Average
  - 5: Average
  - 4: Below Average
  - 3: Fair
  - 2: Poor
  - 1: Very Poor
- **Overall Cond**: Rates the overall condition of the house (integer, 1-9)
  - 9: Excellent
  - 8: Very Good
  - 7: Good
  - 6: Above Average
  - 5: Average
  - 4: Below Average
  - 3: Fair
  - 2: Poor
  - 1: Very Poor

### 8. Year Information
- **Year Built**: Original construction date (integer, year)
- **Year Remod/Add**: Remodel date (same as construction date if no remodeling or additions) (integer, year)

### 9. Roof Information
- **Roof Style**: Type of roof (categorical)
  - Flat: Flat
  - Gable: Gable
  - Gambrel: Gabrel (Barn)
  - Hip: Hip
  - Mansard: Mansard
  - Shed: Shed
- **Roof Matl**: Roof material (categorical)
  - ClyTile: Clay or Tile
  - CompShg: Standard (Composite) Shingle
  - Membran: Membrane
  - Metal: Metal
  - Roll: Roll
  - Tar&Grv: Gravel & Tar
  - WdShake: Wood Shakes
  - WdShngl: Wood Shingles

### 10. Exterior Information
- **Exterior 1st**: Exterior covering on house (categorical)
  - AsbShng: Asbestos Shingles
  - AsphShn: Asphalt Shingles
  - BrkComm: Brick Common
  - BrkFace: Brick Face
  - CBlock: Cinder Block
  - CemntBd: Cement Board
  - HdBoard: Hard Board
  - ImStucc: Imitation Stucco
  - MetalSd: Metal Siding
  - Other: Other
  - Plywood: Plywood
  - PreCast: PreCast
  - Stone: Stone
  - Stucco: Stucco
  - VinylSd: Vinyl Siding
  - Wd Sdng: Wood Siding
  - WdShing: Wood Shingles
- **Exterior 2nd**: Exterior covering on house (if more than one material) (categorical)
  - Same categories as Exterior 1st
- **Mas Vnr Type**: Masonry veneer type (categorical)
  - BrkCmn: Brick Common
  - BrkFace: Brick Face
  - CBlock: Cinder Block
  - None: None
  - Stone: Stone
- **Mas Vnr Area**: Masonry veneer area in square feet (integer, square feet)
- **Exter Qual**: Evaluates the quality of the material on the exterior (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Average/Typical
  - Fa: Fair
  - Po: Poor
- **Exter Cond**: Evaluates the present condition of the material on the exterior (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Average/Typical
  - Fa: Fair
  - Po: Poor

### 11. Foundation Information
- **Foundation**: Type of foundation (categorical)
  - BrkTil: Brick & Tile
  - CBlock: Cinder Block
  - PConc: Poured Contrete
  - Slab: Slab
  - Stone: Stone
  - Wood: Wood

### 12. Basement Information
- **Bsmt Qual**: Evaluates the height of the basement (categorical)
  - Ex: Excellent (100+ inches)
  - Gd: Good (90-99 inches)
  - TA: Typical (80-89 inches)
  - Fa: Fair (70-79 inches)
  - Po: Poor (<70 inches)
  - NA: No Basement
- **Bsmt Cond**: Evaluates the general condition of the basement (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Typical - slight dampness allowed
  - Fa: Fair - dampness or some cracking or settling
  - Po: Poor - Severe cracking, settling, or wetness
  - NA: No Basement
- **Bsmt Exposure**: Refers to walkout or garden level walls (categorical)
  - Gd: Good Exposure
  - Av: Average Exposure (split levels or foyers typically score average or above)
  - Mn: Mimimum Exposure
  - No: No Exposure
  - NA: No Basement
- **BsmtFin Type 1**: Rating of basement finished area (categorical)
  - GLQ: Good Living Quarters
  - ALQ: Average Living Quarters
  - BLQ: Below Average Living Quarters
  - Rec: Average Rec Room
  - LwQ: Low Quality
  - Unf: Unfinshed
  - NA: No Basement
- **BsmtFin SF 1**: Type 1 finished square feet (integer, square feet)
- **BsmtFin Type 2**: Rating of basement finished area (if multiple types) (categorical)
  - Same categories as BsmtFin Type 1
- **BsmtFin SF 2**: Type 2 finished square feet (integer, square feet)
- **Bsmt Unf SF**: Unfinished square feet of basement area (integer, square feet)
- **Total Bsmt SF**: Total square feet of basement area (integer, square feet)

### 13. Heating Information
- **Heating**: Type of heating (categorical)
  - Floor: Floor Furnace
  - GasA: Gas forced warm air furnace
  - GasW: Gas hot water or steam heat
  - Grav: Gravity furnace
  - OthW: Hot water or steam heat other than gas
  - Wall: Wall furnace
- **Heating QC**: Heating quality and condition (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Average/Typical
  - Fa: Fair
  - Po: Poor
- **Central Air**: Central air conditioning (categorical)
  - N: No
  - Y: Yes

### 14. Electrical Information
- **Electrical**: Electrical system (categorical)
  - SBrkr: Standard Circuit Breakers & Romex
  - FuseA: Fuse Box over 60 AMP and all Romex wiring (Average)
  - FuseF: 60 AMP Fuse Box and mostly Romex wiring (Fair)
  - FuseP: 60 AMP Fuse Box and mostly knob & tube wiring (Poor)
  - Mix: Mixed

### 15. Square Footage Information
- **1st Flr SF**: First Floor square feet (integer, square feet)
- **2nd Flr SF**: Second floor square feet (integer, square feet)
- **Low Qual Fin SF**: Low quality finished square feet (all floors) (integer, square feet)
- **Gr Liv Area**: Above grade (ground) living area square feet (integer, square feet)

### 16. Bathroom Information
- **Bsmt Full Bath**: Basement full bathrooms (integer, count)
- **Bsmt Half Bath**: Basement half bathrooms (integer, count)
- **Full Bath**: Full bathrooms above grade (integer, count)
- **Half Bath**: Half baths above grade (integer, count)

### 17. Bedroom and Kitchen Information
- **Bedroom AbvGr**: Bedrooms above grade (does NOT include basement bedrooms) (integer, count)
- **Kitchen AbvGr**: Kitchens above grade (integer, count)
- **Kitchen Qual**: Kitchen quality (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Typical/Average
  - Fa: Fair
  - Po: Poor
- **TotRms AbvGrd**: Total rooms above grade (does not include bathrooms) (integer, count)

### 18. Functional Information
- **Functional**: Home functionality (categorical)
  - Typ: Typical Functionality
  - Min1: Minor Deductions 1
  - Min2: Minor Deductions 2
  - Mod: Moderate Deductions
  - Maj1: Major Deductions 1
  - Maj2: Major Deductions 2
  - Sev: Severely Damaged
  - Sal: Salvage only

### 19. Fireplace Information
- **Fireplaces**: Number of fireplaces (integer, count)
- **Fireplace Qu**: Fireplace quality (categorical)
  - Ex: Excellent - Exceptional Masonry Fireplace
  - Gd: Good - Masonry Fireplace in main level
  - TA: Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
  - Fa: Fair - Prefabricated Fireplace in basement
  - Po: Poor - Ben Franklin Stove
  - NA: No Fireplace

### 20. Garage Information
- **Garage Type**: Garage location (categorical)
  - 2Types: More than one type of garage
  - Attchd: Attached to home
  - Basment: Basement Garage
  - BuiltIn: Built-In (Garage part of house - typically has room above garage)
  - CarPort: Car Port
  - Detchd: Detached from home
  - NA: No Garage
- **Garage Yr Blt**: Year garage was built (integer, year)
- **Garage Finish**: Interior finish of the garage (categorical)
  - Fin: Finished
  - RFn: Rough Finished
  - Unf: Unfinished
  - NA: No Garage
- **Garage Cars**: Size of garage in car capacity (integer, count)
- **Garage Area**: Size of garage in square feet (integer, square feet)
- **Garage Qual**: Garage quality (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Typical/Average
  - Fa: Fair
  - Po: Poor
  - NA: No Garage
- **Garage Cond**: Garage condition (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Typical/Average
  - Fa: Fair
  - Po: Poor
  - NA: No Garage

### 21. Driveway Information
- **Paved Drive**: Paved driveway (categorical)
  - Y: Paved
  - P: Partial Pavement
  - N: Dirt/Gravel

### 22. Porch and Deck Information
- **Wood Deck SF**: Wood deck area in square feet (integer, square feet)
- **Open Porch SF**: Open porch area in square feet (integer, square feet)
- **Enclosed Porch**: Enclosed porch area in square feet (integer, square feet)
- **3Ssn Porch**: Three season porch area in square feet (integer, square feet)
- **Screen Porch**: Screen porch area in square feet (integer, square feet)

### 23. Pool Information
- **Pool Area**: Pool area in square feet (integer, square feet)
- **Pool QC**: Pool quality (categorical)
  - Ex: Excellent
  - Gd: Good
  - TA: Average/Typical
  - Fa: Fair
  - NA: No Pool

### 24. Fence Information
- **Fence**: Fence quality (categorical)
  - GdPrv: Good Privacy
  - MnPrv: Minimum Privacy
  - GdWo: Good Wood
  - MnWw: Minimum Wood/Wire
  - NA: No Fence

### 25. Miscellaneous Information
- **Misc Feature**: Miscellaneous feature not covered in other categories (categorical)
  - Elev: Elevator
  - Gar2: 2nd Garage (if not described in garage section)
  - Othr: Other
  - Shed: Shed (over 100 SF)
  - TenC: Tennis Court
  - NA: None
- **Misc Val**: $Value of miscellaneous feature (integer, dollars)

### 26. Sale Information
- **Mo Sold**: Month Sold (integer, 1-12)
- **Yr Sold**: Year Sold (integer, year)
- **Sale Type**: Type of sale (categorical)
  - WD: Warranty Deed - Conventional
  - CWD: Warranty Deed - Cash
  - VWD: Warranty Deed - VA Loan
  - New: Home just constructed and sold
  - COD: Court Officer Deed/Estate
  - Con: Contract 15% Down payment regular terms
  - ConLw: Contract Low Down payment and interest
  - ConLI: Contract Low Interest
  - ConLD: Contract Low Down
  - Oth: Other
- **Sale Condition**: Condition of sale (categorical)
  - Normal: Normal Sale
  - Abnorml: Abnormal Sale - trade, foreclosure, short sale
  - AdjLand: Adjoining Land Purchase
  - Alloca: Allocation - two linked properties with separate deeds, typically condo with a garage unit
  - Family: Sale between family members
  - Partial: Home was not completed when last assessed (associated with New Homes)

## Data Quality Notes
- Missing values are represented as "NA" in categorical variables
- Some numerical variables may have 0 values which could represent missing data (e.g., no garage, no basement)
- The dataset contains both numerical and categorical variables
- Some variables are ordinal (quality ratings) while others are nominal (neighborhood, style)

## Usage Recommendations
- This dataset is ideal for regression analysis and machine learning tasks
- Consider feature engineering for categorical variables (one-hot encoding, label encoding)
- Pay attention to missing values and their implications
- The target variable (SalePrice) is continuous and suitable for regression models
- Consider log transformation of the target variable if it shows high skewness

## File Information
- **Dataset Name**: Ames Housing Dataset
- **Total Features**: 79 explanatory variables + 1 target variable
- **Total Records**: 2,930 properties
- **File Format**: CSV
- **Encoding**: UTF-8
- **Delimiter**: Comma
