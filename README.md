# LegoData
LEGO blind-bag minifigurine (a.k.a. minifig) data collected from BrickLink (before that website's acquisition by The Lego Group).

Blind-bagged LEGO minifigs are sold in opaque packaging which obscures each bag's contents. These blind-bags are periodically released in sets, called series, which contain several possible minifig sets (where a 'minifig set' means a minifigurine and all other LEGO pieces contained within its bag). Several methods and guides (e.g. 'feel guides') are produced by third parties which assist consumers in accurately determining which minifig's set is contained within a given bag. 

# Motivation
LEGO minifigs and their accessories are known to appreciate in value [Todo: find article]. We seek the ability to predict which specific minifig sets will appreciate the most when only obvious and simply determined factors are known about the sets. This forecasting will be completed using multiple regression analysis. Along the way we will verify our initial assertion that the value of LEGO pieces appreciates over time. 

# Background
 Data was initially collected in an Excel spreadsheet; then converted to CSV file. Multiple regression analysis were initially run using the Minitab software package.

# Format

* # Identification Variables
| Variable Name | Number | Variable Type | Data Type | Notes |
|------------|------|-----------|-------|--------|
| Name | Var1 | Label | Alpha | Official minifig set title |
| Series | Var2 | Categorical | Integer | Blind-bag series number |

* # Price Variables
| Name                         | Number | Variable Type | Data Type | Notes                                                            |
|------------------------------|--------|---------------|-----------|------------------------------------------------------------------|
| Used Sales Data              | Var3   | Numeric       | USD       | Average cost per used minifig set in last six months         |
| Used Minifig-only Sales Data | Var4   | Numeric       | USD       | Average cost per used minifig (without additional pieces) in last six months |
| New Sales Data               | Var5   | Numeric       | USD       | Average cost per new complete minifig set in last six months          |
| Leg Sales                    | Var6   | Numeric       | USD       | Average cost per lot of used leg piece                           |
| Torso Sales                  | Var7   | Numeric       | USD       | Average cost per lot of used torso piece                         |
| Head Sales                   | Var8   | Numeric       | USD       | Average cost per lot of used head piece                          |
| Hair/Hat Sales               | Var9   | Numeric       | USD       | Average cost per lot of used hair/hat piece                      |

* # Mass Variables
| Name               | Number | Variable Type | Data Type | Notes                                    |
|--------------------|--------|---------------|-----------|------------------------------------------|
| Mass (complete)    | Var10  | Numeric       | Grams (g) | Mass of complete minifig set              |
| Mass (figure-only) | Var11  | Numeric       | Grams (g) | Mass of minifig (without additional pieces) |

* # Categorical Variables
| Name        | Number | Variable Type | Data Type | Notes                                                                                                                 |
|-------------|--------|---------------|-----------|-----------------------------------------------------------------------------------------------------------------------|
| Gendered    | Var12  | Categorical   | Boolean   | does the minifig obviously present as female?                                                                          |
| Human       | Var13  | Categorical   | Boolean   | is the minifig obviously meant to be human?                                                                            |
| HeadOnly    | Var14  | Categorical   | Boolean   | did the minifig's head piece come from one mold? (i.e. not multiple pieces?)                                           |
| BodySuit    | Var15  | Categorical   | Boolean   | is the minifig some sort of suited character? (e.g. hot dog suit, chicken man)                                         |
| LivingAddOn | Var16  | Categorical   | Boolean   | does this minifig set come with multiple entities which would animate during a "Indian in the Cupboard" scenario? |
| Handsfull   | Var17  | Categorical   | Boolean   | does this minifig come with enough accessories to fill its hands?                                                  |

* # Piece Data
| Name                  | Number | Variable Type | Data Type | Notes                                                                               |
|-----------------------|--------|---------------|-----------|-------------------------------------------------------------------------------------|
| Number of Accessories | Var18  | Categorical   | Int       | Number of parts contained within completed minifig set, but not within the minifig's listing |
| Number of Parts       | Var19 | Categorical   | Int       | Number of parts contained in the minifig set                                         |

