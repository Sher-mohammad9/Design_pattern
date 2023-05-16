# What is Design Pattern?

Design Pattern basically kisi problem ko solve karane ka tarika hota hai. Alag-alag problems ke alag-alag solution pattern hote hai. Design pattern ki help se programm ko maintain, reuse kare sakte hai. Ek hi programm me ek hi problem dobara nhi aaye esliye design pattern ka use hota hai.

# What is Singleton Pattern?

Singleton pattern ek hi object create karta hai, hum phir se usi object ko create nahi kar sakte aur sari programm mein wahi ek object hi use hoga. Singleton pattern se dosara object create karte hai to singleton pahla bena hoaa object return karta hai. Es pattern ka use programm me ek hi object create karene or osi ko bar-bar use karane ke liye kiya jata hai.

# What is Factory Pattern?

Factory pattern multiple object create karane ke liye use hota hai. Yeh objects ek jaise hi hota hai, lekin unke properties aur behavior mein thoda sa difference hota hai.Factory pattern ka use is tarah ki situations mein kiya jaata hai jab hame multiple objects create karne hote hain aur unme thoda sa difference hota hai. Yeh pattern code ko maintain karne aur extend karne mein bhi help karta hai.

# What is MVC(Model View Controller) Pattern?

MVC pattern ka matlab hota hai Model-View-Controller. Yeh ek software design pattern hai jo ki software development me use kiya jaata hai. Jaise ki naam se hi pata chalta hai, MVC pattern me Model, View aur Controller parts alag-alag hote hai aur ek doosre se alag hote hai. Isse code maintain karne me aur development me madad milti hai.

- __Model__ : Is component ko data aur uske operations ke liye responsible mana jaata hai. Yeh component database se data fetch karke use View per dikhata hai. Or View se aaye data ko database me stor karata hai.

- __View__ : Is component ko user interface ka representation kehte hai. Yeh user ke interactions ko receive karta hai aur user ke interactions ke according result deta hai.

- __Controller__ : Is component ka kaam Model aur View ke beech communication ko manage karna hota hai. Yeh user input ko View se accept karta hai aur usko Model tak pahuchata hai. Iske saath hi Model me koi changes hote hai to wo View ko notify karta hai ki unhe update karna hai.
