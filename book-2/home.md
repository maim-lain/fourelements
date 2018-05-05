# Four Elements Trainer: Book 2
[*\~My list of walkthroughs and when they'll be updated\~*](https://www.patreon.com/maimlain)

<br>

- [Choose Book](https://github.com/maim-lain/fourelements/blob/master/README.md)
- [Love Route Walkthrough](https://github.com/maim-lain/fourelements/blob/master/book-2/loveroute.md)
  - [Scene Guide](https://github.com/maim-lain/fourelements/blob/master/book-2/lovescenes.md)
  
 <!---

- [Slave Route Walkthrough](https://github.com/maim-lain/fourelements/blob/master/book-2/slaveroute.md)
  - [Scene Guide](https://github.com/maim-lain/fourelements/blob/master/book-2/slavescenes.md)
- [Quest Walkthroughs](https://github.com/maim-lain/fourelements/blob/master/book-2/questwalk.md)

--->

<br>
<br>
<br>

## Game Mechanics
### Recipes:
Drink | 1 | 2
--- | ---: | ---:
Wanker | Red | Blue
Tickleberry | Green | Pink
Slapdapper | Yellow | Green
Slumpthumper | Pink | Blue
Hank | Grey | Red
Little tart | Blue | Yellow
Old juice | Grey | Blue
Coinpouch | Pink | Red

<br>

### Training Requirements:
Level | Requirement
--- | ---
6 | Battles = 6
7 | quest
8 | .

<br>
<br>
<br>
<br>
<br>
<br>

## Farm stuff:

Simple version:
- Visit farm everyday to get point
- Fuck girls who aren't pregnant
- Pregnant -> Milk -> Nipples -> Let cum
- Lever
- Leave farm

wait technically, shouldn't it be: (so milk used girls -> become pregnant -> milk again on same day)
- vist farm for point
- milk used girls
- fuck girls who aren't pregnant
- Pregnant -> Milk -> Nipples -> Let cum
- leave farm


<br>
<br>
<br>

Use Lever  
$ milked_today_used = True  
$ milked_today_pregnant = True  
$ milked += pregnant_girls  
$ milked += used_girls


#### Fresh:
Choice | Effect
--- | ---
Taunt | -1 morality
Comfort | none
Fuck | -1 morality & become preg
Set free | +1 morality



#### Used:
Choice | Effect
--- | ---
Talk | none
Milk | $ milked += used_girls ... $ milked_today_used = True
Fuck | become preg
Set free | none



#### Pregnant:
Choice | Effect
--- | ---
Taunt | -1 morality
Comfort | none
Milk | see flow chart
Fuck | -1 morality
Set free | +1 morality


Pregant milk flowchart:
- Milk -> $ milked += pregnant_girls ... $ milked_today_pregnant = True
	- Nipples
		- Let cum -> $ milked +=1 ... $ milked += pregnant_girls ... $ milked_today_pregnant = True
		- Don't let cum -> $ milked += pregnant_girls ... $ milked_today_pregnant = True
	- Milk her -> $ milked += pregnant_girls ... $ milked_today_pregnant = True



If you visit the farm on a day:  
+1 point for each girl  
when girl gets 20 points has birth and then becomes used girl.

$ milked -> $5 for each one  
$20 for birth


morality only used for slave route
