# Exercise
---
Try building a prompt using these building blocks in your LLM like ChatGPT, Gemini or Claude.

### Initial Prompt
---
**The Directive**: Your task is to write a list of 20 objects that we would use now that The Victorians used. 

**Examples**: Small notebooks -> Some people take notes on notebooks. Shillings -> People still use cash money or coins. The lightbulb etc.

**Role**: You are a history professor with a focus on The Victorians. 

**Output formatting**: Give me the list in a table format. The items name and the reason why should be in the table.

**Output style**: You like explaining things curtly.

**Additional information**: You are preparing this content for primary school students.

### Test Result
---

| Victorian Object | Why We Still Use It |
| :--- | :--- |
| **The Flushing Toilet** | It's the cleanest and easiest way to get rid of human waste. Simple. |
| **Postage Stamps** | If you want to mail a physical letter, you still need a stamp. |
| **The Telephone** | We call them mobile phones now, but it's the same idea: talking over distances. |
| **The Lightbulb** | It’s still the main way we light up our homes when it gets dark. |
| **Bicycles** | A good way to get exercise and travel without using a car. |
| **Trains** | They are still one of the fastest ways to travel across land. |
| **Cameras** | We all take pictures, though now they are mostly on our phones. |
| **Sewing Machines** | The quickest way to make and mend clothes at home. |
| **Soap Bars** | A very simple and effective way to wash your hands and body. 🧼 |
| **Tin Cans** | They keep food fresh for a very long time on a shelf. |
| **Christmas Cards** | People still send them to family and friends every December. |
| **Chocolate Bars** | A popular sweet treat. The Victorians invented the first solid ones. 🍫 |
| **Public Parks** | We still need green spaces in our cities for walks and playing. |
| **Post Boxes** | You still put your letters in these big red boxes for the postman. |
| **Jeans** | They were invented as tough work trousers and are now worn by everyone. |
| **Ice Cream** | It's a delicious frozen dessert, perfect for a hot day. 🍦 |
| **Keys and Locks** | To keep our houses and our things safe and secure. |
| **Rubber Tyres** | Cars, buses, and bikes all need them to move smoothly. |
| **Safety Pins** | A quick and easy way to fasten cloth together. |
| **Umbrellas** | They work perfectly to keep the rain off your head. ☂️ |

### Identify Issues
---
1. No numbers there should be numbers of the items.
2. The columns and rows should be seperated by lines.
3. Should not use emojis.


### Implement Improvements
---
**The Directive**: Your task is to write a list of 20 objects that we would use now that The Victorians used. 

**Examples**: Small notebooks -> Some people take notes on notebooks. Shillings -> People still use cash money or coins. The lightbulb etc.

**Role**: You are a history professor with a focus on The Victorians.

**Output formatting**: Give me the list in a table format. The number of the item on the first column, the name of the item on the second column, the reason why on the third column. You must give the list in markdown (.md) formatting. You must not use emojis. Rows and Columns must be seperated by thin lines. You must give me the response in its raw format without rendering.

**Output style**: You like explaining reasons curtly but surely.

**Additional information**: You are preparing this content for primary school students. You are using markdown format (.md) because of the presentation.

### Test Result
---