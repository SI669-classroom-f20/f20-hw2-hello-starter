# HW 2: Hello Hello Hello!

Follow these steps to get your project ready to work on:

1. `cd` into  the directory you will work in (e.g., <669dir>/hw2)
2. clone this repo into your hw2 directory
3. cd into the new directory (e.g., `$ cd hw2-hello-numerator`)
4. create a new expo project called "hw2Hello" (`$ expo init hw2Hello`)
5. cd into the expo project directory (`$ cd hw2Hello`)
6. remove the `.git` directory that is created by expo init (`$ rm -rf .git`). Make sure you do this in the `hw2Hello` diretory and NOT in the directory that was cloned from GitHub.
7. start working on your project


You will start with a blank app, and your job is to modify it to look like this:<br/>
<img src="https://github.com/SI669-classroom-f20/f20-hw2-hello-starter/blob/master/helloApp.png?raw=true" width=300/>
<br/>

### Grading (up to 120 points)
| No. | Requirement  | Points |
| --- | ------------- | ------------- |
| 1 | First text label looks very similar to first label in reference image | 30  |
| 2 | Second text label looks very similar to second label in reference image | 30 |
| 3 | Third text label looks very similar to third label in reference image | 30 |
| 4 | Screen background looks very similar to background in reference image | 20 |
| | **Total** | **120**


## Extra credit (Up to 4 points):
Add an interactive panel that, when you tap it, displays "Hello" in a different language, randomly selected from the values contained in the following JavaScript object:

```
const hellos = {
  Arabic: "Marhaba",
  BavarianAndAustrianGerman: "Grüß Gott",
  Bengali: "Namaskar",
  Bulgarian: "Zdraveite",
  Catalan: "Hola",
  Chamorro: "Hafa adai",      
  Chinese: "Nǐ hǎo",
  Croatian: "Dobar dan",
  Danish: "God dag",
  Dutch: "Hallo",
  Finnish: "hyvää päivää",
  French: "Bonjour",
  Gaeilge: "Dia dhuit",
  German: "Guten tag",
  Greek: "Yasou",
  Hebrew: "Shalom",
  Hindi: "Namaste",
  Hungarian: "Jo napot",
  Icelandic: "Góðan dag",
  Igbo: "Nde-ewo",
  Indonesian: "Selamat siang",
  Italian: "Salve",
  Japanese: "Konnichiwa",
  Korean: "Ahn nyong ha se yo",
  Latin: "Salve",
  Lithuanian:  "Sveiki",
  Luxembourgish: "Moïen",
  Maltese: "Bonġu",
  Nahuatl: "Niltze",
  Nepali: "Namastē",
  Norwegian: "Hallo",
  Persian: "Salam",
  Polish: "Cześć",
  Portuguese: "Olá",
  Romanian: "Bună ziua",
  Russian: "Zdravstvuyte",
  Serbian: "Zdravo",
  Slovak: "Ahoj",
  Spanish: "Hola",
  Swahili: "Hujambo",
  Swedish: "Hallå",
  Tahitian: "Ia orna",
  Thai: "Sawasdee",
  Tsonga: "Avuxeni",
  Turkish: "Merhaba",
  Ukrainian: "Zdravstvuyte",
  Urdu: "Assalamo aleikum",                                
  Vietnamese: "xin chào",
  Welsh: "Shwmae",
  Zulu: "Sawubona" 
}
```

Please check out the [demo video](https://www.loom.com/share/f0153edb300d4ae0b22611a4379ffe69) to see how this should work.

### Grading

| No. | Requirement  | Points |
| --- | ------------- | ------------- |
| X1 | Fourth panel displays at least one "Hello" phrase from the provided object | 1  |
| X2 | Fourth panel receives user input and changes its display in some way when pressed | 1 |
| X3 | Fourth panel displays a randomly selected "Hello" phrase every time it is pressed | 2 |
| | **Total** | **4**
