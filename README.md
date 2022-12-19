# Tamweeny Project:
  
  - This is a Food E-Commerce App for better easier online food shopping 
  - using (Redux) for dynamic state manegement 
  - Adding the ability to toggle between screens using navigation stucture (StackNavigator, BottomTabNavigator,tobTabNavigator)
  - including many features such as :
      - fav product 
      - add to cart 
      - choose product amount
      - rate product 
      - add new address 
      - edit adress 
      - support Arabic and English languages 
         
  
  # Project Structure 
  
  ## App.js 
   - This file creates the app structure by creating app Container and the Navigation structure as well as the state managment whether context(Providers) or redux 
  
  
  ## src folder           
   
   - components folder
      - productItem.js 
      - horizontalList.js
      - Input.js
      - productList.js
      - GreenButton.js
   
   - Redux folder 
      - actions folder
      - reducers folder
      - configration.js
      - types.js
   
   - navigation
      - introStack.js
      - loginStack.js
      - mainFlowStack (includes : bottomTabNav ,tobTabNav ,etc) 
      
    
   - screens 
      - introScreens folder
      - loginScreens folder
      - mainFlowScreens folder
     
    

# Setup

Ganerate react-native app for android 
   ```shell script
create-react-native-app 'project-name'
```
clone the project from github 
   ```shell script
git clone https://github.com/oi19/tamweeny.git
cd tamweeny
```
Run those following commands to run the app inside tamweeny folder

```shell script
npx react-native start
```



         
      
