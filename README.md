# LegoData
Lego blind-bag minifigure sales data with other variables and analysis for correlations

# Motivation
Lego pieces are known to increase in value over time. Being able to predict which pieces will increase in value the most could therefore be lucrative.

# Tech Information
 Data collected originally in Excel spreadsheet. Converted here to CSV file. Statistics run using Minitab software package

# Contribute
Best way to help is to collect more data. Write a script to scrape data from Bricklink website

# Format:
VarNumber: Variable name: Data type: Variable type: Description

* # Identification Data
  * Var1: Name: Alpha: Identifier
  * Var2: Series: Int: Categorical: Blind-bag series number

* # Price Data
  * Var3: Used Sales Data: USD: Numerical: Average cost per used completed figure in last six months
  * Var4: Used Minifig Sales Data: USD: Numerical: Average cost per used minifigure without add ons in last six months
  * Var5: New Sales Data: USD: Numerical: Average cost per new completed figure in last six months
  * Var6: Leg Sales Data: USD: Numerical: Average cost per lot of used legs of minifigure
  * Var7: Torso Sales Data: USD: Numerical: Average cost per lot of used torso of minifigure
  * Var8: Head Sales Data: USD: Numerical: Average cost per lot of used head of minifigure
  * Var9: Hair/hat Sales Data: USD: Numerical: Average cost per lot of used hair/hat of minifigure

* # Mass Data
  * Var10: Mass Complete: Grams: Numerical: Mass of complete minifigure in grams
  * Var11: Mass Minifigure: Grams: Numerical: Mass of minifigure without addons in grams

* # Categorical Booleans
  * Var12: Gendered: Boolean: Categorical: If the figure is obviously feminine
  * Var13: Human: Boolean: Categorical: If the figure is obviously human
  * Var14: HeadOnly: Boolean: Categorical: If the figure has a single molded head piece and not a head and hat or hair
  * Var15: Bodysuit: Boolean: Categorical: If the figure is some sort of suited character (e.g. hot dog suit, chicken man)
  * Var16: LivingAddOn: Boolean: Categorical: If the figure comes with another entity which is implied to be alive
  * Var17: Handsfull: Boolean: Categorical: If the figure contains enough accessories to fill it's hands

* # Piece Data

  * Var18: Number of Accessories: Int: Categorical: Number of parts contained in completed set but not in minifigure
  * Var19: Number of Parts: Int: Categorical: Number of parts in minifigure
