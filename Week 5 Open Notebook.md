Digital History – when taking something physical and making it digital, there are all sorts of implications when those transformations occur
-	A cycle of how to do the different steps at different points
-	Depends on the physicality of the object
-	When it’s something in 3D, you need specific scanners to do
-	Choosing the physicality of the object isn’t just simple photography, need light, infrared, what not
-	The digital object, is not the physical object, it is meaningfully different
-	When you scan something like this, there’s a whole life cycle that get’s unearthed because of that, there’s’ semantic enrichments, the conditions of the scan, the hardware, who did it, etc.
-	Layers of data, when you take all this stuff and put it back into the physical world, a copy can be copious in the sense that it can make something meaningful
-	The copies we work with are our actual research data
-	The act of digitization isn’t about preservation or recreation but about making something new
-	The metadata layer makes things operable and interactable, and remixable

The OCR
-	Not a neutral thing, you don’t just do it and it’s done, you need to be injecting semantic information into it for it to make something meaningful
-	OCR is a very hard problem that has suddenly been solved in the last 6 months
-	About taking this unfinished digital product and transforming it for historical research
-	Comes out of mechanical sources to help things like audible and visual issues 
-	Multi-Layer Perceptron – an array of photo cells, mechanical devices that reacted to the presence of light and dark, hooked up to an electromagnetic gate
-	Is exposed to figures like numbers and letters, learning and making associations between the electricity patterns and the figures being shown
-	In 1980s, is still developing but for computers
-	This works with really well with clearly written texts, however there are more images put into texts, and so need to denoise, deskew, and change the colour grading for these images to be scanned
-	These are models that interpret individual pixels and words where you need to build different models for different types of texts and languages
-	When a model encounters something it doesn’t recognize, weird stuff happens
-	Everything has changed in the last decade with the amount of data these models have seen and their ability to recognize patterns
-	Neural network approaches start to take place
-	Back propagation (similar to reverse unconditional diffusion), making semantic correlations between word and image through machine learning on thousands of images
-	This transforms OCR, because you just need to know the weights

OCR Tutorial Facilitation
-	When you do an OCR without any editing, it turns out as a crappy version
-	The goal of the tutorial is to take all this info and make an ordered data set
-	It isn’t to clean up the OCR text itself, but to format it properly
-	What we are using is regular expressions – which detect “regular” paters of text and can correct them
-	A lot of the code in the tutorial is looking for discrepancies and flagging them where you can then go in yourself and clean it up
-	How can we use code to help?
o	The goal of the first part of the tutorial is about finding out how to clean it up, so that’s what the code does
-	Importing code 
o	The green text is comments, not actual code
o	Importing is saying to Colab, you know how to use it 
o	Re = go get the block with a regular expression
o	Re.compile = ??? 
o	Any / are all flags for regular expression
o	Fin = a bucket to throw things in
-	Have to add the “r” because python has changed since the tutorial, r = read
-	Levenstein distance is measuring the similarity between words, and determines what is different between them i.e. “cow” and “Smurf” are different at a level of 10, while “cow” and “c0w” are different at a level of 0.2
o	Lev (seq 1, seq 2)
o	Lev (“cow”, “Smurf”)
-	Have define what each function is before putting into practice, have to say “def” to make a definition
-	Are able to make page breaks when defining how to find the headings of each page
-	Chunking up text by charter
o	Can be a bit finicky because it’s done by roman numerals
o	Managed to figure it out
-	Finding and Formalizing Folis Markers
-	Finding and Normalizing Italian Summaries
-	Making a Dictionary – making key-value pairs
-	Allows you to search up where things are mentioned relative to their charter in the text
-	We can use HTML to print it in a readable text
o	HTML reads through the dictionary and makes it legible for us humans

Being able to describe what it is you want to happen is possibly more important than knowing how to code what it is you want to do

Shawn’s talk
-	Handwriting transcription is a whole different ball game compared to transcribing typed text
-	All of the code that you would use for scanning photos are integral to the 3D scanning device

Search up the never-ending museum
<img width="468" height="645" alt="image" src="https://github.com/user-attachments/assets/cd9f6bf3-1ccd-4e1b-b18a-8f3223574860" />

