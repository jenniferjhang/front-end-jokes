# front-end-jokes
## HTML, CSS, Javascript, &amp; React jokes to brighten your day
![code jokes](https://github.com/user-attachments/assets/06c820b7-e573-4d95-813f-ffdd1c19b681)

Learning something new can take a bit of grit and encouragement to eventually thrive in it. I hope that these front-end development jokes land, and tickle your frustrations into a few laughs.

#### HTML
##### Quick question 
```html
<html>
	<head>
		<title>Quick question</title>
	</head>
	<body>
		<h1>Will you go on a date with me?</h1>
		<form>
			<input type="radio" id="yes" name="answer" value="yes" checked/>
			<label for="yes">Yes</label><br>
			<input type="radio" id="also-yes" name="answer" value="also-yes"/>
			<label for="also-yes">Yes</label><br>
		</form>
	</body>
</html>
```
##### Hard times
```html
<label for="hard-times">I'm stuck between..</label>
<select id="hard-times">
	<option> a rock</option>
	<option> a hard place</option>
</select>
```
##### On cloud nine: to be extremely happy and excited
```html
<html>
	<head>
		<title>On cloud nine</title>
		<style>
		  .slider-container {
			  display: flex;
			  flex-direction: column;
			  align-items: center;
		  }
		  .slider {
			  writing-mode:vertical-lr;
			  direction:rtl;
		  }
		</style>
	</head>
	<body>
	  <div class="slider-container">
	      <label for="cloud-9">on &#127781 nine</label>
	      <input
	          type="range"
	          min="1"
	          max="9"
	          value="9"
	          class="slider"
	          id="cloud-9"
	      />
	  </div>
	</body>
</html>
```

#### CSS
##### Elephant in the room: an obvious problem that no one wants to talk about
```css
.elephant-in-the-room {
	width: 70vw;
	height: 70vh;
	visibility: hidden;
}
```

##### Where my heart is
```css
.my-heart {
	position: on-my-sleeve;
	feelings-opacity: 0.0001;
}
```

##### Butterflies in my stomach: to feel nervous and anxious
```css
.butterflies {
	position: in-my-stomach;
	animation: flutter 3s ease-in-out infinite;
}
```

##### What Monday morning feels like
```css
.monday-morning {
	enthusiasm: 15%;
	coffee: #000000; 
	bed-hair-overflow: visible;
}
```
### JavaScript
##### Introversion vs. extroversion
```js
introverting() {
	socializing: -100;
	timeAlone: +100;
}
extroverting() {
	socializing: +100;
	timeAlone: -100;
}
ambiverting() {
	socializing: +50;
	timeAlone: +50;
}
```

##### Groundhog day: getting stuck in a forever time loop
```js
let groundHogDay = 1;

while (true) {
	let hour = 1;
	while (hour <= 24) {
		console.log(hour);
		hour++;
	}
}
```

##### When one door closes, another one opens: the end of one opportunity can lead to new opportunities.
```js
function universe() {
	let oneDoorCloses = true;
	if (oneDoorCloses) {
		console.log("It's okay that this door is closing");
		let anotherDoorOpens = true;
		console.log("Another door is open.. let's find it.");
	} else {
		console.log("Keep trying here.");
	}
};
universe();
```

##### When life gives you lemons, make lemonade: turn adversity or misfortune into a positive
```js
const whenLifeGivesYou = [
	{id: "1", what: "lemons"},
	{id: "2", what: "more lemons"},
	{id: "3", what: "even more lemons"},
	{id: "4", what: "guess what more lemons"},
];

const make = 
	  whenLifeGivesYou.map((problem) => {
		  if (problem.id === "1") {
			  return {...problem, what: "lemonade"}
		  };
		  if (problem.id === "2") {
			  return {...problem, what: "lemon sherbet"}
		  };
		  if (problem.id === "3") {
			  return {...problem, what: "limoncello"}
		  };
		  if (problem.id === "4") {
			  return {...problem, what: "lemon meringue pie"}
		  };
	  })
	  console.log(make);
```

##### Once in a blue moon: something that happens rarely
```js
const onceInABlueMoon() {
	unhinged: true,
	wearSocksAndFlipFlops: true,
	eatAt: "3AM",
	watchHIMYM: function() {
		return HIMYM.map(episode => episode.name);
}
```

##### Dating turned into if, else if, else statements
```js
function dating {
	if (date === kind && stable && alignedValues && chemistry) {
		result = "relationship";
	} else if (date === kind && stable && alignedValues) {
		result = "friendship";
	} else if (date === !stable && chemistry) {
		result = "situationship";
	} else {
		result = "thank you, next";
	}
}
```


##### Take advice with a grain of salt: to be skeptical of a biased or unreliable source
```js
function TakeNewsWithA(news) {
	var grainOfSalt = 0;
	switch (news) {
		case "Reuters":
			grainOfSalt += 1;
			break;
		case "FoxNews":
			grainOfSalt += 100;
			break;
		case "NationalEnquirer":
			grainOfSalt += 10000;
			break;
		default:
			console.log("No news is good news");
	}
	return grainOfSalt;
}
console.log("salt level (skepticism) needed in reading National Enquirer:", TakeNewsWithA("NationalEnquirer"))
```
### React JSX
##### Containers my cat likes
```jsx
function livingRoom() {
	const myCat = {
		console.log("purr.");
	};
	return (
		<>
			<div className="plushCatBed">
			</div>
			<div className="expensiveCatTree">
			</div>
			<div className="cardboardBox">
				{myCat}
			</div>
		</>
	);
};
```

##### useEffect(), for side projects that are out there
```jsx
function projects() {
	const [time, setTime] = useState(0);
	const mainProject() {
		frontEnd((time) => time + 5));
	}
	useEffect(() => {
		juggling((time) => time + 10);
		competitiveDuckHerding((time) => time + 15);
		extremeIroning((time) => time + 20);
	}, []);
}
```
