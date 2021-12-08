
## This conatins all commnds for using angular cli > **10**

> `npm install -g @angular/cli`

#### On windows you needs to add below paths to access all ng commands from CMD
> ADD -> C:\YOUR_USERNAME\bhagvat\AppData\Roaming\npm\node_modules\@angular\cli\bin
> ADD -> C:\YOUR_USERNAME\bhagvat\AppData\Roaming\npm

## Install Angular CLI , Required Nodejs installed 

=> Create component
> `ng g component component-name`
> 
> Ex : ng g component student


=> create flat component and skip test files
> ng g component component-name -skip-tests=true --flat=true 
> Ex : ng g component student --skip-tests=true --flat=true 

=> Create component inside module ,by flat and skipping test files 
> ng g component  module_name/new_gen_component_name -skip-tests=true --flat=true
Ex : ng g component  users/student --skip-tests=true --flat=true 

=> Specific help on Component
>  ng g c --help    [here you get cli - flags for component]  

=> Create module
> ng g module module_name
Ex : ng g module user 

=> Create module with routung files 
> ng g module module_name --routing=true
Ex : ng g module users --routing= true
