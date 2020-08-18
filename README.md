# LegoData
Lego blind-bag minifigure sales data with other variables and analysis for correlations

# Motivation
Lego pieces are known to increase in value over time. Being able to predict which pieces will increase in value the most could therefore be lucrative.

# Tech Information
 Data collected originally in Excel spreadsheet. Converted here to CSV file. Statistics run using Minitab software package

# Format:

* # Identification Variables
| Variable Name | Number | Variable Type | Data Type | Notes |
|------------|------|-----------|-------|--------|
| Name | Var1 | Label | Alpha | Official minifigure title |
| Series | Var2 | Categorical | Integer | Blind-bag series number |

* # Price Variables
| Name                         | Number | Variable Type | Data Type | Notes                                                            |
|------------------------------|--------|---------------|-----------|------------------------------------------------------------------|
| Used Sales Data              | Var3   | Numeric       | USD       | Average cost per used complete figure in last six months         |
| Used Minifig-only Sales Data | Var4   | Numeric       | USD       | Average cost per used minifig without add-ons in last six months |
| New Sales Data               | Var5   | Numeric       | USD       | Average cost per new complete figure in last six months          |
| Leg Sales                    | Var6   | Numeric       | USD       | Average cost per lot of used leg piece                           |
| Torso Sales                  | Var7   | Numeric       | USD       | Average cost per lot of used torso piece                         |
| Head Sales                   | Var8   | Numeric       | USD       | Average cost per lot of used head piece                          |
| Hair/Hat Sales               | Var9   | Numeric       | USD       | Average cost per lot of used hair/hat piece                      |

* # Mass Variables
| Name               | Number | Variable Type | Data Type | Notes                                    |
|--------------------|--------|---------------|-----------|------------------------------------------|
| Mass (complete)    | Var10  | Numeric       | Grams (g) | Mass of complete minifigure              |
| Mass (figure-only) | Var11  | Numeric       | Grams (g) | Mass of figure without additional pieces |

* # Categorical Variables
| Name        | Number | Variable Type | Data Type | Notes                                                                                                                 |
|-------------|--------|---------------|-----------|-----------------------------------------------------------------------------------------------------------------------|
| Gendered    | Var12  | Categorical   | Boolean   | does the figure obviously present as female?                                                                          |
| Human       | Var13  | Categorical   | Boolean   | is the figure obviously meant to be human?                                                                            |
| HeadOnly    | Var14  | Categorical   | Boolean   | did the figure's head piece come from one mold? (i.e. not multiple pieces?)                                           |
| BodySuit    | Var15  | Categorical   | Boolean   | is the figure some sort of suited character? (e.g. hot dog suit, chicken man)                                         |
| LivingAddOn | Var16  | Categorical   | Boolean   | does this minifigure set come with multiple entities which would come animate in a "Indian in the Cupboard" scenario? |
| Handsfull   | Var17  | Categorical   | Boolean   | does this minifigure come with enough accessories to fill its hands?                                                  |

* # Piece Data
| Name                  | Number | Variable Type | Data Type | Notes                                                                               |
|-----------------------|--------|---------------|-----------|-------------------------------------------------------------------------------------|
| Number of Accessories | Var18  | Categorical   | Int       | Number of parts contained within completed set, but not within minifigure's listing |
| Number of Parts       | Var 19 | Categorical   | Int       | Number of parts contained in minifigure set                                         |
