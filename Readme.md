The FlexBox tutorial --Started on-- 24.2.2021
Contains a list of folders to discuss every component and tag
Also has a Basic.html which contains a starting pad for learning all the Flexbox stuff.
You can apply styles on two types of Flex items : 1.Flex-Container 2.Flex-Items
#Attributes and where to apply them => 

Syntax=> attribue : defaultValue {Other Values}

-----------------Flex-Container---------------------
-> flex-direction : row {value:row||column||row-reverse||column-reverse}
-> flex-wrap : nowrap {value:wrap||nowrap||wrap-reverse}
-> flex-flow : flex-direction flex-wrap *A shorthand function for specifying both flex-direction and flex-wrap
-> justify-content : flex-start {value:flex-start||flex-end||space-around||space-between} 
-> align-items : stretch {value:stretch||flex-start||flex-end||center||baseline}
-> align-content : stretch {value:stretch||flex-start||flex-end||center||space-around||space-between}


-----------------Flex-Items--------------------------
-> *The direct child elements of flex-container automatically becomes flexible-items.
-> order : 0 {value:anyNumber}
-> flex-grow : 0 {value:anyPositiveNumber || 0}
-> flex-shrink : 1 {value:anyPositiveNumber || 0}
-> flex-basis : value {value:initialSizeOfTheItem}
-> align-self : stretch {value:stretch||flex-start||flex-end||center}
-> flex : (flex-grow, flex-shrink, flex-basis)*A shorthand function for specifying all flex-grow, flex-shrink and flex-basis


-----------------------Some Examples in the project------------------------------
-> Responsive Image Grid
