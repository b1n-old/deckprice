Calculates Magitc The Gatheric deck price.

Uses [Black Lotus Project](http://blacklotusproject.com/) API to get prices.

Can read plain text and  [Clockatrice](http://cockatrice.de) deck format.

{% include_code Treefolk Thematic Deck Result examples/treefolk_result.txt}

Text format for Myr Thematic Deck:
```txt
4 Palladium Myr
2 Myr Battlesphere
4 Myr Enforcer
4 Myr Galvanizer
4 Myr Reservoir
2 Mirrorworks
4 Tree of Tales
4 Vault of Whispers
4 Great Furnace
4 Seat of the Synod
4 Lodestone Myr
4 Thoughtcast
4 Darksteel Citadel
4 Silver Myr
2 Myr Turbine
2 Banefire
2 Voltaic Key
2 Ancient Den
```

Result:
```txt
2 x Myr Battlesphere  = 2 x 0.47 = 0.94
4 x Silver Myr        = 4 x 0.25 = 1.00
2 x Voltaic Key       = 2 x 0.55 = 1.10
2 x Ancient Den       = 2 x 0.67 = 1.34
4 x Myr Enforcer      = 4 x 0.37 = 1.48
2 x Myr Turbine       = 2 x 0.83 = 1.66
4 x Tree Of Tales     = 4 x 0.56 = 2.24
4 x Lodestone Myr     = 4 x 0.60 = 2.40
2 x Mirrorworks       = 2 x 1.23 = 2.46
4 x Vault Of Whispers = 4 x 0.62 = 2.48
4 x Thoughtcast       = 4 x 0.68 = 2.72
4 x Great Furnace     = 4 x 0.74 = 2.96
4 x Myr Galvanizer    = 4 x 0.75 = 3.00
4 x Seat Of The Synod = 4 x 0.75 = 3.00
4 x Myr Reservoir     = 4 x 0.80 = 3.20
4 x Palladium Myr     = 4 x 1.01 = 4.04
4 x Darksteel Citadel = 4 x 1.24 = 4.96
2 x Banefire          = 2 x 2.75 = 5.50
TOTAL: 60 cards : 46.48
```

Cockatrice format for Treefolk Thematic Deck:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cockatrice_deck version="1">
    <deckname></deckname>
    <comments></comments>
    <zone name="main">
        <card number="4" name="Bosk Banneret"/>
        <card number="4" name="Battlewand Oak"/>
        <card number="2" name="Wickerbough Elder"/>
        <card number="2" name="Leaf-Crowned Elder"/>
        <card number="2" name="Timber Protector"/>
        <card number="2" name="Cloudcrown Oak"/>
        <card number="4" name="Dauntless Dourbark"/>
        <card number="4" name="Treefolk Harbinger"/>
        <card number="4" name="Giant Growth"/>
        <card number="2" name="Naturalize"/>
        <card number="2" name="Vines of Vastwood"/>
        <card number="4" name="Wild Growth"/>
        <card number="2" name="Hurricane"/>
        <card number="2" name="Lignify"/>
        <card number="20" name="Forest"/>
    </zone>
</cockatrice_deck>
```

Result:
```txt
2  x Naturalize         = 2  x 0.12 =  0.24
2  x Hurricane          = 2  x 0.12 =  0.24
2  x Cloudcrown Oak     = 2  x 0.25 =  0.50
2  x Wickerbough Elder  = 2  x 0.25 =  0.50
4  x Giant Growth       = 4  x 0.15 =  0.60
2  x Lignify            = 2  x 0.34 =  0.68
4  x Battlewand Oak     = 4  x 0.25 =  1.00
4  x Wild Growth        = 4  x 0.25 =  1.00
4  x Bosk Banneret      = 4  x 0.25 =  1.00
2  x Vines Of Vastwood  = 2  x 0.77 =  1.54
20 x Forest             = 20 x 0.09 =  1.80
2  x Leaf-crowned Elder = 2  x 4.43 =  8.86
4  x Dauntless Dourbark = 4  x 2.66 = 10.64
2  x Timber Protector   = 2  x 6.22 = 12.44
4  x Treefolk Harbinger = 4  x 4.17 = 16.68
TOTAL: 60 cards : 57.72
```

