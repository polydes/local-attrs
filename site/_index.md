+++
[extra]
	blurb = "Use local attributes within events for cleaner code."
+++

This extension allows attributes to be defined within an event, for cleaner code.

The following attribute types are supported:
- Boolean (`var x:Bool = true/false;`)
- Integer (`var x:Int = 0;`)
- Number (`var x:Float = 0.0;`)
- Text (`var x:String = "";`)
- List (`var x:Array<Dynamic> = [];`)
- Map (`var x:Map<String,Dynamic> = [];`)
- Inferred (`var x = y;`, where the Haxe compiler determines the type of variable.)

Boolean, Integer, Number, Text, List, and Map have their block types set properly to work with Stencyl's design mode block type verification.