# A UwU Cafe for QBCore Framework.
Link to the MLO: https://fivem.gabzv.com/package/4724734
Link to the vehicle: https://www.gta5-mods.com/vehicles/vapid-speedo-express-add-on-liveries

## Dependencies:
* qb-target
* qb-management
* qb-input
* qb-menu

## Add this to your @qb-core/shared/items.lua
```
-- UwuU Cafe Items
    ["shiny_wasabi"]                 	= {["name"] = "shiny_wasabi",            		["label"] = "Shiny wasabi",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "shiny_wasabi.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["onion"]                        	= {["name"] = "onion",                       	["label"] = "Onion",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "onion.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["chicken_thighs"]               	= {["name"] = "chicken_thighs",             	["label"] = "Chicken thighs",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "chicken_thighs.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["virgin_olive_oil"]             	= {["name"] = "virgin_olive_oil",          		["label"] = "Virgin olive oil",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "virgin_olive_oil.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["rice"]                         	= {["name"] = "rice",                       	["label"] = "Rice",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "rice.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["soy_sauce"]                    	= {["name"] = "soy_sauce",                     	["label"] = "Soy sauce",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "soy_sauce.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["pullman_bread"]                	= {["name"] = "pullman_bread",              	["label"] = "Pullman bread",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "pullman_bread.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["egg"]                          	= {["name"] = "egg",                       		["label"] = "Egg",             					["weight"] = 150,         ["type"] = "item",         ["image"] = "egg.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["chicken_breast"]               	= {["name"] = "chicken_breast",            		["label"] = "Chicken breast",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "chicken_breast.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["flour"]                        	= {["name"] = "flour",                       	["label"] = "Flour",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "flour.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["butter"]                       	= {["name"] = "butter",                       	["label"] = "Butter",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "butter.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["milk"]                         	= {["name"] = "milk",                       	["label"] = "Milk",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "milk.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["sea_moss"]                     	= {["name"] = "sea_moss",              			["label"] = "Sea moss",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "sea_moss.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["matcha_powder"]                	= {["name"] = "matcha_powder",               	["label"] = "Matcha powder",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "matcha_powder.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["sugar"]                        	= {["name"] = "sugar",                       	["label"] = "Sugar",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "suger.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cocoa_powder"]                 	= {["name"] = "cocoa_powder",                	["label"] = "Cocoa powder",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "cocoa_powder.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["dried_boba_tapioca_pearls"]    	= {["name"] = "dried_boba_tapioca_pearls",    	["label"] = "Dried boba tapioca pearls",     	["weight"] = 150,         ["type"] = "item",         ["image"] = "dried_boba_tapioca_pearls.png",     	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["juice"]                        	= {["name"] = "juice",                       	["label"] = "Juice",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "juice.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["lemon"]                        	= {["name"] = "lemon",                       	["label"] = "Lemon",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "lemon.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["mint"]                         	= {["name"] = "mint",                       	["label"] = "Mint",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "mint.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["noodles"]                      	= {["name"] = "noodles",                       	["label"] = "Noodles",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "noodles.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["chicken"]                      	= {["name"] = "chicken",                       	["label"] = "Chicken",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "chicken.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["baking_powder"]                	= {["name"] = "baking_powder",               	["label"] = "Baking powder",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "baking_powder.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["rice_flour"]                   	= {["name"] = "rice_flour",                   	["label"] = "Rice flour",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "rice_flour.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["awwdorable_valentines_chocolate"] = {["name"] = "awwdorable_valentines_chocolate",["label"] = "Awwdorable valentines chocolate", 	["weight"] = 150,         ["type"] = "item",         ["image"] = "awwdorable_valentines_chocolate.png",	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["booba_milk_tea_1"]             	= {["name"] = "booba_milk_tea_1",             	["label"] = "Booba milk tea Brown",             ["weight"] = 150,         ["type"] = "item",         ["image"] = "booba_milk_tea_1.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["booba_milk_tea_2"]             	= {["name"] = "booba_milk_tea_2",             	["label"] = "Booba milk tea Orange",         	["weight"] = 150,         ["type"] = "item",         ["image"] = "booba_milk_tea_2.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["brewed_coffe"]                 	= {["name"] = "brewed_coffe",                	["label"] = "Brewed coffe",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "brewed_coffe.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cocoa_powder"]                 	= {["name"] = "cocoa_powder",                	["label"] = "Cocoa powder",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "cocoa_powder.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["doki_doki_pancakes"]           	= {["name"] = "doki_doki_pancakes",           	["label"] = "Doki doki pancakes",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "doki_doki_pancakes.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["gingerkitty_cookie"]           	= {["name"] = "gingerkitty_cookie",           	["label"] = "Gingerkitty cookie",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "gingerkitty_cookie.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["hamburg_stake"]                	= {["name"] = "hamburg_stake",                	["label"] = "Hamburg Steak",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "hamburg_stake.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["hot_chocolate"]                	= {["name"] = "hot_chocolate",                	["label"] = "Hot chocolate",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "hot_chocolate.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["jelly_beans"]                  	= {["name"] = "jelly_beans",                  	["label"] = "Jelly beans",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "jelly_beans.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["lovely_hot_chocolate"]         	= {["name"] = "lovely_hot_chocolate",         	["label"] = "lovely hot chocolate",             ["weight"] = 150,         ["type"] = "item",         ["image"] = "lovely_hot_chocolate.png",        	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["matcha_powder"]                	= {["name"] = "matcha_powder",              	["label"] = "Matcha powder",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "matcha_powder.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["matcha_coffee"]                	= {["name"] = "matcha_coffee",               	["label"] = "Matcha coffee",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "matcha_coffee.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["meowchi_mochi_ice_cream"]      	= {["name"] = "meowchi_mochi_ice_cream",      	["label"] = "Meowchi mochi ice cream",        	["weight"] = 150,         ["type"] = "item",         ["image"] = "meowchi_mochi_ice_cream.png",       	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["noodles"]                      	= {["name"] = "noodles",                       	["label"] = "Noodles",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "noodles.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["om_nom_omurice"]               	= {["name"] = "om_nom_omurice",              	["label"] = "Om nom omurice",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "om_nom_omurice.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["nuts"]                         	= {["name"] = "nuts",                       	["label"] = "Nuts",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "nuts.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["pullman_bread"]                	= {["name"] = "pullman_bread",              	["label"] = "Pullman bread",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "pullman_bread.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["rice_balls"]                   	= {["name"] = "rice_balls",                   	["label"] = "Rice balls",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "rice_balls.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["rice_flour"]                   	= {["name"] = "rice_flour",                 	["label"] = "Rice flour",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "rice_flour.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["sea_moss"]                     	= {["name"] = "sea_moss",                     	["label"] = "Sea mossl",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "sea_moss.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["soy_sauce"]                    	= {["name"] = "soy_sauce",                   	["label"] = "Soy saucesoy sauce",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "soy_sauce.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["strawberry"]                   	= {["name"] = "strawberry",                 	["label"] = "Strawberry",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "strawberry.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["strawberry_shortcake"]         	= {["name"] = "strawberry_shortcake",        	["label"] = "Strawberry shortcake",             ["weight"] = 150,         ["type"] = "item",         ["image"] = "strawberry_shortcake.png",         	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["sugoi_katsu_sando"]            	= {["name"] = "sugoi_katsu_sando",          	["label"] = "Sugoi katsu sando",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "sugoi_katsu_sando.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["sweet_herbal_tea"]             	= {["name"] = "sweet_herbal_tea",             	["label"] = "Sweet herbal tea",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "sweet_herbal_tea.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["warm_chicken_noodle"]          	= {["name"] = "warm_chicken_noodle",        	["label"] = "Warm chicken noodle",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "warm_chicken_noodle.png",             ["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["glass_tall_dirty"]             	= {["name"] = "glass_tall_dirty",           	["label"] = "Glass tall dirty",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "glass_tall_dirty.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["bar_bowl_dirty"]               	= {["name"] = "bar_bowl_dirty",             	["label"] = "Bar bowl dirty",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "bar_bowl_dirty.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["bar_bowl"]                     	= {["name"] = "bar_bowl",                    	["label"] = "Bar bowl",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "bar_bowl.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["steak"]                        	= {["name"] = "steak",                       	["label"] = "Steak",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "steak.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["oxygen_cake"]                  	= {["name"] = "oxygen_cake",                 	["label"] = "Oxygen cake",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "oxygen_cake.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["dragos_fire_cupcake"]          	= {["name"] = "dragos_fire_cupcake",          	["label"] = "Dragos fire cupcake",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "dragos_fire_cupcake.png",             ["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["kira_kira_currye"]             	= {["name"] = "kira_kira_currye",            	["label"] = "Kira kira currye",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "kira_kira_currye.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["purrfect_parfait_ballaberry"]  	= {["name"] = "purrfect_parfait_ballaberry",  	["label"] = "Purrfect parfait ballaberry",    	["weight"] = 150,         ["type"] = "item",         ["image"] = "purrfect_parfait_ballaberry.png",   	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["ballbarry_cupcake"]            	= {["name"] = "ballbarry_cupcake",           	["label"] = "Ballbarry cupcake",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "ballbarry_cupcake.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["purrfect_parfait"]             	= {["name"] = "purrfect_parfait",            	["label"] = "Purrfect parfait",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "purrfect_parfait.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cat_macaroon_brown"]           	= {["name"] = "cat_macaroon_brown",          	["label"] = "Cat macaroon brown",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "cat_macaroon_brown.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cat_macaroon_green"]           	= {["name"] = "cat_macaroon_green",           	["label"] = "Cat macaroon green",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "cat_macaroon_green.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cat_macaroon_pink"]            	= {["name"] = "cat_macaroon_pink",            	["label"] = "Cat macaroon pink",             	["weight"] = 150,         ["type"] = "item",         ["image"] = "cat_macaroon_pink.png",             	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cat_macaroon_turquoise"]       	= {["name"] = "cat_macaroon_turquoise",      	["label"] = "Cat macaroon turquoise",          	["weight"] = 150,         ["type"] = "item",         ["image"] = "cat_macaroon_turquoise.png",       	["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["brown_dye"]                    	= {["name"] = "brown_dye",                    	["label"] = "Brown dye",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "brown_dye.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["pink_dye"]                     	= {["name"] = "pink_dye",                    	["label"] = "Pink dye",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "pink_dye.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["green_dye"]                    	= {["name"] = "green_dye",                   	["label"] = "Green dye",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "green_dye.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["turquoise_dye"]                	= {["name"] = "turquoise_dye",               	["label"] = "Turquoise dye",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "turquoise_dye.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["plate"]                        	= {["name"] = "plate",                       	["label"] = "Plate",             				["weight"] = 150,         ["type"] = "item",         ["image"] = "plate.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cup"]                          	= {["name"] = "cup",                       		["label"] = "Cup",             					["weight"] = 150,         ["type"] = "item",         ["image"] = "cup.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["cup_dirty"]                    	= {["name"] = "cup_dirty",                  	["label"] = "Cup dirty",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "cup_dirty.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["plate_dirty"]                  	= {["name"] = "plate_dirty",                 	["label"] = "Plate dirty",             			["weight"] = 150,         ["type"] = "item",         ["image"] = "cat_purple.png",             			["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
    ["ice"]                          	= {["name"] = "ice",                       		["label"] = "Ice",             					["weight"] = 150,         ["type"] = "item",         ["image"] = "ice.png",             				["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},
	["brewed_coffee"]                   = {["name"] = "brewed_coffee",                	["label"] = "Brewed Coffee",             		["weight"] = 150,         ["type"] = "item",         ["image"] = "brewed_coffee.png",             		["unique"] = false,     ["useable"] = true,     ["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},


```
## Add this to your @qb-core/shared/jobs.lua 
```
['uwu'] = {
    label = 'UwU Cafe',
    defaultDuty = true,
    offDutyPay = false,
    grades = {
        ['0'] = {
            name = 'Trainee',
            payment = 50
        },
        ['1'] = {
            name = 'Employee',
            payment = 75
        },
        ['2'] = {
            name = 'Advanced',
            payment = 125
        },
        ['3'] = {
            name = 'Manager',
            payment = 150
        },
        ['4'] = {
            name = 'Owner',
            isboss = true,
            payment = 150
        },
    },
},
```
