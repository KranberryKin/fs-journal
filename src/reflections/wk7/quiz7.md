# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
v-bind: is used to bind certain details or properties to an child element who may need the data values.props can be used when v:bind is used, this is setting the required data type value if needed. Another way would be to to used computed and call a gernal data by it's appstate value (careful with arrays).
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
S - single
P - page
A - Applicaiton
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Data values for pages can be ran more quickly with less load time. Due to the need to grab and load another html fild/page. instead using data alredy obtained and just using a template to place the data on the same page no load/searching.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted means when the page is loaded, do these actions/ run these functions.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
When I create forms and need their inputs to be referenced. I can get a reference by using a v-model and calling it. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
@ can be used in vue to add interactability and run functions when called. there is many uses after you press @.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
There are a few, onMounted as mentioned earlier runs functions when the page is loaded. There is also beforeMount where it loads functions the moment the page is called, and before it renders.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
key is what is required of and information object in order for a v-for to take place. is the key is missing the value it may not be added.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
slot is a method when using components. Often in class we use slots in models in order to reuse the same model but input different desired details within the modals. 
```