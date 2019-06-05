# **Beautiful-Water**
## A RimWorld mod for water beauty


### **What does it do?**
Makes water tiles have a beauty value, as it should.

Changes water tiles from their default 0 beauty value, to:

* Shallow Water: 1
* Shallow Moving Water: 1
* Chest-Deep Moving Water: 5 or 15 ††
* Shallow Ocean Water: 5
* Deep Ocean Water: 25†
* Deep Water: 15†

### **Why use this mod?**
I designed this because, while making a water-side cabin, I realized that the pawns do not appreciate all the work I'm putting in just for them to have a cool home.
I thought it only made sense for ocean water to have a much higher value, because of the pretty scene the pawns should be able to see from it. Unless you build a wall in the way or something, *you monster.*


### Footnotes
†
Water that you can't walk in is treated as a wall by the game, and therefore the beauty for these tiles only goes to a depth of 1. When designing this mod, I didn't know this, so I when I came to this, I decided to adjust the values of these tiles much higher.

††
I use a mod for impassable chest deep water, which similarly turns these tiles in to "wall-like" tiles. So, while using this mod, it makes sense to also boost it. But, I know most people do not use this mod.
I added some code to check whether or not this mod is loaded. If it isn't, I use the default value (5). If it is, I use the updated value (15).

Thanks to Oken for making the thumbnails, and for helping decide on the beauty values.
