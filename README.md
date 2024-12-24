The Los Angeles Times' database of pesticide tests on cannabis products sold to consumers.

## About the data

California’s testing requirements for cannabis products contain major gaps. Over more than a year, a Times investigation documented the presence of potentially harmful chemicals. 

To understand what consumers are exposed to, the Los Angeles Times bought more than 150 products from licensed stores, as well as from tobacco shops and illicit vendors, and had them tested at three state-licensed labs, Anresco Laboratories, SC Labs and Infinite Chemical Analysis Labs. These samples were tested blind, and often with confirmation testing performed at a second lab. The tests were conducted from October 2023 to December 2024.

In addition, The Times also obtained data from private market tests conducted on behalf of vape manufacturer Raw Garden and the March and Ash dispensary chain as well as Infinite CAL and Anresco. Many of these findings were also sent by the testing labs to California regulators, eventually resulting in product recalls or embargoes.

The combined tests represent the first, comprehensive insight into contamination issues in California's cannabis supply chain. The full findings are published by [The Times online in an interactive table](https://www.latimes.com/california/story/2024-12-19/we-tested-cannabis-products-for-pesticides-how-dirty-is-your-weed). They also are provided here in a form that allows for further analysis.

This data may be updated if additional test results become available or state actions take place.

## Reusing the data
The Los Angeles Times is making test data available to aid public understanding of the issue, and to facilitate additional analysis by researchers, policy makers and others.

The company's Terms of Service apply. By using the data, you accept and agree to follow the Terms of Services.

It states that "you may use the content online only, and solely for your personal, non-commercial use, provided you do not remove any trademark, copyright or other notice from such Content," and that, "no other use is permitted without prior written permission of Los Angeles Times."

Reselling the data is forbidden. Any use of these data in published works requires attribution to the Los Angeles Times.

To inquire about reuse, please contact Paige St. John at paige.stjohn@latimes.com.

## Data dictionary

### [expanded-pesticide-tests.csv](https://github.com/datadesk/expanded-cannabis-pesticide-test-data/blob/main/expanded-pesticide-tests.csv)

|field                  |type   |description                                                                                                                                                                            |
|-----------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|ID                     |numeric|A unique string identifier for the test                                                                                                                                                |
|Expanded test          |string |Analysis conducted beyond 66 pesticides tested for by California                                                                                                                       |
|Harmful_Oil            |string |Presence of harmful diluting oils or synthetic THC                                                                                                                                     |
|Product_Source         |string |Place product bought if not state-licensed dispensary                                                                                                                                  |
|Testing_Lab            |string |Lab performing test                                                                                                                                                                    |
|METRC_UID              |string |Unique product identifier in California METRC system                                                                                                                                   |
|Test_Sample            |string |Unique lab testing ID                                                                                                                                                                  |
|Brand                  |string |Brand name of product                                                                                                                                                                  |
|Flavor                 |string |Flavor name of product                                                                                                                                                                 |
|Batch                  |string |Product batch                                                                                                                                                                          |
|Batch_Date             |date   |Manufactured date                                                                                                                                                                      |
|Batch_Size             |numeric|Batch size                                                                                                                                                                             |
|DCC Status             |string |Department of Cannabis Control actions                                                                                                                                                 |
|Removed_from_sale      |string |Product was removed from sale                                                                                                                                                          |
|Removed_from_sale_date |date   |Date product first removed from sale (includes confidential embargo orders)                                                                                                            |
|Finding                |string |Failed: Exceeded limits for California regulated pesticides; Pesticides: Contained pesticides above .1 ppm; Trace: Contained pesticides at lower levels; Clean: No detected pesticides.|
|Aldicarb               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Carbofuran             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Chlordane              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Chlorfenapyr           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Chlorpyrifos           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Coumaphos              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Daminozide             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Dichlorvos             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Dimethoate             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Ethoprophos            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Etofenprox             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenoxycarb             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fipronil               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Imazalil               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Methiocarb             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Mevinphos              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Paclobutrazol          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Parathion Methyl       |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Propoxur               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Spiroxamine            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Thiacloprid            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Abamectin              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Acephate               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Acequinocyl            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Acetamiprid            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Azoxystrobin           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Bifenazate             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Bifenthrin             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Boscalid               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Carbaryl               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Captan                 |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Chlorantraniliprole    |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Clofentezine           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Cyfluthrin             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Cypermethrin           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Diazinon               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Dimethomorph           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Etoxazole              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenhexamid             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenpyroximate          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Flonicamid             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fludioxonil            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Hexythiazox            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Imidacloprid           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Kresoxim Methyl        |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Malathion              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Metalaxyl              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Methomyl               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Myclobutanil           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Naled                  |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Oxamyl                 |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pentachloronitrobenzene|string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Permethrin             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Phosmet                |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Piperonyl Butoxide     |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Prallethrin            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Propiconazole          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pyrethrins             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pyridaben              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Spinetoram             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Spinosad               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Spiromesifen           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Spirotetramat          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Tebuconazole           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Thiamethoxam           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Trifloxystrobin        |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|2-Phenylphenol         |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Acetochlor             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Ametryn                |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Aminocarb              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Anthraquinone          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Azadirachtin           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Biphenyl               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Buprofezin             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Cadusafos              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Carbendazim            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Clothianidin           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Cyphenothrin           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Cyprodinil             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Cyromazine             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|DCPA (Dacthal)         |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Dinotefuran            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Diphenylamine          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Ethirimol              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Ethofumesate           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenpropathrin          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenobucarb             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenthion               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fenvalerate            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Fluopyram              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Flutriafol             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Forchlorfenuron        |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Formetanate            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Hydramethylnon         |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Isoprocarb             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Mandipropamid          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Metaflumizone          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Methoprene 2           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Methoxyfenozide        |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Metolachlor            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|p,p'-DDE               |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pendimethalin          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pentachlorobenzene     |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pentachlorobenzonitrile|string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Phenothrin             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Procymidone            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Profenofos             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Propamocarb            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Propargite             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Propyzamide            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Prometryne             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pymetrozine            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pyraclostrobin         |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pyrimethanil           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pyriproxifen           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Pentachloroanisole     |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Quinoxyfen             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Resmethrin             |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Spirodiclofen          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Terbutryn              |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Thiabendazole          |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Thiobencarb            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Triadimenol            |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Tricyclazole           |string |Pesticide level in parts per billion. NT = Not tested. ND = No detection                                                                                                               |
|Regulated_Pesticides   |numeric|Number of pesticides subject to mandatory screening                                                                                                                                    |
|Unchecked_Pesticides   |numeric|Number of pesticides excluded from mandatory screening                                                                                                                                 |

