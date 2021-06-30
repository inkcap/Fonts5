While not deployed as part of Fonts5.
If you wanted to make a custom element for ease of use in your application. Below is one way it could be done. The code below has not been tested. Consider it psudo code. 
This would not work for older browsers such as Internet Explorer.

Please look at the svg-with-js.css file, this may help with your implementation.

'''

    export class Fonts5 extends HTMLElement{
        constructor(){
            super()
        }
        connectedCallback(){
            this.innerHtml = `<svg class="icon ${this.getAttribute("class-list")}"><use href="./public/Images/sprites.svg#${this.getAttribute("name")}"></use></svg>`
        }
    }

'''

Html Example usage
'''

    <html>
      <body>
        <fonts5 class-list="large" name="pencil"/>
      </body>

'''
