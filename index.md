## Exercise1 

### **Formatted text in Markdown**

**_Italic text_**

-Writing in Markdown is _not_ that hard! 

**Bold text**

-I **will** complete these lessons!

**Both together in same sentence**

-"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!" 

**Both together in same words**

-If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

### **Headers in Markdown**
# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six  

### **Search for it!**
[Search for it.](www.google.com)

[You're **really, really** going to want to see this.](www.dailykitten.com)

#### The Latest News from [the BBC](www.bbc.com/news) 

**More searhing!**

Do you want to see something fun? [a fun place]

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com 

### **Tiger and cats**
![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

### **Blockquotes**
I read this interesting quote the other day:

> "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

**And one more**
>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
>
>His father told him that story: his father looked at him through a glass: he had a hairy face.
>
>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

**Vive L'Irlande!**
>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

### **Make some lists**

**Shopping list**
* Flour
* Cheese
* Tomatoes

**A recipe**
1. Cut the cheese 
2. Slice the tomatoes
3. Rub the tomatoes in flour

**A bit of latin**
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

**Who is he?**
* Calculus
    * A professor
    * Has no hair
    * Often wears green
* Castafiore
    * An opera singer
    * Has white hair
    * Is possibly mentally unwell
  
**Wanna know how to cut the cheese?**
1. Cut the cheese
  
 Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes
  
 Be careful when holding the knife.
 
 For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_. 
 
### **Paragraphs**

**Empty spaces**

We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.

**A recipe again** 
1. Crack three eggs over a bowl.   
Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

## Exercise 2

**Markup languages**

**SGML** (_Standard Generalized Markup Language_) specified a syntax for including the markup in documents. It descended from IBM's Generalized Markup Language (GML). SGML was originally designed in 1986 to enable the sharing of machine-readable large-project documents in government, law, and industry. SGML is properly _a meta-language_, and many markup languages are derived from it. There are three versions of it: Original _SGML_, _SGML (ENR)_ and _SGML (ENR+WWW or WebSGML)_. SMGL(ENR) resulted from a Technical Corrigendum to add extended naming rules allowing arbitrary-language and -script markup and SMGL (ENR+WWW or WebSGML) resulted from a Technical Corrigendum to better support XML and WWW requirements. Most substantial markup languages have been based on the SGML system, for example _TEI_ and _DocBook_. 

An SGML document have three parts:
* the SGML Declaration
* the Prologue, containing a DOCTYPE declaration with the various markup declarations that together make a Document Type Definition (DTD)
* the instance itself, containing one top-most element and its contents.

![kuva](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/SGML.svg/421px-SGML.svg.png)

**EML** or **EmotionML** (_An Emotion Markup Language_) was created by the _W3C Emotion Incubator Group (EmoXG)_ in May 2014. It was created as a general-purpose emotion annotation and representation language. It's idea was to use it in a large variety of technological contexts where emotions need to be represented. _Emotion-oriented computing_ is gaining importance as interactive technological systems become more advanced. To represent users the emotional states or the emotional states that has been simulated by a user interface requires a suitable representation format for example _markup language_. For example DocBook SGML and LinuxDoc uses SGML tools. 

## Exercise 3

Do you want to see a cat picture?  
[Click here to see](https://omaelainklinikka.fi/wp-content/uploads/2020/08/kissanpentu-sangylla.jpg) 

Want to learn more about Markdown? 

[![](https://img.youtube.com/vi/HUBNt18RFbo/maxresdefault.jpg)](https://www.youtube.com/watch?v=HUBNt18RFbo)

      
## Exercise 4
```C#
public class Person{  
  private string name;  
  private int age;  

  public Person(string initialName)  
  {  
    this.age = 0;  
    this.name = initialName;  
  }  
  public void PrintPerson()  
  {  
    Console.WriteLine(this.name + ", age " + this.age + " years");  
  }  
  public void GrowOlder()  
  {  
    this.age = this.age + 1;  
  }  
}  
```