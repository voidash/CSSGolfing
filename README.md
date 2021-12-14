# CSS notes

          selector { property : value }
* what are tags and what are elements? Elements refers to collection of tags or element itself inside of opening and closing brace. Tags are just components that are parsed by the browser to perform desired rendering.

* ways to add into the HTML
   - using import keyword
      
          <style>
            @import url("stylesheet");
          </style>
    
    
* inheritance : a child node will inherit most of the properties of parent node. 

* specifity : How specific a style rule is to the desired element. The image  denotes specifity of style relating to element. The closer it is to element, more the chances to be triumpant style.

![specifity A](https://i.imgur.com/qfhfDhW.png)
![specifity B](https://i.imgur.com/yJhl7C8.png)

* ## Selectors
  - element p, a 
  - universal *
  - class based (.myClass)
  - id based #id
  - element and id can be mixed. ```div#myId``` will select only a div element with id of ```myId```
  - ### Descendant and child selectors
    - my daughter is my child and descendant. direct
    - my grandaughter is not my child but a descendant.
    - descandant selector : ```div span {color: yellow;}``` 
    
          <div>
            <p>
              <span>
                this will be changed to yellow
              </span>
           </p>
          </div>
      
     - child selector  : ```div > span {color: yellow;}```
     
           <div>
           <span>
            this will be changed to yellow because its direct descendant 
           </span>
            <p>
              <span>
                this will not be changed to yellow
              </span>
           </p>
          </div>
          
       - sibling selector ``` p + span {} ``` : if they come within same heirarchy. 
   - attribute selector : ``` a[title="test"] ``` 
   -  pseudo selectors: ```:first-child   , :lang(np) ``` 
      
      - for a tags. the dynamic pseudo selectors such as link visited focus hover active  the order matters so the mnemonic ``` :LoVe For HAte.``` will work
      - :before and :after pseudo selectors to add before and after the element we want to specify.
   
   
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
