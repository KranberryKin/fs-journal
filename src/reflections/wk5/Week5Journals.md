**What is the purpose of a Query String?**

A Query String is a unit where information is stored by a website, using the string which is added to the end of a url to access and store the Query String.

**What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?**

A query parameter starts whit a question mark (?). The distingguishable part between them, is that one is bracket notation([]). Which turns phrase the notation as an object({}). As for the other parmeter you use the 'and' symbol(&). It creates the phrase as an property array if so desired(color=[]).

**When do you think Query parameters would be helpful when writing your server?**

When I want to create allot objects with properties as data for an api, or when I want to create an array of potential strings/numbers.

**Mondays Link:** https://kranberrykin.github.io/BurgerShop/

**What are the three types of relationships?**

1: One to One Relationship
2: One to Many Relationship
3: Many to Many Relationship

**What are the benefits of the traditional linking of relationships instead of Embedding**

Traditional linkings can and will always return a value, but if you embed propterties. Then you have to dig into the embeddment, and access the properties.

**What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?**

The main issue with many-to-many relationships, is that when adding information to a section you can easily run out of data. There can be multiple items with the same catagory. But if we had every catagory in the books that are being added to that catagory, will use allot more data than intended and/or needed.

**Tuesdays Link:** https://kranberrykin.github.io/Greglist-auth/


**In simple terms what is a sub-document?**

A sub-document is a property that you label inside a Schema. A sub-document can be re-used as a template for more simular properties.

**When might you use a sub-document?**

When I want to create an Schema of a character, and I want a few basic skills and one super skill. Using a sub-document we can use one line to show an array of object blueprints( [{}] ). Then set the special skill to a singular object({}).

**How do you add to a collection of sub-documents? What about editing them?**

const a element as a new schema, then use the element to add a property = [{name: 'name-here'},{etc.}]. When you want to edit a sub-document. Find the object you want to edit and const it to an element. Than, access the property you want to add too with .push(), or you can access the specific [array location] and the properties the manually set them to 'strings' or nums.


**Wednesday Link:**


**What is a virtual property?**

A virtual property is an set property which is not accessable. It's simply virtual in the sense that we can all this property which may use other actual properties as it's data.

**When might you use a virtual property?**

When i would want to create a social media webpage where I can have people choose how much of their name they want display on their profile. 

**How do you search by a virtual properties value?**

once you create the virtual property on an schema, you can call that schema like user.fullname if the full-name what set up as a virutal property.

**Thursdays Link:**  Dereks Github : Group Assesment 