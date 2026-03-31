
Website Link :
- Obsidian Helper ( tips & guidance on using Obsidian ) : https://obsidian.md/help/syntax
- Obsidian Developer ( build plugins and themes for Obsidian ) : https://docs.obsidian.md/Home


<h4>1. Checkbox list - Task </h4> 
- [ ] First Task
- [ ] Second Task 
- [ ] Third Task 
- [ ] testing 

=={orange}Syntax== 
```
- [ ] 
```

----

<h4>2.Call Out</h4>
>[!question]
>Do callout method have other "type" for me to use ?

> [!answer]-
> - Yes, they do have, you may refer to the website link below 
> Obsidian Callout link : https://obsidian.md/help/callouts

<h4>Tips 1 : Can callout be done in nested loop?</h4>
> [!question] Can callouts be nested?
> > [!todo] Yes!, they can.
> > > [!example]  You can even use multiple layers of nesting.

<h4>Tips 2 : You can customize your callout</h4>
- Download community ==CSS snippet== to declare your own callout UI
- website link : https://obsidian.md/help/callouts#Customize+callouts

=={orange}Syntax== 
```
>[!question]
```

-------
<h4>Code Block Environment </h4>
==JS Code Environment== 
```js
// Print message in website console
console.log("Print JS messsage to Console Panel")

// Print message in initialize id
var dataDisplay = document.getElementById("searchBar");
dataDispalay.innerHTML = "<h2>Hello World</h2>";
```

==C# Code Environment==
```CS
	// Print message in console project
	console.WriteLine("Print C# message to console project");
	
	// Make axis motor number 1 to servon on.
	int index = 1;
	Axis axisMoon = controller.AxisGet(index);
	axisMoon.AmpServoOn();
```

==Syntax ==
- *three back tick & Implement environment type ( CS /  CPP /  JS / CSS )
---







